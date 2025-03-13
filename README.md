# 🧬 Huntington Disease Prediction

This project applies **machine learning** to predict **Huntington’s Disease progression stages** using clinical, genetic, and functional biomarkers.

## 📂 Dataset
- Sourced from **[Kaggle](https://www.kaggle.com/datasets/rajmohnani12/huntington-disease-dataset/data)**
- Features include **genetic markers, motor symptoms, cognitive decline, and brain volume loss**.
- Target variable: **Disease_Stage** (Pre-Symptomatic, Early, Middle, Late).

## 🛠️ Preprocessing
✔ Dropped non-informative columns
✔ Handled missing values (most frequence for categorical)
✔ One-hot encoded categorical features & standardized numerical features

## 🤖 Model
- **RandomForestClassifier** trained to predict disease stage.
- **Hyperparameter tuning** with `RandomizedSearchCV`.
- Evaluated using **cross-validation accuracy & feature importance**.
