# Online_Payments_Fraud_Detection

## In This Project

We will train a machine learning model for classifying fraudulent and non-fraudulent payments.

Dataset used can be found here - https://www.kaggle.com/datasets/ealaxi/paysim1
Various Columns of dataset, used in project are: 
 - step: represents a unit of time where 1 step equals 1 hour
 - type: type of online transaction
 - amount: the amount of the transaction
 - nameOrig: customer starting the transaction
 - oldbalanceOrg: balance before the transaction
 - newbalanceOrig: balance after the transaction
 - nameDest: recipient of the transaction
 - oldbalanceDest: initial balance of recipient before the transaction
 - newbalanceDest: the new balance of recipient after the transaction
 - isFraud: fraud transaction

## Implementation Steps

- Extract the data.
- Check, if data has null values. UIf yes, clean the data.
- Check correlation between the features of the data with the isFraud column.
- Transform the categorical features into numerical.
  - Transform the values of the isFraud column into No Fraud and Fraud labels.
- Train a classification model to classify fraud and non-fraud transactions.
- Test it, classify whether a transaction is a fraud or not by feeding about a transaction into the model.
   


