# Predicting House Prices using Linear Regression Models

This project signifies the second milestone in my journey of transitioning into the world of data science.
Throught this project, I utilised linear regression techniques to predict house prices in Malaysia using a public dataset from Kaggle. It includes exploratory data analysis, preprocessing, and modeling with multiple regularized regression methods, with a focus on Lasso Regression for performance and interpretability.

The dataset used in this project is available on Kaggle:

**[Malaysian House Price Regression](ttps://www.kaggle.com/datasets/mcpenguin/raw-malaysian-housing-prices-data/data)**
# Project Summary

This project predicts the prices of houses in Malaysia given a variety of features such as:
- Property size (sq.ft.)
- The type of property
- Number of bedrooms and bathrooms
- Available facilities
- Location and other relevant attributes.

Using a publicly available dataset from Kaggle, the analysis includes:
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Machine Learning
- Hyperparameter Tuning
- Model Comparison of various linear regression models:
    - Ordinary Least Squares (OLS)
    - Ridge Regression
    - Lasso Regression
    - Elastic Net

## Results
- Lasso Regression was optimised with LassoCV to produce the best performing model.
- Lasso improves interpretability by shrinking irrelevant feature coefficients to zero.

| Metric | Value |
|--------|-------|
|Best Alpha |0.001|
|R² (Log Scale, Test) |0.757|
|RMSE (Log Scale, Test) |0.289|
|MAE (Log Scale, Test) |0.215|

- Residual and predicted vs. actual plots confirm the model generalizes well with no major bias or variance issues.

## Future Improvements
- Experiment with ensemble models or stacking.
- Further feature engineering to improve model performance.
- Handle outliers and rare categories more robustly.
