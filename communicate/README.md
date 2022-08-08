# (Dataset Exploration Title)
## by (your name here)


## Dataset

### The Prosper Loan data data set
> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
For this project I only chose to work with 19 variable that I felt were directly aligned with the question i was looking to find answers for. Among them as below

>- **Term**,  - The length of the loan expressed in months.
>- **LoanStatus**  - The current status of the loan: Cancelled,  Chargedoff, Completed, Current, Defaulted, FinalPaymentInProgress, PastDue.
>- **BorrowerRate** - The Borrower's interest rate for this loan. 
>- **IncomeRange** - The income range of the borrower at the time the listing was created.
>- **IsBorrowerHomeowne**r -A Borrower will be classified as a homowner if they have a mortgage on their credit profile or provide  documentation confirming they are a homeowner.
>- **ProsperRating (Alpha)** - The Prosper Rating assigned at the time the listing was created between AA - HR.  Applicable for loans originated after July 2009.
>- **ListingCategory (numeric)** - The category of the listing that the borrower selected when posting their listing: 0 - Not Available, 1 - Debt Consolidation, 2 - Home Improvement, 3 - Business, 4 - Personal Loan, 5 - Student Use, 6 - Auto, 7- Other, 8 
>- **Baby&Adoption,** 9 - Boat, 10 - Cosmetic Procedure, 11 - Engagement Ring, 12 - Green Loans, 13 - Household Expenses, 14 - Large Purchases, 15 - Medical/Dental, 16 - Motorcycle, 17 - RV, 18 - Taxes, 19 - Vacation, 20 - Wedding Loans
>- **BorrowerState** - The two letter abbreviation of the state of the address of the borrower at the time the Listing was created.
>- **EmploymentStatus** - The employment status of the borrower at the time they posted the listing.
>- **EmploymentStatusDuration** - The length in months of the employment status at the time the listing was created.
>- **DelinquenciesLast7Years** - Number of delinquencies in the past 7 years at the time the credit profile was pulled.
>- **MonthlyLoanPayment** - The scheduled monthly loan payment.
>- **StatedMonthlyIncome** - The monthly income the borrower stated at the time the listing was created.
>- **TotalProsperLoans** - Number of Prosper loans the borrower at the time they created this listing. This value will be null if the borrower had no prior loans. 
>- **LoanOriginalAmount** - The origination amount of the loan.
>- **LoanOriginationDate** - The date the loan was originated.
>- **Recommendations** - Number of recommendations the borrower had at the time the listing was created.
The data set can be found through the url 'https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv'


## Summary of Findings

> The following were the finding from the exploratory process.

In the explorations, I started by exploring the individual variable that I had sected to work with and see how they are distributed against the count. I found out that majority of the listing are the current on the loan status, meaning they are active. Also found out that the majority majority of over 17500 scored C, meaning properity rating is average. Also found out that Debt consolidation was the biggest reason for loan acquiring with above 50000 borrower while being trailed to second by with other by barely 10000 borrowers. Most borrowers are employed with over 70000 borrowers in the employemt bracket and mjority of them homeowners probably on mortgage.
Futher I decided to mojor on defaulted and completed loans. There are 19664 completed loans while those defalted is 6341. The first distribution depicted that most who defalted and completed their loans were those  borrowers who are employed. For the prosper rating I found out that  most rating of the dfaulted loans is D while the mosting rating among the Completed loasn is D as well. On the distribution of borrowing rate over the years since  listing began, I found out that there was a steady rise in 2009 from 0.195 to 0.235 in 2011 before dropping gradually to 0.185 in 2014. On pairwise correlation of numerical data, I found out that the numerical values are strong correlated.
I also found out that Borrowers who completed on category **debt consolidation**, **business**,**motorcycle** and **green loans** took the highest of the loans but debt consolidation and motorcycle category did tend to have high density under 18000 and 10000 respectively. The non-existent(The category was named _Not_availble_) category had all borrowers completed on payment. And lastly I found out that borrowers who are homeowners were on loans with lower borrow rates as compared to compariotes who are not home owners


## Key Insights for Presentation

For this project I chose only variables that I felt would anser my main objective.I realised that the factoers affected the the choices that borrowers made when going for the loans, and even narrowed that the dafaulters were actualy on higher insteret rate loans as compared to counter parts who complated their loans.