# loan-data-from-prosper

The data set contains information concerning 113912 loan listings, 
including loan amount, borrower rate (or interest rate), current loan status, 
borrower income, and many others. For the purpose of this analysis
we focused on the following:

ProsperRating - The Prosper Rating assigned at the time the listing was created: 0 - N/A, 1 - HR, 2 - E, 3 - D, 4 - C, 5 - B, 6 - A, 7 - AA. Applicable
for loans originated after July 2009.

Term - The length of the loan expressed in months.
ListingCategory - The category of the listing that the borrower selected when posting their listing
>0 - Not Available; 1 - Debt Consolidation; 2 - Home Improvement; 3 - Business
>4 - Personal Loan; 5 - Student Use; 6 - Auto; 7- Other; 8 - Baby&Adoption
>9 - Boat; 10 - Cosmetic Procedure; 11 - Engagement Ring; 12 - Green Loans
>13 - Household Expenses; 14 - Large Purchases; 15 - Medical/Dental
>16 - Motorcycle; 17 - RV; 18 - Taxes; 19 - Vacation; 20 - Wedding Loans

LoanOriginalAmount - The origination amount of the loan.

BorrowerAPR-The Borrower's Annual Percentage Rate (APR) for the loan.

EstimatedReturn - The estimated return assigned to the listing at the time it was created. Estimated return is the difference between the Estimated
Effective Yield and the Estimated Loss Rate. Applicable for loans originated after July 2009.

LoanStatus - The current status of the loan: Cancelled, Chargedoff, Completed, Current, Defaulted, FinalPaymentInProgress, PastDue. The
PastDue status will be accompanied by a delinquency bucket.
StatedMonthlyIncome - The monthly income the borrower stated at the time the listing was created.
