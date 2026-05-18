# 🧠 Santé Mentale des Femmes — Big Data Pipeline

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Spark](https://img.shields.io/badge/Apache%20Spark-4.0-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-AUC%200.81-green)
![Dataset](https://img.shields.io/badge/Dataset-1.4M%20lignes-purple)

## Problématique
Quels facteurs socio-démographiques et comportementaux prédisent la dépression chez les femmes américaines ?

## Pipeline
| Étape | Outil |
|-------|-------|
| Ingestion | pandas chunks |
| Storage | DuckDB + Parquet |
| Processing | Apache PySpark + Spark SQL |
| ML | XGBoost + Random Forest + SHAP |
| Visualisation | Plotly + Streamlit |

## Dataset — BRFSS/CDC
- **1.4M lignes** · 30+ colonnes · données réelles CDC
- Source : https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system
