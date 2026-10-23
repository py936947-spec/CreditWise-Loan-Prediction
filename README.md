# CreditWise-Loan-Prediction
Machine learning project for loan prediction


## Project Overview
CreditWise Loan Prediction is a Machine Learning project designed to predict whether a loan application should be approved or rejected based on applicant information.

The project addresses challenges in manual loan verification, such as time-consuming processing and inconsistent decisions. It uses historical loan application data to identify patterns and support loan approval decisions.

## Problem Statement
Financial institutions need an efficient way to evaluate loan applications. This project explores how machine learning can help analyze applicants' financial details, credit scores, income, and other characteristics to predict loan approval.

**Target variable:** `Loan_Approved`
- `1` — Loan Approved
- `0` — Loan Rejected

## Dataset Description
The dataset contains information about loan applicants, including:

- Applicant and co-applicant income
- Employment status and age
- Marital status and dependents
- Credit score and existing loans
- Debt-to-Income (DTI) ratio
- Savings and collateral value
- Loan amount, term, and purpose
- Property area and education level
- Gender and employer category

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Load and inspect the dataset.
2. Handle missing values.
3. Perform Exploratory Data Analysis (EDA).
4. Visualize loan approval patterns and relationships between features.
5. Encode categorical variables.
6. Analyze feature correlations.
7. Split the data into training and testing sets.
8. Apply feature scaling.
9. Train and evaluate machine learning models.
10. Perform feature engineering to explore model improvements.

## Machine Learning Models
The notebook explores the following classification algorithms:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

## Model Evaluation
The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### Initial Evaluation Results

| Model | Accuracy | Precision | Recall | F1-score |
|---|---:|---:|---:|---:|
| Logistic Regression | 86.50% | 78.33% | 77.05% | 77.69% |
| KNN | 76.00% | 62.75% | 52.46% | 57.14% |
| Gaussian Naive Bayes | 86.50% | 80.36% | 73.77% | 76.92% |

*These results are from the initial model evaluation recorded in the notebook. Results may differ after feature engineering or other changes.*

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries.
3. Ensure the dataset filename and file-reading method match the notebook.
4. Open `Creditwise_Loan.ipynb` in Jupyter Notebook or JupyterLab.
5. Run the cells in sequence to perform data analysis, train models, and evaluate their performance.

Install the main dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Project Structure

```text
CreditWise-Loan-Prediction/
├── Creditwise_Loan.ipynb
├── loan_approval_data.csv
├── README.md
└── requirements.txt
```


## Learning Outcomes
- Data preprocessing and missing-value handling
- Exploratory Data Analysis and visualization
- Categorical encoding and feature scaling
- Classification model training
- Model evaluation and feature engineering

## Disclaimer
This project is for educational purposes. Predictions are intended to support analysis and should not be treated as final financial decisions. Real-world loan approval systems require appropriate validation, fairness assessment, privacy safeguards, and human oversight.
