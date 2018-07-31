# Notes for Home Credit Default Risk 

## Problem Description
Predict probability of how capable each applicant is of repaying a loan.  
Target is 0 or 1. So this is a supervised classification problem.  
All they want is to judge whether it is capable or not, a human is also can do this job by looking into the files datas given.

## Structure

#### Read files:  
We got nine files in total.  

1. application test and train .csv  
Train with target and test without. Each row represent one loan record.  
Training data shape:  (307511, 122) 
Testing data shape:  (48744, 121)   
Target:  
0: 282686  
1: 24825  
##### EDA:  
- Data imbalaced problem.  
- Missing data in half columns.  
- Column data type include int64 float64 object(categorical features) label encoding & one-hot  
- Anomalies  
- 




2. bureau.csv   
Client's previous credits provided by third party.  
Each loan has one row in this file before application date.

3. bureau_balance.csv   





#### Machine learning methods:  
Linear Regression
Decsion Tree
LightGBM
Xgboost

#### Deep learning methods:  







	
