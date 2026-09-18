# Hospital Readmission Prediction

End-to-end machine learning project predicting **30-day hospital readmission risk**, so healthcare providers can flag high-risk patients for preventive intervention. Built for DS 630 (Machine Learning).

## Pipeline

1. **Exploratory Data Analysis** — dataset overview, missing-value analysis, target distribution and class-imbalance check, numerical and categorical feature distributions
2. **Preprocessing** — missing-value handling, categorical encoding, feature scaling, train/test split (via `ColumnTransformer` + `Pipeline`)
3. **Modeling** — Logistic Regression vs. Random Forest, trained and compared head-to-head
4. **Fairness metrics** — model performance checked across patient subgroups
5. **Deployment** — model serialized and served behind a Flask API, tested end-to-end

## Tech stack

Python · scikit-learn · pandas · Parquet · Flask · Jupyter

## Run it

1. Open `hospital-readmission-prediction.ipynb` in Jupyter or Colab
2. Upload `readmission.parquet` when prompted (Section 2)
3. Run all cells top to bottom
