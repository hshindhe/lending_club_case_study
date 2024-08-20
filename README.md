# Lending Club Case Study

We have been provided customer loan data and the data dictionary of a firm that provides Business, Home, Personal loan to its customers across the different state of US. By performing Exploratory Data analsyis we have been asked to provide insights into the past and existing loans and help the firm to get risk analysis of its customers on who will pay the loan promptly, default on the loan. This will also help the firm to make informed decisions in future on who to approve  a loan and also who to reject a loan. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

The main entities of interest are Loan and Customer.
Loan has its own attributes such as amount requested, term, interest rate, purpose etc.
Customers has its own attributes such as annual income, past history in terms of publick records, DTI, join applications and so on.
We have to look at each entities on their own as well as combine different attributes of these entities to ascertain
	various facts from past history
	also draw conclusions on patterns observed to help make future calls on approving / rejecting a loan.
A loan denied to a prompt paying customer is a opportunity lost for the firm.
Likewise, a loan approved for a likely defaulter is a bad asset to the firm which is a loss.


## Conclusions
Based on the above graph analysis related to the charged off loans, there is more probability of defaulting on the below scenarios:
1. The city of California has the highest number of loan availed.
2. Debt consolidation is the biggest reason why people are availing loans
3. Most of the people who have availed loan are in the annual income range of 40 k to 80 k
4. Most of the loans that have been funded are in the range of 10 k to 20 k
5. Employees with more than 10 years of experience are the largest availers of loan.
6. The second buggest group is people with < 1 years of exprience.
7. Thankfully most of the loans are already paid, unfortunately a good percentage are defaultes and a small portion is in progress
8. Loans which were not verified are higher than the other categories.
9. Lower amounts are funded at a higher rate of interest and seem to recede gradually as we approach the 25 k mark, Any loan given after 25 k, there is a         	sharp decrease in interest rates
10.Looks like loans offered at 36 months are most defaulted though there is not much difference between them in the bigger scheme of things
11.Looks like loans defaults are rising year on year and loan offered in 2011 are the most defaulted
12. Loans taken during the month of December are the most that are likely to be defaulted.
13. Looks like the loans that were offered in the interest rate of 11-15 % have defaulted the most
14. Looks like customers with annual income of 26-50 k have defaulted the most
15. Looks like loans with installments in 151-300 are the most defaulted


## Technologies Used
- Python - version 3.11.7
- Pandas - version 2.1.4
- Numpy - version 1.26.4
- Seaborn - version 0.12.2
- Matplotlib - version 3.8.0
- Jupyter Notebook - version 7.0.8

## Acknowledgements
- Thanks to the wonderful case study, It helped revise the EDA concepts, and go through the various plots once again and apply them to this case study.

## Contact
Created by Harish Shindhe and Harshit Sharma
