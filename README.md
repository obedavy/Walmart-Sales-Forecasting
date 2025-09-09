# 🛒 Walmart Sales Forecasting

## 📌 Project Overview
This project analyzes and predicts **weekly sales across Walmart stores** using machine learning. By applying regression models and advanced boosting algorithms, the project provides actionable insights into sales drivers and helps optimize forecasting strategies.

---

## 🎯 Problem Statement
Retail sales are influenced by multiple factors such as holidays, fuel prices, economic conditions, and seasonality. Accurate forecasting is crucial for:  
- Inventory management  
- Staff planning  
- Promotional campaigns  

**Objective:** Build and evaluate machine learning models to forecast **Weekly Sales** and identify the most influential factors.

---

## 📊 Dataset
- **Source**: [Walmart Sales Dataset (Kaggle)](https://www.kaggle.com/datasets/yasserh/walmart-dataset)  
- **Features**:  
  - `Store` → Store ID  
  - `Date` → Week of sales  
  - `Weekly_Sales` → Target variable (sales amount)  
  - `Holiday_Flag` → Holiday indicator  
  - `Temperature`, `Fuel_Price`, `CPI`, `Unemployment`  

---

## 🛠️ Workflow
1. **Data Understanding**
   - Data loading and inspection  
   - Summary statistics  

2. **Data Preparation**
   - Handling duplicates & missing values  
   - Outlier detection (IQR method)  
   - Data cleaning  

3. **Exploratory Data Analysis (EDA)**
   - Sales distribution  
   - Trends across stores and holidays  
   - Correlation analysis  

4. **Feature Engineering**
   - Created new time-based features  
   - Normalization / scaling  

5. **Modeling**
   - Ridge Regression  
   - Decision Tree Regressor  
   - Random Forest Regressor  
   - XGBoost  
   - LightGBM  

6. **Evaluation**
   - Metrics: RMSE, MAE, R²  
   - Cross-validation for robustness  
   - Model comparison  

---

## 📦 Tech Stack
- **Python**: NumPy, Pandas, Scikit-learn, XGBoost, LightGBM  
- **Visualization**: Matplotlib, Seaborn, Plotly  
- **Environment**: Jupyter Notebook  

---

## 📈 Results & Insights
- Boosting models (XGBoost, LGBM) achieved the **lowest error metrics** compared to simpler models.  
- Sales show **significant spikes during holidays**.  
- Macroeconomic indicators like **CPI and Unemployment** influence sales moderately.  
- Random Forest and Gradient Boosting provided **better generalization**.  

---

## ▶️ How to Run

1. **Clone this repository**  
   ```bash
   git clone https://github.com/your-username/walmart-sales-forecasting.git
   cd walmart-sales-forecasting
