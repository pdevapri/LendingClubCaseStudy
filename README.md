# Lending club Case Study
> This case study is about analysing the data set and identifying the driving factors for risky loan applicants(i.e the defaulters who have not paid the loan for a long time) . So that the such loan to risky applicants can be reduced thereby cutting down the amount of credit loss



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
A Consumer finance company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
•	If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
•	If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The dataset contains contains the information about past loan applicants and whether they ‘defaulted’ or not. 

The aim of the case study is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.



## Conclusions
Below are the major driving factors for loan default as per my analysis:

- Lower Annual income (default percentage is maximum for annual income <20000)
- Purpose of loan is “Small Business”
- High Interest Rate (>24%)
- Term of loan is 60 months
- Home ownership is ‘Rent’ or ‘Mortgage’
- Revolving utilization rate above 90%
- Employment term <=1 
- Public record bankruptcies >=2
- Applicants paying late fee 
- Grade G and F applicants (subgrades of F and G)


## Technologies Used
- Data Understanding using the Data Dictionary
- Data Ceaning 
- Univariate Analysis
- Segmented Univariate Analysis
- Bivariate Analysis

Versions:
- jupyter @ file:///C:/ci/jupyter_1607685287094/work
- ipykernel @ file:///C:/ci/ipykernel_1633545585502/work/dist/ipykernel-6.4.1-py3-none-any.whl
- pandas @ file:///C:/ci/pandas_1635506685681/work
- numpy @ file:///C:/ci/numpy_and_numpy_base_1626271900803/work
- seaborn @ file:///tmp/build/80754af9/seaborn_1629307859561/work
- matplotlib @ file:///C:/ci/matplotlib-suite_1634667159685/work

## Acknowledgements
- This project was an assignment from Upgrad
- [https://www.learn.Upgrad.com](https://www.learn.Upgrad.com).


