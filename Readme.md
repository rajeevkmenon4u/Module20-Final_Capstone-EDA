# Capstone Project : Clasification Problem
**Overview**: The objective of the project is to develop a classification model that predicts which bank customers are likely to close their accounts. Additionally, the study aims to identify and analyze the key factors contributing to customer attrition.  
### Problem 1: Understanding the Data
To gain a better understanding of the data, Analysing the data and performing EDA.
### Data Details
Input variables:

| Column            | Non-Null Count | Dtype   |
|-------------------|----------------|---------|
| id                | 165034         | int64   |
| CustomerId        | 165034         | int64   |
| Surname           | 165034         | object  |
| CreditScore       | 165034         | int64   |
| Geography         | 165034         | object  |
| Gender            | 165034         | object  |
| Age               | 165034         | float64 |
| Tenure            | 165034         | int64   |
| Balance           | 165034         | float64 |
| NumOfProducts     | 165034         | int64   |
| HasCrCard         | 165034         | float64 |
| IsActiveMember    | 165034         | float64 |
| EstimatedSalary   | 165034         | float64 |


Output variable (desired target):

| Column            | Non-Null Count | Dtype   |
|-------------------|----------------|---------|
| Exited            | 165034         | int64   |
