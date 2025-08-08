# 🏠 NTI Final Project – House Price Prediction

This repository contains my final project from my **NTI Internship** where I applied the skills I learned during **90 hours of Machine Learning training**.  
The goal of the project is to predict **house prices** based on multiple features such as living area, land value, number of rooms, heating type, and more.

---

## 📌 Project Overview
- **Type**: Regression Problem
- **Dataset**: Real estate dataset containing numerical and categorical features.
- **Goal**: Build and evaluate different regression models to achieve the best possible accuracy.
- **Tools Used**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## ⚙️ Steps & Workflow
1. **Data Loading & Exploration**
   - Checked dataset structure and statistics.
   - Removed irrelevant or redundant features.
   - Handled missing and invalid values.

2. **Data Preprocessing**
   - One-Hot Encoding for categorical features (`heating`).
   - Scaling numerical features using **MinMaxScaler** with custom ranges.
   - Removed outliers and negative values in specific columns.

3. **Feature Engineering**
   - Added new derived features to improve model performance.
   - Adjusted scaling ranges to reflect feature importance.

4. **Modeling**
   - Applied and compared multiple regression models:
     - Linear Regression
     - K-Nearest Neighbors (KNN)
     - Random Forest Regressor
     - Gradient Boosting Regressor
     - Extra Tree Regressor
     - XGBRegressor
   - Evaluated using **MAE**, **MSE**, **RMSE**, and **R² Score**.

5. **Results**
   - Initial models achieved around **66% R² score**.
   - After adding new feature(price pre sqft) and tuning, best models reached **90%+ accuracy**.

---

## 📊 Final Results
| Model                  | R² Score |
|------------------------|----------|
| Linear Regression      | ~0.93    |
| Random Forest          | ~0.97    |
| Gradient Boosting      | ~0.98    |
| XGBRegressor           | ~0.98    |
| KNN                    | ~0.73    |
| Extra tree             | ~0.89    |


---

## 🛠️ Technologies Used
- **Python 3**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---
