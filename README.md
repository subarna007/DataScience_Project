# Data Science Projects: Loan Prediction and NEPSE Analysis

## 1. Loan approval prediction (`Project_LoanPrediciton.ipynb`, data: `Dataset.csv`)

Predicts whether a home loan is approved from applicant income, credit history, property area and
other fields. Missing values are filled, categories are encoded and several classifiers are compared.
Logistic regression, SVM and k-NN are compared; logistic regression and SVM both reach 77.3% test accuracy and k-NN 71.4%. A cleaned-up version is in
[loan-prediction-model](https://github.com/subarna007/loan-prediction-model).

## 2. NEPSE index analysis (`nepsedata.ipynb`, data: `nepse.csv`)

Exploratory analysis of daily Nepal Stock Exchange (NEPSE) index data:

- closing price over time and its 100-day moving average
- daily trading volume and percentage change
- high vs low prices, monthly box plots and the closing-price distribution

## Run it

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook
```
