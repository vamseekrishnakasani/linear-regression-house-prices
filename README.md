
# Data-Visualization

# Linear Regression for House Price Prediction

This repository demonstrates the implementation of a **Linear Regression Model** to predict house prices based on their size. The model is built from scratch using Python, without predefined libraries for model creation. It includes:
- Training the model iteratively with gradient descent.
- Visualizing the decision boundary (line of best fit).
- Evaluating model performance using metrics like MAE, MSE, RMSE, and R² Score.

---

## Features
- **Custom Linear Regression**:
  - Built without using predefined machine learning models.
  - Implements gradient descent for parameter optimization.
- **Performance Metrics**:
  - Mean Absolute Error (MAE).
  - Mean Squared Error (MSE).
  - Root Mean Squared Error (RMSE).
  - R² Score and Adjusted R² Score.
- **Visualization**:
  - Plots decision boundaries and data points to illustrate model performance.
- **Test Predictions**:
  - Predicts house prices for unseen data and evaluates accuracy.

---

## Dataset
- The dataset simulates house sizes (`x_train`) in \(1000 \, \text{sqft}\) and their corresponding prices (`y_train`) in \(1000 \, \text{USD}\):
  ```python
  x_train = np.array([1.0, 2.0, 3.0, 4.0, 5.0, 6.0])
  y_train = np.array([300.0, 400.0, 500.0, 600.0, 700.0, 800.0])
