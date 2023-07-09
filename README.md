# Credit-Card-Default-Prediction-Project

Project Statement:
This project is aimed at predicting the customer's default payments in Taiwan.From the perspective of the risk management,the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or non credible clients.
This dataset consists of 30000 rows and 25 columns which contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

ID: ID of each client

LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit)

SEX: Gender (1=male, 2=female)

EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)

MARRIAGE: Marital status (1=married, 2=single, 3=others)

AGE: Age in years

PAY_0: Repayment status in September, 2005 (-2= No Consumption, -1=pay duly, 0= paid minimum & revolving credit, 1=payment delay for one month, 2=payment delay for two months, … 9=payment delay for nine months and above)

PAY_2: Repayment status in August, 2005 (scale same as above)

PAY_3: Repayment status in July, 2005 (scale same as above)

PAY_4: Repayment status in June, 2005 (scale same as above)

PAY_5: Repayment status in May, 2005 (scale same as above)

PAY_6: Repayment status in April, 2005 (scale same as above)

BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)

BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)

BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)

BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)

BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)

BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)

PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar)

PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)

PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)

PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)

PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)

PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)

default.payment.next.month: Default payment (1=yes, 0=no)


Conclusion
EDA Outcomes:

People who are not married taking credits slightly higher than the married people
Age of most using og credit is in the range of 24 and 40. After the age 60, almost there is a declinebusing credit.
77.88 % people are not the defaulters of credit card. 22.12 % (6636 out of 30000) people are the defaulters.
Female count is higher than Male in taking credit card.
Challenges:

Ouliers detected by Boxplot and Treated
Imbalance of Data treated by SMOTE Approach
Some Data not having proper explanation
Removed Irrelavent classes in columns.
Model Outcomes:

Among all the models, Random Forest Model given good results.

Random Forest Classifier & XG Boost given the best precision Score i.e. 85.9% & 84.5% respectively.

Random Forest Classifier given the best recall Score i.e. 87.9%

The Columns 'LIMIT_BAL','BILL_AMT_SEP' & 'PAY_AMT_AUG' are the most important features for our Target Feature i.e., to check whether the user Defaulter or not.

In Overall, Random Forest Classifier best to fit on this data, But Execution of CrossValidation using GridSearchCV for hyper parameters takes long time.

--------------------------------------------------------------------------------------------------------------------------------------------------------
If you have any doubts/ suggestions, kindly reach out me on mail

mail: saiharish.swarna@gmail.com

---Thankyou for Reading---

