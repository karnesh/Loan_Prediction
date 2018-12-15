# Loan_Prediction

This is a binary classification problem for determining loan approval. 

## Dataset
It comprises of train and test dataset. Train data has 13 columns (Loan_ID, Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area, Loan_Status). We have to predict whether loan gets approved or rejected that is 'Loan_Status' column.

## Models
I tried four different models (mentioned below) and compared their performace. 
1. Logistic Regression
2. Decision Trees
3. Random Forest
4. XGBoost

| Model                | Accuracy      |
| -------------------- | ------------- |
| Logistic Regression  | 80.28552      |
| Decision Tree        | 71.15808      |
| Random Forest        | 80.4521%      |
| XGBoost              | 77.99838%     |

Random Forest works best closly followed by Logistic Regression while Decision Tree has the worst performance. 

## Things to try next
 - Grid Search for XGBoost
 - Feature engineering
 - Independent vs independent variable visualizations to discover some more patterns
 - Try ensemble modeling 
