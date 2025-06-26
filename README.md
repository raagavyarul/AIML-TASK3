# AIML-TASK3
# 🏡 House Price Prediction using Linear Regression

This project implements and explains *Simple & Multiple Linear Regression* using the *House Price Prediction Dataset*.

## 📌 Objective

- Learn how to preprocess data and apply linear regression using scikit-learn.
- Evaluate the model using standard error metrics.
- Visualize regression results and interpret feature importance.

---

## 📁 Dataset

- Dataset used: *House Price Prediction*
- Contains features like area, bedrooms, bathrooms, furnishingstatus, airconditioning, etc.

---

## ⚙️ Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## ✅ Steps Performed

### 1. Import & Preprocess the Dataset
- Loaded dataset using pandas
- Checked for null values
- Handled categorical features using *one-hot encoding*
- Normalized features

### 2. Split Data into Train-Test Sets
- Used train_test_split() to split data into 80% train and 20% test sets

### 3. Fit Linear Regression Model
- Used LinearRegression() from sklearn.linear_model
- Trained model and predicted prices

### 4. Evaluate the Model
- Calculated:
  - *MAE* (Mean Absolute Error)
  - *MSE* (Mean Squared Error)
  - *R² Score* (Coefficient of Determination)

### 5. Plot Regression & Interpret Coefficients
- Plotted:
  - Scatter plot of Actual vs Predicted values
  - Regression line (for area vs price)
- Printed model coefficients to understand the influence of each feature
