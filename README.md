# Boston Housing Price Prediction

This project aims to predict housing prices in Boston using machine learning techniques. The dataset used in this project is the Boston house-price data collected by Harrison, D. and Rubinfeld, D.L. in 1978.

## Project Overview

The goal of this project is to develop machine learning models that can accurately predict median house prices in Boston based on various features such as crime rate, average number of rooms, pupil-teacher ratio, etc.

### Dataset Description

The dataset contains the following features:

1. CRIM: Per capita crime rate by town
2. ZN: Proportion of residential land zoned for lots over 25,000 sq.ft.
3. INDUS: Proportion of non-retail business acres per town
4. CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
5. NOX: Nitric oxides concentration (parts per 10 million)
6. RM: Average number of rooms per dwelling
7. AGE: Proportion of owner-occupied units built prior to 1940
8. DIS: Weighted distances to five Boston employment centers
9. RAD: Index of accessibility to radial highways
10. TAX: Full-value property-tax rate per $10,000
11. PTRATIO: Pupil-teacher ratio by town
12. B: The result of the equation B=1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
13. LSTAT: Percentage of lower status of the population

### Models Used

1. Gradient Boosting Regression
2. Random Forest Regression
3. Linear Regression

## Results

- Gradient Boosting Regression:
  - RMSE on test data: 24.69
  
- Random Forest Regression:
  - RMSE on test data: 2.81
 
- Gradient Boosting Regression after outlier removal:
  -RMSE on test data: 2.18

## Further Improvements

1. Experiment with different models and hyperparameters to improve predictive performance.
2. Explore additional feature engineering techniques to enhance model accuracy.
3. Consider incorporating more recent data if available to capture changes in housing prices over time.



