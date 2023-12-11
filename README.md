### Findings:
#### Application Data
- More users applied for cash loans compared to revolving loans.
- A higher number of females submitted their loan applications than males.
- The majority of applicants applied for loans unaccompanied, completed their secondary education, and work as laborers.
- Most applicants come from families with around 5 members.
- More applicants with payment difficulties were observed among those who changed their ID/registration and started their current jobs a few days before their loan applications.
- Younger clients are more likely to experience payment difficulties compared to older clients.
- Females are more prone to facing payment difficulties than males.

#### Previous Application Data
- Most of the refused and canceled loans are cash loans.
- The majority of approved loans fall under consumer loans.
- The most common client type is repeaters, with the majority of applications being approved.
- The XNA category for these five columns (NAME_PAYMENT_TYPE, NAME_SELLER_INDUSTRY, NAME_YIELD_GROUP, NAME_PORTFOLIO, NAME_PRODUCT_TYPE) has the highest number of canceled applications, while other columns typically have "approved applications" as the most common application status.
- POS and Cash are the highest distributed portfolio categories for approved and refused applications, while XNA is predominant for canceled and unused offers.
- The only reason for unused offers being rejected is "Client"; the top three reasons for refused applications are HC, LIMIT, and SCO.

### tldr
Click [HERE](https://github.com/haiilingg/EDA-project/blob/main/EDA%20project-HLT%20(application%20data).ipynb) (application data) and [HERE](https://github.com/haiilingg/EDA-project/blob/main/EDA%20project-HLT(%20previous%20data).ipynb) (previous data)for the Jupyter Notebooks where I performed EDA using Python.

Else, read the information below for the detailed project explanation.

## Loan Defaulter
This case study aims to identify patterns which indicate if a client has difficulty paying their instalments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. 

This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

![loan default](https://github.com/haiilingg/EDA-project/assets/130296433/cb8101e6-e355-44b2-9a6c-5b8fec6c2ac5)

### About the data
There are 2 files for this EDA analysis:
- Application Data (information of the client at the time of application. The data is about whether a client has payment difficulties)
- Previous Application Data (information about the client’s previous loan data. It contains the data whether the previous application had been Approved, Cancelled, Refused or Unused offer)

### Tasks Performed:
1. Data Exploration
2. Data Cleaning

### Types of analysis performed
1. Numerical Analysis
2. Univariate Analysis
3. Bivariate Analysis
4. Multivariate/ Correlation Analysis

