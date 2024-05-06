# Bank Loan Insight / Analysis using Power Bi and SQL
### Bussiness Requirement / Problem Satement

#### Total Loan Application :
We need to calculate the total number of loan applications received during a specified period. Additionally, it is essential to monitor the Month-to-Date (MTD) Loan Applications and track changes Month-over-Month (MoM).
#### Total Funded Amount :
Understanding the total amount of funds disbursed as loans is crucial. We also want to keep an eye on the MTD Total Funded Amount and analyse the Month-over-Month (MoM) changes in this metric.
#### Average Interest Rate :
Calculating the average interest rate across all loans, MTD, and monitoring the Month-over-Month (MoM) variations in interest rates will provide insights into our lending portfolio's overall cost.

#### Good Loan 
  1) Good Loan Application Percentage.
  2) Good Loan Applications.
  3) Good Loan Funded Amount.
  4) Good Loan Total Received Amount.

#### Bad Loan
  1) Bad Loan Application Percentage
  2) Bad Loan Applications
  3) Bad Loan Funded Amount
  4) Bad Loan Total Received Amount

### Loan Status
In order to gain a comprehensive overview of our lending operations and monitor the performance of loans, we aim to create a grid view report categorized by 'Loan Status.’ By providing insights into metrics such as 'Total Loan Applications,' 'Total Funded Amount,' 'Total Amount Received,' 'Month-to-Date (MTD) Funded Amount,' 'MTD Amount Received', and  'Average Interest Rate this grid view will empower us to make data-driven decisions and assess the health of our loan portfolio.

#### Monthly Trends by Issue Date 
To identify seasonality and long-term trends in lending activities.
#### Loan Term Analysis : 
To allow the client to understand the distribution of loans across various term lengths.
#### Employee Length Analysis : 
How lending metrics are distributed among borrowers with different employment lengths, helping us assess the impact of employment history on loan applications.
#### Loan Purpose Breakdown : 
Will provide a visual breakdown of loan metrics based on the stated purposes of loans, aiding in the understanding of the primary reasons borrowers seek financing.
#### Home Ownership Analysis :
For a hierarchical view of how home ownership impacts loan applications and disbursements.

#### Details Analysis
Need for a comprehensive 'Details Dashboard' that provides a consolidated view of all the essential information within our loan data. This Details Dashboard aims to offer a holistic snapshot of key loan-related metrics and data points, enabling users to access critical information efficiently.

## Solution Approach:

To address the problem statement, the following approach was used:

### Data Import and Initial Analysis: 
  The Bank Loan data was provided in a SQL dump file, which was imported into a SQL database. Initial insights were drawn from the data using SQL queries and analysis techniques to gain a preliminary understanding of the sales trend.

###   Connecting SQL Database to Power BI: 
  The SQL database was connected to Power BI, establishing a live connection or importing the necessary data tables into Power BI.

###  Data Modeling and Relationship Creation: 
   Data modeling was performed within Power BI to create relationships between the relevant tables in the SQL database. This step ensured that the data could be properly analyzed and visualized.

### Data Cleaning and Transformation: 
Power BI's data transformation features, such as Power Query, were utilized to clean and transform the data. Irrelevant entries, duplicates, and inconsistencies were removed or resolved, ensuring the data was accurate and reliable.

###  Dashboard Creation 

#### Dashboard 1 | Summary

### Key Performance Indicators (KPIs)

Total Loan Applications: We need to calculate the total number of loan applications received during a specified period. Additionally, it is essential to monitor the Month-to-Date (MTD) Loan Applications and track changes Month-over-Month (MoM).

Total Funded Amount: Understanding the total amount of funds disbursed as loans is crucial. We also want to keep an eye on the MTD Total Funded Amount and analyse the Month-over-Month (MoM) changes in this metric.

Total Amount Received: Tracking the total amount received from borrowers is essential for assessing the bank's cash flow and loan repayment. We should analyse the Month-to-Date (MTD) Total Amount Received and observe the Month-over-Month (MoM) changes.

Average Interest Rate: Calculating the average interest rate across all loans, MTD, and monitoring the Month-over-Month (MoM) variations in interest rates will provide insights into our lending portfolio's overall cost.

Good Loan v Bad Loan KPI’s

Good Loan:
  1) Good Loan Application Percentage
  2) Good Loan Applications
  3) Good Loan Funded Amount
  4) Good Loan Total Received Amount

Bad Loan
  1) Bad Loan Application Percentage
  2) Bad Loan Applications
  3) Bad Loan Funded Amount
  4) Bad Loan Total Received Amount

Loan Status Detail ana
In order to gain a comprehensive overview of our lending operations and monitor the performance of loans, we aim to create a grid view report categorized by Loan Status By providing insights into metrics such as . Total Loan Applications, Total Funded Amount, Total Amount Received, Month-to-Date (MTD) Funded Amount, MTD Amount Received and Average Interest Rate this grid view will empower us to make data-driven decisions and assess the health of our loan portfolio.

#### Dashboard 2 | Overview

Monthly Trends by Issue Date (Line Chart):  To identify seasonality and long-term trends in lending activities.

Loan Term Analysis (Donut Chart): To allow the client to understand the distribution of loans across various term lengths.

Employee Length Analysis (Bar Chart): How lending metrics are distributed among borrowers with different employment lengths, helping us assess the impact of employment history on loan applications.

Loan Purpose Breakdown (Bar Chart): Will provide a visual breakdown of loan metrics based on the stated purposes of loans, aiding in the understanding of the primary reasons borrowers seek financing.

Home Ownership Analysis (Tree Map): For a hierarchical view of how home ownership impacts loan applications and disbursements.

#### Dashboard 3 | Details 

##### Objective
The primary objective of the Details Dashboard is to provide a comprehensive and user-friendly interface for accessing vital loan data. It will serve as a one-stop solution for users seeking detailed insights into our loan portfolio, borrower profiles, and loan performance.


## Expected Outcome 
By implementing the above solution expects to achieve the following outcomes:
   * Enhanced Data Analysis: The connection between the SQL database and Power BI enables real-time or near-real-time analysis of the sales trend. The solution provides users with the ability to explore and analyze data more efficiently, leading to better insights and understanding.

   * Improved Decision Making: The creation of the three dashboards (Summary, Overview and Details) equips users with a comprehensive view of the Bank Loan from different perspectives. 

   * Increased Efficiency: By utilizing Power BI's data transformation features, data cleaning and transformation tasks are streamlined. This saves time and effort, allowing users to focus more on analyzing the data and extracting valuable insights.







