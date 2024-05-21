# Project Name
> Lending Club case Study.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Problem Statement: 
>You work for a consumer finance company specializing in various types of loans for urban customers.
>The company must decide on loan approvals based on the applicant's profile, balancing the risk of losing business by rejecting good applicants and the risk of financial loss by approving those likely to default. 
>The provided data includes information on past loan applicants and their default status. The goal is to identify patterns indicating a likelihood of default to inform decisions such as loan denial, loan amount reduction, or higher interest rates for risky applicants. 
>This case study involves using Exploratory Data Analysis (EDA) to understand the impact of consumer and loan attributes on default tendencies.

### Objective:
>Understand and identify driving factors behind loan defaults.
>Provide insights for risk assessment.
>Identify patterns indicating a high risk of loan default.



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

1)The exploratory data analysis has highlighted several key factors influencing loan default risks, such as loan amount, interest rates, annual income, loan purpose, home ownership, employment length, and public records.
2)By understanding these factors, the company can better assess risk and make informed decisions on loan approvals, terms, and interest rates.
3)Implementing these insights and recommendations will help minimize financial losses due to loan defaults and improve the overall profitability and sustainability of the lending business.

### Driver Variables Identified
 1.Loan Amount
 2.Interest Rate
 3.Annual Income
 4.Loan Purpose
 5.Home Ownership
 6.Employment Length
 7.Debt-to-Income Ratio (DTI)
 8.Verification Status
 9.Public Records and Bankruptcies
 10.Geographical Location

### Business Insights
1)Loan Amount and Default Risk: Higher loan amounts are associated with increased risk of default. Most loans are in the range of 5k-14k, but loans closer to the maximum (27k-28k) exhibit higher default rates.
2)Interest Rates: Loans with higher interest rates (16% and above) have a significantly higher chance of being charged off. The average interest rate for defaulted loans is higher than for fully paid loans.
3)Annual Income: Applicants with lower annual incomes (0-20k) have higher default rates, while those with incomes above 80k have a lower propensity for default. Annual income is inversely proportional to the likelihood of loan default.
4)Loan Purpose: Loans taken for small businesses and debt consolidation have higher default rates compared to other purposes.
5)Home Ownership: Majority of the loan defaulters are either renting or have a mortgage. Homeownership slightly reduces the likelihood of default.
6)Employment Length: Applicants with less than 1 year of employment experience have a higher tendency to default. Longer employment length correlates with lower default rates.
7)Debt-to-Income Ratio (DTI): Higher DTI values correlate with a higher risk of loan default. A low DTI ratio is associated with lower interest rates and better repayment behavior.
8)Verification Status: Loans that are not verified have higher default rates. Verification status plays a crucial role in assessing risk.
9)Public Records and Bankruptcies: Applicants with public records or previous bankruptcies have a higher chance of defaulting. Historical financial behavior is a strong predictor of future default risk.
10)Geographical Insights: States like CA, NV, and FL have higher default rates, suggesting regional economic factors may play a role.



### Recommendations
1)Stricter Loan Approval for High Amounts: Implement more rigorous screening for higher loan amounts to mitigate default risks.
2)Interest Rate Management: Adjust interest rates based on risk assessment. Higher-risk applicants should be offered loans at higher rates with caution or additional guarantees.
3)Income-Based Screening: Focus on applicants with stable and higher incomes. Introduce minimum income thresholds for loan approval.
4)Purpose-Specific Strategies: Tailor loan terms and interest rates based on the purpose, especially for high-risk purposes like small business loans.
5)Employment Verification: Emphasize employment stability by requiring a minimum employment length for loan approval. Consider offering better terms to those with longer employment histories.
6)Reduce Unverified Loans: Increase efforts to verify applicant information. Unverified loans should either be limited or subject to higher interest rates and stricter terms.
7)Regional Risk Adjustments: Consider regional economic conditions and adjust loan terms and risk assessments accordingly.




<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas
- NumPy 
- Seaborn 
- MatplotLib


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was completed as part of case study provided by UpGrad IITB Programme for the Machine Learning and Artificial Intelligence course.


## Contact
Created by 
Gaurav Kumar
Dinkar Navaneetha

 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
