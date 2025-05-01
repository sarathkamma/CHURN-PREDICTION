# CHURN-PREDICTION


This project uses machine learning to predict customer churn based on behavioral, demographic, and service interaction data. Built using **Random Forest**, it includes data preprocessing, leakage control, model evaluation with cross-validation, and interpretability via **SHAP**.

---

## 📁 Project Structure
📊 Features Used
The model uses features such as:

Tenure

Usage Frequency

Contract Length

Subscription Type

Total Spend

Last Interaction

(Categorical features are one-hot encoded)

Highly correlated/leaky features like Payment Delay or Support Calls are excluded.

✅ Model Evaluation
Cross-Validation: 5-fold accuracy reported

Metrics: Accuracy, Precision, Recall, F1-score

Explainability: SHAP plots for feature importance
