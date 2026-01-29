Project Overview:
This project involves building a Linear Regression model to predict house prices using the California Housing dataset. The goal is to understand the relationship between various housing features and the target median house value, while evaluating model accuracy through standard regression metrics.

Tech Stack:
Language: Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib
Dataset: California Housing (Scikit-learn built-in)

Implementation Workflow:
1. Data Exploration & Inspection
Action: Loaded the dataset into a Pandas DataFrame and performed an initial inspection using .head(), .info(), and .describe().
Goal: To verify data types, check for missing values, and understand the numerical ranges of features like median income and average rooms.
2. Model Development
Splitting: Separated the data into Training and Testing sets using train_test_split with a fixed random_state for reproducibility.
Training: Fitted a LinearRegression() model to the training data to calculate the line of best fit.
3. Evaluation & Visualization
Prediction: Generated predictions on the test set and created a comparison table of Actual vs. Predicted values.
Metrics: Calculated Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to measure the average prediction error.
Visuals: Created a scatter plot to visually assess the correlation between actual and predicted house prices.
