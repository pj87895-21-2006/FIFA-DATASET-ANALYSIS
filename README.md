# ⚽ FIFA Dataset Analysis

Machine learning project analyzing FIFA player data to predict player performance/value using regression models.

## 📊 Overview
This project applies a full data preprocessing and machine learning pipeline to a Kaggle FIFA dataset (`players.csv`), comparing Linear Regression and Random Forest models to predict player ratings/value.

## 📁 Contents
- `fifa-dataset-analysis.ipynb` — Main analysis & modeling notebook
- `players.csv` — Raw dataset
- `README.md` — Project documentation

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn (sklearn)
- Matplotlib

## 🔄 Workflow

1. **Check null values** — Identify missing data across all columns
2. **Remove high-null columns** — Drop columns with more than 50% missing values
3. **Remove useless columns** — Drop irrelevant/non-predictive features (IDs, names, etc.)
4. **Encode categorical data** — Convert categorical → numerical values
5. **Handle missing values** — Impute remaining nulls (mean/median/mode)
6. **Feature scaling** — Standardize/normalize values using sklearn scalers
7. **Model selection** — Train and compare:
   - Linear Regression
   - Random Forest Regressor
8. **Evaluation** — Assess model performance (R², MAE, RMSE, etc.)
9. **Visualization** — Plot results and comparisons using Matplotlib
