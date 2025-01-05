Name: Rithigha R
intern id:CT08DS276
Project Report: Predicting Purchase Amount Using Random Forest Regression
Objective
The aim of this project is to predict customer purchase amounts in USD using demographic and shopping behavior data. A Random Forest Regressor was employed, with the dataset preprocessed using a pipeline for handling both categorical and numerical data.

Dataset Overview
Dataset: shopping_trends.csv
Size: N/A (to be detailed based on dataset size)
Key Features:
Categorical: Demographic or behavioral categories (e.g., Gender, Shopping Preferences).
Numerical: Continuous variables like Age, Income, or Time Spent Shopping.
Target Variable: Purchase Amount (USD) – the amount spent by customers.
Methodology
1. Data Preprocessing
Target and Feature Selection:
Target: Purchase Amount (USD)
Features: All columns except Customer ID and the target.
Handling Categorical Data:
Applied OneHotEncoder to transform categorical variables into numerical features.
Handling Numerical Data:
Standardized numerical columns using StandardScaler for consistency in scale.
2. Model Training
Random Forest Regressor:
Hyperparameters: Default settings (e.g., 100 trees, random_state=42 for reproducibility).
Pipeline: Combined preprocessing and model training steps to streamline data flow.
Training-Test Split:
80% of the data used for training, 20% for testing (random_state=42).
3. Evaluation Metrics
Mean Squared Error (MSE):
Measures the average squared difference between predictions and actual values.
R-squared (R²):
Indicates the proportion of variance explained by the model.
Results
Model Performance
Mean Squared Error: {mse} (update with actual value from output)
R-squared: {r2} (update with actual value from output)
Key Insights
The model's R-squared score suggests that [X%] of the variance in purchase amounts is explained by the predictors.
The error metrics provide a baseline for improvement, potentially through hyperparameter tuning or feature engineering.
Future Work
Feature Engineering:
Explore additional features, such as interaction terms or domain-specific transformations.
Hyperparameter Optimization:
Use grid search or random search to optimize the Random Forest Regressor's performance.
Model Comparison:
Benchmark the Random Forest model against other regressors like Gradient Boosting or Neural Networks.
Visualization:
Provide insights into feature importance and trends in purchase behavior.<img width="383" alt="intern 5" src="https://github.com/user-attachments/assets/a9c68819-3aae-4921-b4c8-734ca8fd8d71" />
