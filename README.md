Predicting Online News Popularity with Machine Learning

This project explores how we can predict the number of shares an online news article might get using machine learning techniques. The dataset comes from real Mashable articles and includes social media metrics and content features.

Project Summary
Objective: Estimate how popular a news article will be, measured by its number of shares.

Dataset: Online News Popularity dataset from the UCI Machine Learning Repository.

Approach: Tested multiple regression models including CatBoost, Random Forest, XGBoost, and Ridge Regression.

Metric: Used Root Mean Squared Error (RMSE) to evaluate model performance.

Tools and Libraries
pandas, numpy, scikit-learn, matplotlib, seaborn

CatBoost and XGBoost for boosted models

newspaper3k and BeautifulSoup for article parsing

Google Colab as the main environment

How to Use
Clone the repository:
git clone https://github.com/snripesh/PythonProject.git
Open the notebook in Google Colab.

Upload the dataset file OnlineNewsPopularity.csv when prompted.

Run through the notebook to clean data, train models, and make predictions.

Key Takeaways
Among the models tested, CatBoost and XGBoost gave the most accurate results. These models were particularly effective at handling the dataset's mix of numerical and categorical features.
