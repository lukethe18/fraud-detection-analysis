# Credit Card Fraud Detection Analysis

This project demonstrates an end-to-end fraud analytics workflow, including exploratory data analysis, feature engineering, machine learning modeling, and fraud pattern identification. Built as part of my data science portfolio.

## Project Overview
This analysis explores a synthetic credit card transaction dataset to identify patterns of fraudulent behavior. I applied a full machine learning pipeline using:

- Exploratory Data Analysis (EDA)
- Feature engineering (amount deviations, distance calculations, time-based flags)
- Handling class imbalance using **SMOTE**
- Logistic Regression baseline model
- Random Forest
- XGBoost
- Model evaluation using ROC, AUC, confusion matrix, feature importance

## Tools and Technologies
- Python (pandas, numpy, sklearn, xgboost)
- Matplotlib & Seaborn
- SMOTE (imblearn)
- Jupyter/Colab Notebook

## Key Results
- Fraud detection improved significantly with engineered features.
- Random Forest outperformed all models:
  - AUC: .8363
  - Accuracy: 98%
  - Precision/Recall (Fraud class): .99 / .98

## Notable Feature Engineering
- Amount deviation & Z-scores  
- Distance between cardholder and merchant  
- Time-based risk indicators (hour, waking hours)  
- Categorical encoding  

## Repository Structure
```
fraud-detection-analysis/
│── Synthetic_Fraud_Dataset.ipynb
│── Synthetic_Fraud_Dataset.py
│── requirements.txt
└── README.md
```

## How to Run
1. Clone the repository  
   ```
   git clone [https://github.com/lukethe18/fraud-detection-analysis.git]
   ```
2. Install dependencies  
   ```
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook.

## Future Enhancements
- Deploy model as an API
- Add explainability using SHAP
- Build dashboard using Power BI or Streamlit

**Luke Theivagt**  
Data Scientist
GitHub: github.com/lukethe18  
LinkedIn: linkedin.com/in/luke-theivagt
