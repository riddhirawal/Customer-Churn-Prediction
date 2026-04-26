# Customer Churn Prediction Pipeline

## 📌 Project Overview
Developed a machine learning solution to predict customer attrition for a telecommunications company. The project focuses on identifying high-risk customers to enable targeted retention strategies.

## 🛠️ Tech Stack
- **Languages:** Python (Pandas, NumPy)
- **Machine Learning:** Scikit-learn (Random Forest, XGBoost, Logistic Regression)
- **Sampling:** SMOTE (Synthetic Minority Over-sampling Technique)
- **Visualization:** Seaborn, Matplotlib

## 🚀 Key Features & Workflow
- **Data Engineering:** Cleaned 7,000+ records, handled missing values in total charges, and applied feature scaling.
- **Imbalance Handling:** Implemented **SMOTE** to address class imbalance, significantly improving model recall for minority churn classes.
- **Model Evaluation:** Benchmarked multiple algorithms; the **Random Forest** model emerged as the top performer with a ~15% increase in accuracy over baseline.

## 📊 Business Insights
- **Contract Type:** Month-to-month subscribers exhibit the highest churn risk.
- **Service Trends:** Fiber optic users and customers without tech support are more likely to leave, suggesting a need for service bundling.
