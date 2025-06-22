
# Logistic Regression-Based Credit Risk Prediction for LoanTap

## 🎯 Objective
To build a reliable logistic regression model that accurately predicts loan default risk, enabling LoanTap to make faster, smarter underwriting decisions and offer customized loan products with reduced credit risk.

## 📝 Project Report
-You can access the complete project python file here - Python
-You can access the complete project in pdf format here - Report

## 📚 About Data

| Feature | Description |
|:--------|:------------|
| loan_amnt | The listed amount of the loan applied for by the borrower.|
| term | The number of payments on the loan.|
| int_rate | Interest Rate on the loan |
| installment |The monthly payment owed by the borrower if the loan originates.|
| grade | LoanTap assigned loan grade |
| sub_grade | LoanTap assigned loan subgrade |
| emp_title | The job title supplied by the Borrower when applying for the loan.|
| emp_length | Employment length in years.|
| home_ownership | The home ownership status provided by the borrower during registration |
| annual_inc | The self-reported annual income provided by the borrower during registration. |
| verification_status | Indicates if income was verified by LoanTap|
| issue_d | The month which the loan was funded |
| loan_status | Current status of the loan - Target Variable |
| purpose | A category provided by the borrower for the loan request. |
| title | The loan title provided by the borrower|
| dti | A ratio calculated using the borrower’s total monthly debt payments on the total debt
obligations, excluding mortgage and the requested LoanTap loan, divided by the borrower’s
self-reported monthly income. |
| earliest_cr_line | The month the borrower’s earliest reported credit line was opened |
| open_acc | The number of open credit lines in the borrower’s credit file.|
| pub_rec | Number of derogatory public records|
| revol_bal | Total credit revolving balance |
| revol_util | Revolving line utilization rate, or the amount of credit the borrower is using
relative to all available revolving credit. |
| total_acc | The total number of credit lines currently in the borrower’s credit file|
| initial_list_status | The initial listing status of the loan. Possible values are – W, F |
| application_type | Indicates whether the loan is an individual application or a joint application with two co-borrowers |
| mort_acc | Number of mortgage accounts. |
| pub_rec_bankruptcies | Number of public record bankruptcies |
| Address | Address of the individual |

## Outcome Insights and Reccomendations

-Achieved model accuracy of 80%, identifying opportunities for further improvement.

-Identified sub_grade and interest rate as the most influential features in predicting loan status based on coefficients.

-Facilitated the avoidance of NPAs, contributing to the firm's healthy functioning


