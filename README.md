# Lending Club Case Study
This project is for the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

Like most other lending companies, lending loans to `risky` applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.


## Table of Contents
* [Objectives](#objectives)
* [Data cleanup](#data-cleanup)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [How to run](#how-to-run)


## Objectives
The Objective is to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.


## Data cleanup
- We first removed all the columns with NULL values, and all the rows with all the NULL values
- We then removed all the columns, with unique value in all the rows.
- We then removed all the columns, with high number of null values (more than 60%).
- We then removed all the columns, which are not related to this project's analysis.
- Finally we did outlier treatment on our dataframe.


## Conclusions
- It seems that Mortgage and rent housing type borrowers are riskiest. They are also taking comparatively more amount of loan.
- It seems that the verified borrowers are taking higher loan amounts and are still being charged off comparatively more than non verified, which is of high risk.
- It seems that giving loans to the small businesses is riskiest, mainly because not all the small business successfully ran. But their volume is quite low. On the other hand debt consolidation is riskiest of all with very high volume of charged off borrowers.
- It seems that the borrowers living in RENT housing in CA state takes the highest amount of loan, they also have a highest charged off records, as compare to any other state.


## Technologies Used
- Python - Version 3.11.7
- numpy - Version 1.26.4
- pandas - Version 2.1.4
- matplotlib - Version 3.8.0
- seaborn - Version 0.13.2
- Jupyter Notebook - Version 7.0.8
- JupyterLab - Version 4.0.11
- Anaconda - Version 24.1.2


## How to run
1. git clone https://github.com/shubhankit92/LendingClubCaseStudy.git
2. cd LendingClubCaseStudy
3. copy the loan.csv file at this location
4. Execute the .ipynb file
