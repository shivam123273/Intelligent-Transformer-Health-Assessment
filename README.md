# Intelligent-Transformer-Health-Assessment
An end-to-end predictive maintenance framework for power transformers using Machine Learning, SHAP Explainability, and Binary Integer Programming for Health Index prediction, root cause analysis, maintenance recommendations, and maintenance optimization.
## Project Overview

Power transformers are critical assets in electrical power systems. Traditional maintenance strategies are often time-based or reactive, leading to unnecessary maintenance or unexpected failures.

This project develops an intelligent decision-support framework that:

- Predicts the **Transformer Health Index**
- Assigns a **Health Category**
- Identifies the **Root Cause** using SHAP Explainability
- Generates **Maintenance Recommendations**
- Optimizes maintenance planning using **Binary Integer Programming (BIP)**

The framework integrates Data Analytics, Machine Learning, Explainable AI, and Operations Research into a single predictive maintenance workflow.

## Key Features

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Domain-Specific Feature Engineering
- Random Forest Regression for Health Index Prediction
- SHAP Explainability for Model Interpretation
- Root Cause Analysis
- Automated Maintenance Recommendations
- Binary Integer Programming (BIP) for Maintenance Optimization
- Automated Diagnosis Report Generation

## Technology Stack

| Category | Tools & Libraries |
|----------|------------------|
| Programming | Python |
| Database | PostgreSQL |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Explainable AI | SHAP |
| Optimization | PuLP |
| Visualization | Matplotlib |
| Model Serialization | Joblib |

# Project Workflow
<p align="center">
  <img src="images/project_workflow.png" width="900">
</p>

# Project Structure

Intelligent-Transformer-Health-Assessment/
│
├── README.md
├── requirements.txt
│
├── Data/
│   ├── Health index.csv
│   ├── Health_index_final.csv
│   └── transformer_features_final.csv
│
├── Models/
│   ├── RandomForest_HealthIndex.pkl
│   ├── scaler.pkl
│   └── model_features.pkl
│
├── Notebooks/
│   ├── 01_Data_Cleaning.ipynb
│   ├── 02_EDA.ipynb
│   ├── 03_Feature_Engineering.ipynb
│   ├── 04_Machine_Learning.ipynb
│   ├── 05_Model_Inference.ipynb
│   └── 06_Maintenance_Optimization.ipynb
│
├── Output/
│   └── Transformer_Diagnosis_History.csv
│
└── Images/

# Machine Learning Pipeline

The machine learning workflow consists of the following stages:

- Data Preparation
- Feature Selection
- Train-Test Split
- Feature Scaling
- Cross Validation
- Hyperparameter Tuning
- Model Evaluation
- Model Selection
- Final Model Testing
- Model Saving

The final selected model is **Random Forest Regression**, which demonstrated the best predictive performance for transformer Health Index prediction.

### Model Performance

> **Insert Screenshot**
>
> Save your **Actual vs Predicted Plot** or **Model Comparison Table** as:
>
> images/model comparison table.png

<p align="center">
  <img src="images/model comparison table.png" width="700">
</p>
