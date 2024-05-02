### Machine Learning Principles and Concepts: Regression Analysis & Data Engineering

#### Overview

In this assignment, we delve into the conventional machine learning problem of Regression, enriched with a blend of various data engineering techniques. These techniques include management of categorical features, feature engineering, normalization, dimensionality reduction, and more, all applied to a dataset of 205 car models across 25 columns.

#### Dataset

- **Size**: 205 car models
- **Columns**: 25
  - **Target Variable**: Price (last column)
  - **Features**: 24 columns (numerical and categorical)

#### Models Utilized

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree
- Random Forest
- Multilayer Perceptron

Metrics Calculated:
- Mean Squared Error
- Mean Absolute Error
- R-Squared Score

#### Techniques & Tools Applied

1. **Data Engineering Techniques**: Including categorical feature management, feature engineering, normalization, and dimensionality reduction.
2. **Hyperparameter Optimization**: Using Grid Search.
   
#### Key Findings & Results Discussion

- **Best Performing Model**: Random Forest, exhibiting the lowest mean squared error, mean absolute error, and highest R-squared score.
- **Data Standardization Insight**: The Random Forest model maintained superior performance even with standardized data, while the MLP regressor was notably sensitive to data scaling.
- **Dimensionality Reduction Insight**: Models trained on the original dimensional space generally outperformed those trained with PCA, indicating vital information may be lost during dimensionality reduction. However, the Random Forest regressor demonstrated consistency in performance even in reduced dimensional spaces.

##### [Detailed Analysis & Visualizations](#Analysis)
For comprehensive analysis, graphs comparing models, methods, and thorough insights, download the project file:
- [Download HTML File](https://1drv.ms/u/s!AiFPoorne5KpjCdqKOdduZzNzOUt?e=2e2mDr)
- [Download IPYNB File](https://1drv.ms/u/s!AiFPoorne5KpjCZI84SiyFmxr8cg?e=MsifDd)

---

### Notes for GitHub Users
- **Key Learnings**: Proficiency in implementing various regression models, applying data engineering techniques, and evaluating models using multiple metrics.
- **Demonstrated Skills**: In-depth analysis using multiple regression models, effective application of data engineering techniques, and insightful evaluation and discussion of model performance.

### Technologies & Libraries Used

1. **Pandas**: A powerful data manipulation and analysis library.
2. **NumPy**: A library for numerical operations and handling arrays in Python.
3. **Matplotlib**: A comprehensive library for creating static, interactive, and animated visualizations in Python.
   - `pyplot`: A module to provide a MATLAB-like interface for making plots and charts.
4. **Seaborn**: A statistical data visualization library based on Matplotlib.
5. **Scikit-Learn (sklearn)**: A machine learning library that provides simple and efficient tools for data analysis and modeling.
   - `decomposition`
     - `PCA`: Principal Component Analysis module.
   - `preprocessing`
     - `StandardScaler`: A module for standardizing dataset.
   - `model_selection`
     - `train_test_split`: A module for splitting data into training and testing sets.
   - `linear_model`
     - `LinearRegression`: A module for linear regression modeling.
     - `Ridge`: A module for ridge regression modeling.
     - `Lasso`: A module for lasso regression modeling.
   - `tree`
     - `DecisionTreeRegressor`: A module for regression through decision trees.
   - `ensemble`
     - `RandomForestRegressor`: A module for random forest regression modeling.
   - `neural_network`
     - `MLPRegressor`: A module for regression using multi-layer Perceptrons.
   - `metrics`
     - `mean_squared_error`: A module for calculating the mean squared error.
     - `mean_absolute_error`: A module for calculating the mean absolute error.



