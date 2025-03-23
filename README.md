# **Problem Statement**

### Business Context

In the banking and financial services industry, accurately assessing the creditworthiness of loan applicants is crucial for maintaining profitability and minimizing financial risk. When a bank receives a loan application, it must decide whether to approve or deny the loan based on the applicant's profile. Two key risks are associated with this decision:

1. If the applicant is a good credit risk, i.e. is likely to repay the loan, then not approving the loan to the person results in a loss of business to the bank
2. If the applicant is a bad credit risk, i.e. is not likely to repay the loan, then approving the loan to the person results in a financial loss to the bank

At HRE Bank, the loan approval process currently faces significant challenges in accurately predicting loan defaults. On average, the bank receives 10,000 loan applications per month, with an estimated default rate of 15%. This means that around 1,500 approved loans per month result in defaults, leading to substantial financial losses. Conversely, the bank also misses out on approximately 1,000 potential good credit applicants per month, further impacting potential revenue growth.

### Objective

The objective is to develop a predictive model to accurately forecast whether a loan applicant is likely to default, based on demographic and socio-economic profiles. By implementing this predictive model, HRE Bank can significantly reduce the number of high-risk loan approvals, thereby minimizing financial losses. Additionally, the model will help identify good credit risks more effectively, allowing the bank to capitalize on profitable lending opportunities. Overall, this solution aims to enhance the bank’s decision-making process, improve financial stability, and boost customer satisfaction.

### Dataset Description

- Age (Numeric: Age in years)
- Sex (Categories: male, female)
- Job (Categories : 0 - unskilled and non-resident, 1 - unskilled and resident, 2 - skilled, 3 - highly skilled)
- Housing (Categories: own, rent, or free)
- Saving accounts (Categories: little, moderate, quite rich, rich)
- Checking account (Categories: little, moderate, rich)
- Credit amount (Numeric: Amount of credit in DM - Deutsche Mark)
- Duration (Numeric: Duration for which the credit is given in months)
- Purpose (Categories: car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, vacation/others)
- Risk (0 - Person is not at risk, 1 - Person is at risk(defaulter))

  
