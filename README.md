# LendingClubCaseStudy
**Case study to analyze the factors for an applicant to default**

## Business Understanding

When a person applies for a loan, there are two types of decisions that could be taken by the company:

* **Loan accepted**: If the company approves the loan, there are 3 possible scenarios described below:  
  * **Fully paid**: Applicant has fully paid the loan (the principal and the interest rate)  
  * **Current**: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.  
  * **Charged-off**: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan  
* **Loan rejected**: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

The aim is to identify patterns which indicate if a person is likely to default (quits repaying the loan borrowed), which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

To achieve this goal, we will be using EDA (Exploratory Data Analysis) which would involve understanding the dataset, collecting and cleaing of data, analyzing the data with multiple graphs/plots and finally providing a few observations and recommendations to the club.


EXPLORATORY DATA ANALYSIS  
Flow of the analysis is as follows:

* Data Sourcing  
* Cleansing the dataset  
* Data Analysis  
  * Univariate Analysis  
  * Bivariate Analysis  
* Derived Metrics

## Recommendations

* Verification and background check for large loan applications is of prime importance as verified loans (large loans are more likely to default)
* Need to check other sources of income, pervious or ongoing debts with other parties, or assets for applicants with low annual income.
* Check why certain states have a high default rate when compared to others.


