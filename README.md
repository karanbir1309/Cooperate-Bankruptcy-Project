This repository contains the implementation of a Corporate Bankruptcy Prediction model designed to analyze financial data and predict the likelihood of company bankruptcy using machine learning techniques. It covers data preprocessing, feature selection, and model implementation, utilizing algorithms like Logistic Regression, Random Forest, Gradient Boosting (XGBoost, LightGBM), and Neural Networks. The project also includes exploratory data analysis, hyperparameter tuning, and evaluation metrics such as accuracy, precision, recall, and ROC-AUC scores.
**Problem:**
It is a classification problem. As bankruptcy due to business failure can negatively affect the enterprise as well as the global economy, it is crucial to understand and predict whether a company is showing symptoms of getting bankrupt or not. The problem statement is to develop a prediction model which will predict whether a company can go bankrupt or not. This will help the company to take appropriate decisions.

**Dataset:**
The data is collected from Taiwan Economic Journal for the years 1999 to 2009. Company bankruptcy was defined based on the business regulations of the Taiwan Stock Exchange. The dataset consists of multiple financial ratio columns such as:

Return on Assets (ROAs)
Gross Profits
Operating & Net income and Expenses
Cash flows
Taxes
Growth rate
Debt
Turnover, Revenue, Liability, etc.
All the features are normalized in the range 0 to 1.

The target column is “Bankrupt?” (0: No, 1: Yes).

It is a highly imabalanced data.

Source : https://archive.ics.uci.edu/ml/datasets/Taiwanese+Bankruptcy+Prediction
