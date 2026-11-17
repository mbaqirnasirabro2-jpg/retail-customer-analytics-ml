# Retail Customer Segmentation & Predictive Analytics

## 📌 Project Overview
This repository contains an end-to-end Data Science pipeline designed to clean, analyze, and model retail customer behavior. The objective is to identify high-value customer segments, handle real-world data anomalies (missing values/outliers), and build a predictive model for customer spending scores.

## 🛠️ Tech Stack & Tools
- **Language:** Python 3.x
- **Data Manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn, LightGBM, SHAP

## ⚙️ Key Workflow & Methodology
1. **Data Cleaning & Imputation:** 
   - Handled missing entries in `Age`, `AnnualIncome`, and `ProductCategory` using median/mode imputation strategies to prevent data leakage.
2. **Exploratory Data Analysis (EDA):** 
   - Analyzed spending patterns across demographics and product categories.
   - Identified high-revenue customer clusters using correlation matrices and distribution plots.
3. **Feature Engineering & Preprocessing:** 
   - Built a modular `ColumnTransformer` pipeline utilizing `OneHotEncoder` for categorical variables and `StandardScaler` for numerical features.
4. **Predictive Modeling & Explainability:** 
   - Trained a `LightGBM` regressor/classifier to predict customer spending behavior.
   - Used `SHAP` values to interpret feature importance and model transparency.

## 🚀 How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/mbaqirnasirabro2-jpg/retail-customer-analytics-ml.git](https://github.com/mbaqirnasirabro2-jpg/retail-customer-analytics-ml.git)
