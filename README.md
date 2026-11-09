# Home Loan Default Risk Analysis and Prediction

## Project Overview

This project focuses on analyzing customer financial information and predicting the likelihood of home loan default using Machine Learning techniques.

The main objective is to identify potential loan defaulters, understand important factors influencing loan default, and classify customers into different risk categories to support better lending decisions.

## Problem Statement

1. Perform comprehensive Exploratory Data Analysis (EDA) on the given banking dataset.
2. Develop Machine Learning models to predict customer loan default.
3. Identify important factors associated with loan default.
4. Segment customers based on their predicted default risk.
5. Compare multiple Machine Learning models and recommend the best-performing model.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Machine Learning

## Dataset Description

The project uses seven datasets:

1. application_train.csv
2. bureau.csv
3. bureau_balance.csv
4. previous_application.csv
5. installments_payments.csv
6. POS_CASH_balance.csv
7. credit_card_balance.csv

These datasets contain customer application details, previous credit history, loan information, installment payments, and credit card transaction history.

## Project Workflow

1. Data Collection and Loading
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Integration and Aggregation
6. Machine Learning Model Development
7. Model Evaluation and Comparison
8. Feature Importance Analysis
9. Customer Risk Segmentation
10. Loan Eligibility Recommendations

## Machine Learning Algorithms

The following classification algorithms were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC
- PR AUC

### Best Model

Logistic Regression was selected as the preferred model based on its highest PR AUC score.

| Evaluation Metric | Score |
|---|---:|
| Accuracy | 70.33% |
| Precision | 17.06% |
| Recall | 69.29% |
| F1 Score | 27.38% |
| ROC AUC | 76.66% |
| PR AUC | 25.01% |

## Customer Risk Segmentation

Customers are classified into three categories based on predicted default probability:

- **Low Risk:** 0–20%
- **Medium Risk:** 20–50%
- **High Risk:** 50–100%

This segmentation helps support risk-based lending decisions and customer assessment.

## Key Outcomes

- Analyzed and integrated multiple banking datasets.
- Performed exploratory data analysis to identify customer financial patterns.
- Developed and compared three Machine Learning classification models.
- Identified important features associated with loan default.
- Classified customers into different default risk categories.
- Recommended Logistic Regression for further production evaluation.

## Future Enhancements

- Improve model performance through hyperparameter tuning.
- Optimize classification thresholds.
- Apply probability calibration.
- Develop an interactive loan default prediction application.
- Perform additional validation before real-world deployment.

## Project Structure

```text
Home-Loan-Default-Risk-Analysis/
│
├── HomeLoan_Default_RiskAnalysis_Prediction.ipynb
├── README.md
└── requirements.txt
```

## Conclusion

This project demonstrates the application of Machine Learning in the banking and financial services domain to predict home loan defaults, analyze customer credit behavior, identify important risk factors, and support informed lending decisions.
