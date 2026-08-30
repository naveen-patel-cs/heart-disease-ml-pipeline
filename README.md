# Heart Disease Risk Prediction — End-to-End ML Pipeline

### Author: Naveen Patel | B.Tech IT (AI/ML) | Published ML Researcher

## Overview
Built a complete machine learning pipeline to predict heart disease 
risk using real patient medical records. Compared 3 ML models and 
implemented SHAP explainability for clinical interpretability.

## Dataset
- Source: UCI Heart Disease Dataset
- 303 patients, 13 features
- Binary classification: Disease vs No Disease

## Models Built and Results

| Model | Accuracy | Disease Recall | Missed Patients |
|-------|----------|---------------|-----------------|
| Logistic Regression | 88.5% ✅ Best | 91% | 3 |
| Random Forest | 86.8% | 84% | 5 |
| Neural Network | 82.0% | 84% | 5 |

## Key Findings
- thal and ca were strongest predictors (0.52 and 0.46 correlation)
- Asymptomatic patients had highest heart disease rate — 
  demonstrating value of ML screening over symptom-based diagnosis
- Cholesterol showed surprisingly weak correlation at just 0.09
- Logistic Regression outperformed complex models on small dataset

## SHAP Explainability
Implemented SHAP values to explain individual predictions —
identifying which features drove each patient's risk score.

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Keras, TensorFlow, 
SHAP, Matplotlib, Seaborn, Power BI

## Project Structure
- heart_disease_ml_pipeline.ipynb — Main notebook
- heart_disease_model.pkl — Saved trained model
- predictions.csv — Model predictions for dashboard
- heart.csv — Dataset

## How to Run
1. Open heart_disease_ml_pipeline.ipynb in Google Colab
2. Runtime → Run all
3. All outputs and charts will generate automatically
