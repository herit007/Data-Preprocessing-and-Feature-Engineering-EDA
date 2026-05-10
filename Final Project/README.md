# Holistic Data Preparer

A complete end-to-end data preprocessing and feature engineering project built for machine learning readiness.

---

## Project Objective

The objective of this project is to perform complete data preprocessing on a customer credit risk dataset by applying:

- Data cleaning
- Missing value handling
- Outlier treatment
- Encoding
- Feature engineering
- Feature scaling
- Data transformations

The final output is a clean and transformed dataset ready for machine learning modeling.

---

## Project Structure

```bash
Final Project/
│
├── Dataset/
│   ├── customer_credit_risk.csv
│   ├── customer_metadata.json
│   └── loan_history.db
│
├── holistic_data_preparer.ipynb
├── final_cleaned_dataset.csv
├── scaled_dataset.csv
├── data_quality_report.html
└── README.md
```

---

## Files Description

### Dataset Folder
Contains raw project data files:

- **customer_credit_risk.csv** → Main dataset
- **customer_metadata.json** → Additional metadata
- **loan_history.db** → SQL database file

---

### Notebook
- **holistic_data_preparer.ipynb**

Contains:
- Part A to Part H implementation
- Theory answers
- Data preprocessing workflow
- Final analysis and summary

---

### Output Files

#### final_cleaned_dataset.csv
Contains:
- Missing values handled
- Outliers treated
- Encoded variables

#### scaled_dataset.csv
Contains:
- Standardized numerical features for ML usage

#### data_quality_report.html
Generated automated profiling report.

---

## Techniques Implemented

### Missing Value Handling
- Complete Case Analysis
- Mean Imputation
- Most Frequent Imputation
- Missing Indicator
- Random Sample Imputation
- KNN Imputation
- MICE Imputation

### Outlier Handling
- Z-Score
- IQR
- Percentile Method
- Winsorization

### Encoding
- Label Encoding
- Ordinal Encoding
- One Hot Encoding
- Binarization

### Feature Engineering
- Debt-to-Income Ratio
- Average Monthly Transactions
- Spending-Income Ratio

### Scaling
- StandardScaler
- MinMaxScaler
- MaxAbsScaler
- RobustScaler
- Normalization

### Transformations
- Log Transformation
- Square Root
- Reciprocal Transformation
- Box-Cox
- Yeo-Johnson

---

## Best Methods Selected

After comparing preprocessing methods:

- **Mean Imputation** for numerical missing values
- **Most Frequent Imputation** for categorical missing values
- **Winsorization** for outlier treatment
- **One Hot Encoding** for nominal categorical variables
- **Ordinal Encoding** for ordered categories
- **StandardScaler** for feature scaling

---

## Final Outputs Generated

- `final_cleaned_dataset.csv`
- `scaled_dataset.csv`
- `data_quality_report.html`

---

## Conclusion

This project successfully transforms raw customer credit data into a clean, structured, and machine-learning-ready dataset.

It demonstrates a holistic approach to data preparation by comparing multiple preprocessing techniques and selecting the most suitable methods for the dataset.

---

## Author

**Herit Tanna**