# Telco Customer Churn Analysis

## Project Overview

Customer churn is an important business problem because losing existing customers can affect company revenue and growth.

The goal of this project is to analyze customer data and identify factors associated with customer churn. The analysis focuses on customer characteristics, contract type, tenure, monthly charges, and services.

## Business Questions

1. What is the overall churn rate?
2. Which customer groups have higher churn rates?
3. Does contract type affect churn?
4. Is churn related to customer tenure?
5. Is churn related to monthly charges?
6. Which services are associated with higher churn?

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Key Findings

- The overall customer churn rate is **26.5%**.
- Month-to-month customers have a much higher churn rate (**42.7%**) than customers with one-year (**11.3%**) or two-year (**2.8%**) contracts.
- Customers in their first 12 months have the highest churn rate (**47.4%**). Churn decreases as customer tenure increases.
- Senior customers without a partner showed the highest churn rate among the analyzed customer segments (**48.9%**).
- Customers with higher monthly charges generally show higher churn, although the relationship is not strictly linear.
- Fiber optic customers have a churn rate of **41.9%**, compared with **19.0%** for DSL customers.
- Customers without Online Security or Tech Support have substantially higher churn rates than customers with these services.

## Business Recommendations

- Encourage month-to-month customers to switch to longer-term contracts by testing incentives such as discounts or additional benefits.
- Focus retention efforts on customers during their first year.
- Pay additional attention to customer segments with higher churn rates and investigate the reasons behind their behavior.
- Test whether promoting Online Security and Tech Support as part of service packages can improve customer retention.
- Investigate the high churn rate among Fiber optic customers, including possible factors such as pricing, service quality, and customer experience.
- Consider offering renewal incentives before customer contracts expire.

## Dataset

The dataset contains information about customer demographics, account information, services, charges, and churn status.

Source: [Telco Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/karimasen/telco-customer-churn-dataset)

License: MIT

## Project Files

- `telco-customer-churn-analysis.ipynb` — complete data analysis, visualizations, findings, and recommendations
- `telco.csv` — dataset used in the analysis

## Conclusion

The analysis identified several customer characteristics associated with higher churn. The strongest patterns were observed among month-to-month customers, customers with shorter tenure, and Fiber optic customers.

These findings can help identify higher-risk customer groups and provide a starting point for developing and testing customer retention strategies.
