# Loan Repayment (Classification Problem).
###### Tools Used: Machine Learning Models, python,Jupyter Notebook

![loan repayment](https://github.com/ishagoel840/Loan-Repayment/assets/163164421/d7c4779b-eda3-4376-aaa0-eec2711aa830)

## About the Dataset
The dataset used for this project includes loan data with 80,000 records for training and 20,000 records for testing. The features include various aspects of the borrowers and their loan details, such as credit history, employment information, loan amount, interest rate, and the purpose of the loan.
You are required to build and train a model that identifies a customer will repay or default from the loan dataset.


### Data description 
|Column | Description|
|---|---|
|earliest_cr_line :|The month the borrower's earliest reported credit line was opened|
|emp_title:| The job title supplied by the Borrower when applying for the loan.|
|fico_range_high:| The upper boundary range the borrower’s FICO at loan origination belongs to.|
|fico_range_low:| The lower boundary range the borrower’s FICO at loan origination belongs to.|
|Grade:| LC assigned loan grade|
|application_type:| Indicates whether the loan is an individual application or a joint application with two co-borrowers|
|initial_list_status:| The initial listing status of the loan. Possible values are – W, F|
|num_actv_bc_tl:| Number of currently active bankcard accounts.|
|mort_acc:| Number of mortgage accounts.|
|tot_cur_bal:|  Total current balance of all accounts|
|open_acc:| The number of open credit lines in the borrower's credit file.|
|pub_rec:|  Number of derogatory public records|
|pub_rec_bankruptcies:|  Number of public record bankruptcies.|
|Purpose: | A category provided by the borrower for the loan request.|
|revol_bal:|  Total credit revolving balance|
|Title:| The loan title provided by the borrower|
|total_acc: | The total number of credit lines currently in the borrower's credit file|
|verification_status: |Indicates if income was verified by LC, not verified, or if the income source was verified|
|addr_state:| The state provided by the borrower in the loan application|
|annual_inc:| The self-reported annual income provided by the borrower during registration.|
|emp_length:| Employment length in years. Possible values are between 0 and 10 where 0 means less than one year and 10 means ten or more years.|
|home_ownership:| The home ownership status provided by the borrower during registration. Our values are: RENT, OWN, MORTGAGE, OTHER.|
|int_rate:| Interest Rate on the loan|
|loan_amnt:| The listed amount of the loan applied for by the borrower. If at some point in time, the credit department reduces the loan amount, then it will be reflected in this value.|
|sub_grade: |LC assigned loan subgrade|
|Term:| The number of payments on the loan. Values are in months and can be either 36 or 60.|
|revol_util:| Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit.|
|loan_status: | Status of the loan|
#### Target
```
loan_status:  Status of the loan
```
## Key Steps
- Data Exploration and Analysis: Conducted a thorough exploratory data analysis to understand the dataset.
- Data Preprocessing: Performed data cleaning, handled missing values, and processed features for the model.
  - Dealing with Imbalanced data
- Feature Engineering: Engineered new features to better capture the information in the dataset.
- Splitting the dataset into test and validation data.
- Model Building: Built a classification model using Logistic Regression, KNN and XgBoost.
- Hyperparameter tuning


 ## Model Performance Evaluation
 ```
Accuracy: 83%

Precision : 95.00%

Recall : 79.26%
```

## Conclusion
```
 Model Evaluation: Evaluated the model and XgBoost has the highest accuracy of 83%
```
 ## Prediction on Test Dataset
- The preprocessing for test dataset is done in the same manner as the train dataset.
- Successfully trained the model and  tuned model is fitted on the test dataset.
