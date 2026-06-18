# Smart Credit Dashboard 
# Smart Credit — Lending Decision Platform

**Author:** Shawn Kimani Ngugi | SCT213-C002-0043/2022  
**Institution:** Jomo Kenyatta University of Agriculture and Technology (JKUAT)  
**Supervisor:** Mr. Daniel Njuguna  
**Project:** Improving Lending Decision-Making and Loan Default Predictions Using Logistic Regression and Gradient Boosting Techniques

---

## Overview
An interactive ML-powered credit risk dashboard built with Streamlit. The platform compares Logistic Regression and XGBoost models across two credit datasets, with SHAP explainability, fairness auditing, and prescriptive scenario analysis.

## Features
- **Borrower Assessment** — Real-time default probability with risk gauge and SHAP-based drivers
- **Model Performance** — Cross-dataset comparison of Logistic Regression vs XGBoost
- **Fairness & Compliance** — Demographic parity, equal opportunity, and disparate impact audit
- **Scenario Explorer** — Risk landscape maps across borrower feature combinations
- **Batch Scoring** — Upload CSV, score all applications, download results

## Methodology
- Framework: CRISP-DM
- Models: Logistic Regression, XGBoost
- Datasets: UCI German Credit (DS1), Algozee Behavioral Credit Risk (DS2), Loan default dataset (DS#3)
- Techniques: SMOTE oversampling, RandomizedSearchCV, SHAP, cost-sensitive threshold optimisation (5:1 FN penalty)

## Running Locally
```
pip install -r requirements.txt
streamlit run dashboard.py
```

## Deployed App
[mart-credit-interactive-user-dashboard ∙ main ∙ SMART CREDIT dash.py](https://smart-credit-interactive-user-dashboard-cueulamkjfumrdmccvctwq.streamlit.app/)
