Sales Prediction - Machine Learning Project

This project focuses on building and evaluating machine learning models to predict sales based on given features. It involves feature selection, data preparation, model training, and performance evaluation.

- **To install dependencies**
  - pip install -r requirements.txt


Project Workflow

- **Feature Selection**
  - Conducted correlation analysis to eliminate irrelevant features.

- **Data Preparation**
  - Splitted the dataset into a **75:25 Train-Test Ratio**.
  - Applied **feature scaling** for better model convergence.

- **Model Building**
  - Trained and tested multiple models:
    - Random Forest
    - Decision Tree
    - XGBRegressor
    - Ridge Regression
    - Linear Regression

- **Model Evaluation**
  - Performance measured using:
    - Mean Squared Error (MSE)
    - Root Mean Squared Error (RMSE)
    - R-Squared (R²)

- **Best Model Selection**
  - Identified the most reliable model based on evaluation metrics.

# Technologies Used

- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

# Visualizations

- Correlation heatmaps
- Prediction vs Actual plots
- Residual error plots
