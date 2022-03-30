
# Processes  : 
### 1-  Data Sources
    https://www.kaggle.com/yeanzc/telco-customer-churn-ibm-dataset
### 2- Data Gathering
### 3- Data Preprocessing 
### 4- Data Integration [SSIS]
### 5- Data Analysis & Creating Cubes  [SSAS] 
   ![image](https://user-images.githubusercontent.com/70976091/153679556-8dc9d871-866f-4f18-896e-6f2905399d7e.png)
### 6- Paginated Reports [SSRS]
### 7- Dashboards (Power BI)
## Dashboards (Power BI)
![Screenshot_2](https://user-images.githubusercontent.com/70976091/153680609-eb8b0db9-1b30-40f7-a6ce-bf5e5f6b544b.png)


![Screenshot_3](https://user-images.githubusercontent.com/70976091/153680969-bffecf59-550a-4d4a-94fe-2682973cdf23.png)
![Screenshot_4](https://user-images.githubusercontent.com/70976091/153680977-3849ae26-f0a9-4399-b75b-60fb797d56e9.png)
![Screenshot_5](https://user-images.githubusercontent.com/70976091/153680981-74b376a8-951f-4a73-abb5-0b29bf18f23e.png)
![Screenshot_1](https://user-images.githubusercontent.com/70976091/153680984-1de8edf6-3f66-4a8c-972e-c733758a73f3.png)

# Project: Telco Customer Analysis - ITI 'BI Track' Graduation Project

## Table of Contents
<ul>
<li>Introduction</li>
<li>Data Exploring</li>
<li>Data Preprocessing</li>
<li>Data Integration</li>
<li>Data Visualization</li>
<li>Conclusions</li>
</ul>

## Introduction

### Dataset Description 

#### Context
A fictional telco company that provided home phone and Internet services to 7043 customers in California in Q3. The original dataset is on the link [here](https://www.kaggle.com/yeanzc/telco-customer-churn-ibm-dataset).

#### Data Description
7043 observations with 33 variables
<ul>
<li>CustomerID : A unique ID that identifies each customer.</li>
<li>Count : A value used in reporting/dashboarding to sum up the number of customers in a filtered set.</li>
<li>Country: The country of the customer’s primary residence.</li>
<li>State: The state of the customer’s primary residence.</li>
<li>City: The city of the customer’s primary residence.</li>
<li>Zip Code: The zip code of the customer’s primary residence.</li>
<li>Lat Long: The combined latitude and longitude of the customer’s primary residence.</li>
<li>Latitude: The latitude of the customer’s primary residence.</li>
<li>Longitude: The longitude of the customer’s primary residence.</li>
<li>Gender: The customer’s gender: Male, Female.</li>
<li>Senior Citizen: Indicates if the customer is 65 or older: Yes, No </li>
<li>Partner: Indicate if the customer has a partner: Yes, No. </li>
<li>Dependents: Indicates if the customer lives with any dependents: Yes, No. Dependents could be children, parents, grandparents, etc.</li>
<li>Tenure Months: Indicates the total amount of months that the customer has been with the company by the end of the quarter specified above.</li>
<li>Phone Service: Indicates if the customer subscribes to home phone service with the company: Yes, No. </li>
<li>Multiple Lines: Indicates if the customer subscribes to multiple telephone lines with the company: Yes, No.</li>
<li>Internet Service: Indicates if the customer subscribes to Internet service with the company: No, DSL, Fiber Optic, Cable.</li>
<li>Online Security: Indicates if the customer subscribes to an additional online security service provided by the company: Yes, No.</li>
<li>Online Backup: Indicates if the customer subscribes to an additional online backup service provided by the company: Yes, No.</li>
<li>Device Protection: Indicates if the customer subscribes to an additional device protection plan for their Internet equipment provided by the company: Yes, No.</li>
<li>Tech Support: Indicates if the customer subscribes to an additional technical support plan from the company with reduced wait times: Yes, No</li>
<li>Streaming TV: Indicates if the customer uses their Internet service to stream television programing from a third party provider: Yes, No. The company does not charge an additional fee for this service.</li>
<li>Streaming Movies: Indicates if the customer uses their Internet service to stream movies from a third party provider: Yes, No. The company does not charge an additional fee for this service.</li>
<li>Contract: Indicates the customer’s current contract type: Month-to-Month, One Year, Two Year.</li>
<li>Paperless Billing: Indicates if the customer has chosen paperless billing: Yes, No</li>
<li>Payment Method: Indicates how the customer pays their bill: Bank Withdrawal, Credit Card, Mailed Check</li>
<li>Monthly Charge: Indicates the customer’s current total monthly charge for all their services from the company.</li>
<li>Total Charges: Indicates the customer’s total charges, calculated to the end of the quarter specified above.</li>
<li>Churn Label: Yes = the customer left the company this quarter. No = the customer remained with the company. Directly related to Churn Value.</li>
<li>Churn Value: 1 = the customer left the company this quarter. 0 = the customer remained with the company. Directly related to Churn Label.</li>
<li>Churn Score: A value from 0-100 that is calculated using the predictive tool IBM SPSS Modeler. The model incorporates multiple factors known to cause churn. The higher the score, the more likely the customer will churn.</li>
<li>CLTV: Customer Lifetime Value. A predicted CLTV is calculated using corporate formulas and existing data. The higher the value, the more valuable the customer. High value customers should be monitored for churn.</li>
<li>Churn Reason: A customer’s specific reason for leaving the company. Directly related to Churn Category.</li>

</ul>











> **Note**: This project is an ITI graduation project so it's a training project. All data used are fictional and there's no restrictions on editing, deleting or any process can be used on data to make it more suitable to answer our analysis questions. 


### Question(s) for Analysis


