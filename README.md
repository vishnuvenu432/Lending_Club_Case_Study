# Lending Club – Case Study
> A consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- The company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
- Objective is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilize this knowledge for its portfolio and risk assessment.
- Primary goal is to identify the driving factors (or driver variables) behind loan default such that, the company can utilize this knowledge for its portfolio and risk assessment. 
- Using EDA for risk assessment


## Conclusions
- The Probability of defaulting is high when:
    - Loan Applicants not owing home (Mortgage or Rent) and have high Annual Income Range (60K - 70K)
    - Loans with interest rates between 9% - 17%
    - Applicants with Annual Income range between 35k - 70k and availing loan for Debt Consolidation.
    - Loan Applicants with >10 years of experience and with loan amount > 10K or with interest rate (>10%)
- Indicators for loan defaulters 
    - Annual Income, Home Ownership, Purpose of Loan, Loan Amount, Interest Rate


## Technologies Used
- Python
- Jupyter Notebook
- Libraries
    - numpy - version 1.21.5
    - pandas - version 1.4.4
    - matplotlib - version 3.5.2
    - seaborn - version 0.11.2


## Contribution
- Vishnu Venu
- Aishwarya Sudevan


## Acknowledgements
Reference
- https://github.com/
- https://stackoverflow.com/

### Developed as part of the Exploratory Data Analysis Module required for Executive PG Programme in Machine Learning & AI - IIIT,Bangalore.