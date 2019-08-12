# Loan Data Exploration

## Dataset

The original data set from Prosper contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

To make it clear, I've only selected 11 features that may be related to the questions I'm interested in.(Term, LoanStatus, BorrowerAPR, BorrowerRate, ProsperRating(numeric), EmploymentStatus, EmploymentStatusDuration, StatedMonthlyIncome, LoanOriginalAmount, MonthlyLoanPayment, CurrentDelinquencies)


## Summary of Findings

In the exploration, I am mainly interested in what affect the BorrowerAPR, and I found that there was a strong relationship between the APR and I found Prosper Rating has strong effect on APR and borrower rate, the higher the rating is given the lower the APR is. Other than rating, loan original amount, monthly payment and term also can influence APR but in a smaller scale.
Also, categorical variable like Loan status and Employment status are factors as well.

Outside of the main variables of interest, I see the strong postive correlation of monthly loan payment and loan original amount, 
and there's no big delinquency difference between employed borrowers and not employed ones.


## Key Insights for Presentation

For the presentation, I focus on just the effect of the main variable of interest on the borrower APR. Firstly, I introduce each variate by showing their distributon, and then start to combine two variable to see their correlation.

Finally, I plot 3-4 variables to further strengthen the relationship, I found out that the term effect on APR actually related their prosper rating, longer terms higher rates is not always the case. Moreover, unemployed borrowers don't really have higher delinquencies.

