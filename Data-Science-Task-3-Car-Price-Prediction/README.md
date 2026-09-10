# Car Price Prediction with Machine Learning

## Project Overview

This project predicts the selling price of used cars using machine learning.

The analysis includes data cleaning, feature engineering, exploratory data analysis, categorical encoding, model training, and model evaluation.

## Dataset

The project uses the Car Dekho vehicle dataset.

Important features include:
- Car Name
- Year
- Selling Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

## Feature Engineering

Two new features were created:
- Car Age — calculated from the year of the car
- Brand — extracted from the car name

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Analysis Performed

- Data loading and inspection
- Missing-value and duplicate checking
- Data cleaning
- Feature engineering
- Selling-price distribution
- Selling price by fuel type
- Selling price vs car age
- Correlation heatmap
- Categorical feature encoding
- Train/test split

## Machine Learning Models

Two regression models were trained:

1. Linear Regression
2. Random Forest Regressor

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The model with the better R² score was selected as the best-performing model.

## Feature Importance

Feature importance analysis was performed to identify the most influential features for predicting car selling prices.

## Conclusion

This project demonstrates how exploratory data analysis and machine learning can be used to predict used car selling prices and understand the factors that influence vehicle prices.