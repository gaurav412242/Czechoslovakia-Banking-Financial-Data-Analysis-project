# Czechoslovakia-Banking-Financial-Data-Analysis-project

🔷The Czechoslovakia Bank has provided a dataset containing information about its
financial activities for the past 5 years. By employing advanced analytics techniques, we intend to extract valuable patterns, trends, and actionable information from banking Dataset . 

🔷Objective:
The Czechoslovakia Bank wants to analyse  with actionable insights thatcan help them make informed decisions about their financial operations. The analysis willinvolve data cleaning, exploratory data analysis, and predictive modelling to identify patternsand trends in the data

🔷The dataset consists of the following tables:
1. Account: 2. Card: 3. Client: 4. Disposition: 5. District: 6. Loan: 7. Order: 8. Transaction:

🔷The bank has identified the following questions as important for their analysis:
1. What is the demographic profile of the bank's clients and how does it vary across
districts?
2. How the banks have performed over the years. Give their detailed analysis year &
month-wise.
3. What are the most common types of accounts and how do they differ in terms of usage
and profitability?
4. Which types of cards are most frequently used by the bank's clients and what is the
overall profitability of the credit card business?
5. What is the bank’s loan portfolio and how does it vary across different purposes and
client segments?
6. How can the bank improve its customer service and satisfaction levels?
7. Can the bank introduce new financial products or services to attract more customers and
increase profitability?


🔷Tools used for this project are : Microsoft Excell ,  AWS (S3) , Snowflake(Sql) ,MySQL Workbench(ER diagram) , Power-bi(Reporting) .

🔷Microsoft Excell - Performed Minor Cleaning and uploaded the files to the folders created in S3 bucket in aws .

🔷 AWS: Created an AWS S3 bucket and uploaded raw files into it .
 🔸Implemented secure access controls to the bucket, ensuring data confidentiality.
 🔸Enabled user-specific folders and data , upload capabilities for seamless data management.
 🔸Created Roles for the Users and Applied policies To the roles .

🔷SNOWFLAKE : 
 🔸Created tables and established a connection with AWS S3 for data integration. 
 🔸Configured Snowflake's storage integration , created Csv File Format , created External Stage  and created pipe to automate data ingestion. Set up a snowpipe to continuously ingest and update data from the external stage.
 🔸Created a master table and implemented key performance indicators (KPIs) using cleaned 
 data .
 🔸performed exploratory data analysis .

🔷MySQL Workbench: 
 🔸Created the same tables in MySQL workbench and created an ER diagram . 


🔷 POWER-BI : 🔸Connected Snowflake's clean data, master table, and KPIs to Power BI seamlessly. 
 🔸Leveraged the power of Power BI's features, such as data analysis expressions (DAX),measures, and parameters, to create an intuitive and insightful dashboard .
 🔸Publish the Report in the Power bi Service .
