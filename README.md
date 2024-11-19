# Project Name
> Lending Club Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Lending Club case study is first assigment as part of MS Upgrad program
- As part of this we need identify what attributes can be used to identify if a applicant is worthy or given loan or he is risk and will default
- To arrive at this Objective we Use EDA (Exploratory Data Analysis) and
  1. Clean the data set and identify required key columns
  2. Do Univariate and Bi Variate anaylsis to columns and validate how they impact the risk of giving loan

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. Post data cleaning  Final Shape Shape:(39717, 21)
2. Funded Amount Analysis indicated that if the funding is above higher than the probability of default is higher , however the margin difference is not conclusive ,we may have to do hypothesis on this
3. Interest rate : If the interest is higher than 15% the likelihood of defaulting is higher. Hence lower rate of interest is one of ways to manage risk profiles.
4. Int Rate Groups 16%-20% are at high risk of default , validate payment capacity before giving loans at high ROI
5. Employment term more than 10 years and have high rate of interest i.e 16%-20% have high chance of risk
6. Loans taken under 31k have high risk of loan defaulting
7. LC Grade B and D have highest risk, within B and C , Sub Grades - B3 and C2 have the highest number of defaults
8. Loan applicants who stay in Rented houses have high probability of default
9. Loan taken for purpose of debt consolidation have very high probability of defaulting
10. While loan verification is important the impact is very limited on risk
11. CA State applicants have the highest amt of loan default risk
12. Loan given in Dec Month has highest risk esp in the year 2011 Dec month applicants has highest risk of default
13. Loans given with funding amount <10k has highest risk, we should do through validation before given low value risk
14. Home Improvement, Credit Card and debt consolidation loan given below a certain threshold have clear indication of default
15. Based on home ownership , customer who stay in mortgage house and have income range from 70-80k have high risk of default
16. Higher the funding amount, higher the interest rate, however highest risk is when int rate is btw 15-16%
17. When loan is taken for small business , debt consolidation , house have a risk of loan defaulting
18. Loan when given to applicants with 10+ years employment exp and rate of interest 16-20% the risk of defaulting is higher.

## Technologies Used
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import warnings
warnings.filterwarnings('ignore')

## Contact
Created by [@rhamsagar-sf] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
