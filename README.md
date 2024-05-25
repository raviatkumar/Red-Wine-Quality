# Project Title : Red Wine Quality

### Problem Statement:

The objective of this project is to develop a predictive model that can accurately predict the quality of Portuguese "Vinho Verde" wine based on its physicochemical properties. The dataset contains features representing various physicochemical attributes of the wine, such as acidity levels, residual sugar, chlorides, sulfur dioxide content, density, pH, sulphates, and alcohol content. The quality of the wine is rated on a scale from 0 to 10, with higher values indicating better quality.

The problem can be formulated as a regression or classification task, depending on how we choose to interpret the output variable. As the quality variable is continuous and ranges from 0 to 10, it can be treated as a regression problem where the goal is to predict the exact quality score of the wine. Alternatively, we can convert the quality scores into discrete classes (e.g., low, medium, high) and treat the problem as a multi-class classification task.

### Dataset 

- Input variables based on physicochemical tests:
  1. Fixed acidity
  2. Volatile acidity
  3. Citric acid
  4. Residual sugar
  5. Chlorides
  6. Free sulfur dioxide
  7. Total sulfur dioxide
  8. Density
  9. pH
  10. Sulphates
  11. Alcohol

- Output variable based on sensory data:
  12. Quality (score between 0 and 10)

Based on these metrics, the algorithm with the lowest MSE, RMSE, and MAE scores, and the highest R^2 and Adjusted R^2 scores is Random Forest. Therefore, Random Forest is performing the best among the provided algorithms.
