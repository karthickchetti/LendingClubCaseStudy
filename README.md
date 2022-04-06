# Lending Club Case Study
> The lending club wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Lending club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
- Background
    * When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
        * If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
        * If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- Business Problem
    * We are trying to perform risk analytics on the loan dataset of the customers
- Dataset
    * The dataset contains the information about past loan applicants and whether they ‘defaulted’ or not. 

## Conclusions
The major factors for charging off loans :
 1) Loan amount – For amounts greater than 10000
 2) Annual income - For income less than 50000
 3) Interest rate - For interest rates greater than 10%
 4) Debt to Income Ratio – For dti greater than 15
 5) Term – For loan tenure of 60 months
 6) Employee Length – For employees with more than 10 years of experience
 7) Purpose – Debt consolidation and small business
 8) Earliest Credit Line – For customers starting credit lines from 1985 to 2005
 9) Address State – Customers from California and Florida

“It is recommended for the lending club to be more cautious in providing loans to customers who fall under any of the above criteria”

## Technologies Used
- pandas - version 1.3.4
- numpy - version 1.20.3
- seaborn -version 0.11.2
- matplotlib - version 3.4.3

## Acknowledgements
We would like to thank Upgrad for providing the opportunity to work on this project

## Contact
Created by [@karthickchetti] & [@kvc0608] - feel free to contact us!
