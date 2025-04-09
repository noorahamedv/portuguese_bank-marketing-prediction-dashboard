# 📊 Bank Marketing Campaign Prediction Dashboard

This Project predicts customer subscription to term deposits using a Portuguese bank's marketing data.  
It includes Python machine learning, SHAP explainability, and a Power BI dashboard.

This project combines **machine learning** and **business intelligence** to predict whether customers will subscribe to a term deposit based on direct marketing campaign data from a Portuguese bank. 

It leverages **Python modeling** and a **Power BI dashboard** to deliver clear, actionable business insights.

---

## 🚀 Project Objectives

- Predict term deposit subscription likelihood using historical campaign data.
- Handle data imbalance using SMOTE to improve model performance.
- Train and evaluate Logistic Regression, Random Forest, and XGBoost models.
- Explain model behavior using SHAP values.
- Visualize results with an interactive Power BI dashboard.

---

## 🧱 Dataset Overview

**Source**: UCI Machine Learning Repository  
- Size: ~41,000 records  
- Target Variable: `y` (1 = subscribed, 0 = not subscribed)  

### `Key Features:`
- `Demographics`: age, job, education, marital status  
- `Campaign interaction`: contact month, number of contacts, call duration  
- `Economic context`: employment rate, consumer index  

### **Dimension Tables**  
- `dim_time`: Time attributes (date, month, year)  
- `dim_stock`: Stock tickers and company mapping  
- `dim_company`: Company names and ticker info  
- `dim_index`: Market index info and volumes  

---

## 🧠 Tech Used

- `Language`: Python (Google Colab)  
- `ML Libraries`: pandas, scikit-learn, XGBoost, SHAP, imblearn  
- `BI Tool`: Microsoft Power BI  
- `Other Tools`: Matplotlib, Seaborn, SMOTE, Joblib  

---

## 📥 Report

### 🧠 Modeling Approach

- **Preprocessing**: Removed `unknown`, one-hot encoded categoricals  
- **Feature Engineering**: Added `subscription_probability`, `score_bin`  
- **Model Training**:
  - Logistic Regression  
  - Random Forest  
  - XGBoost ✅ Best performance  
- **Explainability**: SHAP beeswarm plot  

🔗 [Final Project Report (PDF)](report/Report.pdf)

---

## 📸 Report Summary Preview

<p align="center">
  <img src="report.png" alt="Final Report Preview" width="800"/>
</p>
