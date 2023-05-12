# Predictive-Analysis-of-Telco-Customer-Churn

# Introduction

Telco — a telecommunications or communication service provider (CSP) company that transports information electronically through telephony and data communication services in the networking industry. Since the invention of mobile telephony Telco have also become Internet service providers (ISPs). However, the company’s churn rate has been increasing over the past year, which is a cause for concern. Customer churn is an important metric for businesses as it measures the rate at which customers are leaving the company. As the company faces intense competition in the telecommunications industry, it is essential to maintain high customer retention rates.

The primary objective of this analysis was to identify the churn rate and develop recommendations to improve customer retention.

# Data Collection

The project workflow is shown below:

![image](https://github.com/olajumokeabe/Predictive-Analysis-of-Telco-Customer-Churn/assets/125363157/33babba0-feab-4a86-9479-631b86535d2d)
Microsoft Excel was used for this analysis.

The data was downloaded from Kaggle, and you can access it (https://www.kaggle.com/datasets/blastchar/telco-customer-churn/download?datasetVersionNumber=1).

The Telco customer churn data contains information about a fictional telco company that provided phone, multiple lines and internet services to it’s 7043 customers.

The data set includes information about:

. Customers who left within the last month — the column is called Churn
. Services that each customer has signed up for — phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
. Customer account information — how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
. Demographic info about customers — gender, age range, and if they have partners and dependents


# Data Cleaning and Transformation

The raw data contains 7043 rows (customers) and 21 columns (features). Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

Primary key is a column in a table that uniquely identifies the rows in that table and in the case of this dataset, the Customer ID can be identified as primary key.

I loaded the data into power query editor to check if the Customer ID is unique and without duplicates and make sure that the data conform to the specified format.

I discovered the data was clean and void of error, so I proceeded to analyzing and visualizing.

# Data Cleaning and Transformation

First let’s calculate the churn rate; customer churn rate measures the percentage of customers who stop using a service over a specified period while retention rate is the rate at which customers stay with a business in a given period.

. The customer churn rate is calculated using the formula:

(Lost Customers ÷ Total Customers at start of period) x 100

The churn rate for our dataset is 26.54% and the retention is 73.46%.

![churn%](https://github.com/olajumokeabe/Predictive-Analysis-of-Telco-Customer-Churn/assets/125363157/5ec1ba95-b01b-43bf-8309-615e71b21f9c)


There are almost equal number of male and female customers which also have no effect on a customer’s choice of churning or retaining.

![genderchurn](https://github.com/olajumokeabe/Predictive-Analysis-of-Telco-Customer-Churn/assets/125363157/e8e0025f-bc47-4e99-981c-f9ad7498d370)


The percentage of senior citizens using the service is very small and majority them stopped using the services of the company. This could mean that interest in using telecommunication services drops after the age of 65.

![agechurn](https://github.com/olajumokeabe/Predictive-Analysis-of-Telco-Customer-Churn/assets/125363157/0a76d6e3-9f06-4359-89b4-d520efdd2e34)


About 51.70% customers are unmarried. These customers have higher churn rate than customers with partners. Customers who have spouses and dependents actually have a lower percentage of churn. This is inversely proportional to those who do not have a partner and dependents.

![contractpartner](https://github.com/olajumokeabe/Predictive-Analysis-of-Telco-Customer-Churn/assets/125363157/6c925049-fe2e-4d9c-8048-9734433d6f6e)


3875 customers opt for the Month-to-Month subscription plan, and they are the most likely to churn, with churn rate numbers at 1655 compared to others who subscribe to the One-Year or Two-Year plan. Customers under the Two year subscription plans have less churn rate.

![contratchurn](https://github.com/olajumokeabe/Predictive-Analysis-of-Telco-Customer-Churn/assets/125363157/dd4921f9-51f9-4882-ab29-7bfe8a484dd9)


The most preferred payment method is Electronic check with 1071 users churning making it the payment method with the highest number of churn as compared to its other method.

![paymentchurn](https://github.com/olajumokeabe/Predictive-Analysis-of-Telco-Customer-Churn/assets/125363157/3b8eb8ed-c64e-4579-8a0d-01d75cd800e6)


# Visualization

The interactive dashboard involves the use of slicers to get better knowledge of churn by service provided.

![Telco](https://github.com/olajumokeabe/Predictive-Analysis-of-Telco-Customer-Churn/assets/125363157/be4fbf09-d81c-47e1-a49a-616ddaa9214a)


# Recommendations
Insights could not be given on why the customers are churning the service as the information was not provided.

However, the major reason customers will churn the services will be mainly as a result of but not limited to; competition, pricing, quality of service provided, service tech support, e.t.c. the company should carry out market survey or request for feedbacks from its customers in order to know the main reasons why customers are churning the service.

The company should improve the quality of its services and make them more appealing to customers. It should also offer discounts, free upgrades, price reduction, and/or adding new features to what they offer to encourage customers to stay.

The company should also see to proper training of its technical support staffs to provide excellent support to customers. They should provide more ways for customers to reach out for support.

The company should deploy different marketing schemes, for example, sending mails, calls, or text customers and inform them on new decisions and offers.

The preferences of older customers should be considered and plans should be put in place for senior citizens to this effect in order to encourage them in using the services.

This can improve the company’s operations and can make them a better competition to its opponent.

Link to interactive dashboard on excel;

https://1drv.ms/x/s!Amhisb_pS3Whboj0tU2Secyu-2w
