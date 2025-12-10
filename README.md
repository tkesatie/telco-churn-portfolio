# Telco Customer Churn Prediction

## 📌 Project Overview
The telecommunications industry faces high customer attrition (churn). This project analyzes customer behavior to identify key drivers of churn and builds a predictive model to flag high-risk customers for proactive retention campaigns.

**Business Value:** By identifying at-risk customers with **52% Recall** (Sensitivity), this model allows the marketing team to target retention incentives, potentially saving the company estimated revenue.

## 🔍 Key Insights
* **Fiber Optic Users are High Risk:** Customers with Fiber Optic internet are significantly more likely to cancel than DSL users.
* **Payment Method Matters:** Electronic Check users have the highest churn rate.
* **Contract Lock-in:** Month-to-month contracts are the #1 predictor of churn. 

## 🛠️ Tools & Technologies
* **Python**: Pandas, NumPy
* **Visualization**: Matplotlib, Seaborn
* **Machine Learning**: Scikit-Learn (Logistic Regression)

## 📊 Model Performance
* **Model:** Logistic Regression
* **Accuracy:** ~79%
* **Recall (Churners):** 52% (Optimized for identifying positive cases)