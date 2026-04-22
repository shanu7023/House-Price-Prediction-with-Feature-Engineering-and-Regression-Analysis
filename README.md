# House-Price-Prediction-with-Feature-Engineering-and-Regression-Analysis
This project predicts house prices using Linear Regression. The pipeline includes data cleaning, handling missing values, and one-hot encoding categorical variables like zoning and building type. Model performance is evaluated using R2 and MAE metrics, with feature scaling applied via StandardScaler to analyze its impact on prediction accuracy.

# 🏠 House Price Prediction using Linear Regression

## 📌 Problem Statement

The goal of this project is to predict house prices based on various features such as zoning, building type, and exterior characteristics.

---

## 📊 Dataset

* Dataset: HousePricePrediction.csv
* Target Variable:

  * SalePrice
* Features:

  * MSZoning
  * LotConfig
  * BldgType
  * Exterior1st
  * and other numerical features

---

## ⚙️ Approach

### 1. Data Cleaning

* Dropped unnecessary column: Id
* Handled missing values:

  * Filled SalePrice null values with mean
  * Dropped rows with remaining null values

### 2. Feature Engineering

* Converted categorical variables using One-Hot Encoding:

  * MSZoning
  * LotConfig
  * BldgType
  * Exterior1st

### 3. Train-Test Split

* 80% training and 20% testing data

### 4. Model Training

* Applied Linear Regression model

### 5. Model Evaluation

Used multiple evaluation metrics:

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Percentage Error (MAPE)

### 6. Feature Scaling

* Applied StandardScaler
* Compared model performance before and after scaling


### Before Scaling:

* R² Score:
* MAE:
* RMSE:
* MAPE:

### After Scaling:

* R² Score:
* MAE:
* RMSE:
* MAPE:

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## 📌 Key Learnings

* Handling missing data effectively
* One-hot encoding for categorical features
* Comparing model performance using multiple metrics
* Understanding impact of feature scaling on regression models

---

## 🚀 Future Improvements

* Try advanced models (Random Forest, XGBoost)
* Perform feature selection
* Hyperparameter tuning
* Deploy model using Streamlit

---

## 📁 Project Structure

* HousePricePrediction.csv
* house_price_predictor.ipynb
* README.md

---

## 👨‍💻 Author

Shanu
