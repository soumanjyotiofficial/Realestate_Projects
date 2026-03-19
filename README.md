# 🏠 Taiwan Real Estate Price Analysis

## 📌 Project Overview
This project analyzes key factors affecting real estate prices in Taiwan using exploratory data analysis (EDA) and regression modeling. The objective is to identify which variables significantly influence house prices per unit area.

---

## 🎯 Problem Statement
Identify the impact of the following factors on housing prices:
- House Age  
- Number of Convenience Stores Nearby  
- Distance to the Nearest MRT Station  

---

## 📂 Dataset
Features used:
- X2 house age  
- X3 distance to the nearest MRT station  
- X4 number of convenience stores  
- Y house price of unit area  

---

## 🧹 Data Preprocessing
- Removed missing values  
- Filtered outliers using 10th and 90th percentiles  
- Converted columns to numeric format  

---

## 📊 Exploratory Data Analysis (EDA)

### House Age vs Price
- No strong linear relationship observed  

### Convenience Stores vs Price
- Moderate positive correlation (~0.51)  
- More stores → higher price  

### Distance to MRT vs Price
- Strong negative correlation (~ -0.65)  
- Greater distance → lower price  

---

## 🤖 Model Building

### Model 1: Convenience Stores
- Algorithm: Linear Regression  
- R² Score: 0.28  
- Weak predictive power  

### Model 2: Distance to MRT
- Algorithm: Linear Regression  
- R² Score: 0.52  
- Strong predictor  

---

## 📈 Evaluation Metrics

| Metric | Stores | Distance |
|--------|--------|----------|
| MAE    | 6.33   | 4.81     |
| MSE    | 58.22  | 38.75    |
| RMSE   | 7.63   | 6.22     |
| R²     | 0.28   | 0.52     |

- Lower MAE, MSE, RMSE = Better  
- Higher R² = Better  

---

## 🧠 Key Insights
- Distance to MRT is the most important factor  
- Convenience stores have moderate impact  
- House age has weak or no linear relationship  

---

## ⚠️ Limitations
- Only single-variable models used  
- No multivariate regression  
- Possible non-linear relationships ignored  
- Sequential train-test split  

---

## 🚀 Future Improvements
- Multiple Linear Regression  
- Feature engineering (log, polynomial)  
- Random Forest / XGBoost  
- Proper train-test split  
- Residual analysis  

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

