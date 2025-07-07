# House-Price-Prediction
Predict house prices using multiple regression techniques including Linear, Ridge, Lasso, and Decision Tree regressors on a real estate dataset.

## Introduction
This project aims to predict house prices using various regression models. It involves data preprocessing, feature engineering, and model evaluation on the House Prices dataset from Kaggle. The goal is to determine the best performing model for predicting house prices.

## Technology Stack
Python: For data analysis and modeling.
Pandas, NumPy: Data manipulation and numerical operations.
Matplotlib, Seaborn: Data visualization.
Scikit-Learn: Machine learning algorithms and metrics.

## Methodology
Data Cleaning: Handle missing values and outliers.
Feature Engineering: Encode categorical variables and select relevant features.
Model Training: Train and evaluate Linear Regression, Ridge Regression, Lasso Regression, and Decision Tree Regressor models.
Model Evaluation: Assess model performance using MAE, MSE, RMSE, and R-squared metrics.

## Model Performance Metrics

| Metric                | Lasso Regression | Ridge Regression | Decision Tree Regression | Linear Regression |
|-----------------------|-------------------|------------------|---------------------------|--------------------|
| **Mean Absolute Error (MAE)** | 16,003.10          | 15,996.73         | 22,663.57                 | 16,004.77          |
| **Mean Squared Error (MSE)**   | 464,862,900        | 464,628,800       | 1,076,528,000             | 464,924,300        |
| **Root Mean Squared Error (RMSE)** | 21,560.68         | 21,555.25        | 32,810.48                 | 21,562.10          |
| **R-squared**                | 0.9049            | 0.9049            | 0.7798                    | 0.9049             |

Best Model: Ridge Regression.


## Conclusion
Ridge Regression outperformed other models in predicting house prices. The model achieved the best balance between bias and variance, making it suitable for real estate price prediction tasks.


