# Customer Churn Prediction & Analytics

## Project Overview
Built a machine learning project to analyze customer churn patterns and predict customers at risk of leaving a telecom service.

## Objectives
- Analyze customer churn behavior and identify key patterns.
- Compare multiple machine learning classification models.
- Identify important factors influencing customer churn using SHAP.

## Technologies
- Python
- Pandas
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib
- Seaborn

## Machine Learning Models
- Logistic Regression
- Random Forest
- XGBoost

## Model Performance

| Model | Accuracy | ROC-AUC | Churn F1-Score |
|---|---:|---:|---:|
| Logistic Regression | 80.38% | 83.57% | 60.91% |
| Random Forest | 79.03% | 81.95% | 56.04% |
| XGBoost | 78.75% | 83.62% | 56.35% |

## Key Insights
- Month-to-month customers showed substantially higher churn than customers on one-year or two-year contracts.
- Customers with longer tenure showed lower churn.
- Fiber optic internet service was one of the most influential features in the XGBoost model.
- Contract type was an important factor associated with customer churn.

## Explainability
SHAP was used to interpret model predictions and identify the features with the greatest influence on churn risk.

## Dataset
IBM Telco Customer Churn dataset.

## Project Workflow
Data Cleaning → Exploratory Data Analysis → Feature Engineering → Train/Test Split → Model Training → Model Evaluation → Feature Importance → SHAP Analysis
