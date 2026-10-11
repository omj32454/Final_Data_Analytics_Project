Sales & Transaction Analysis

1. Problem Statement:-

   The objective of this project is to analyze sales and transaction data to understand business performance, identify sales trends, evaluate customer payment preferences, and determine the best-performing products and locations.

   The project uses Python, Pandas, Excel, and Power BI to clean, analyze, and visualize the data and generate meaningful business insights for better decision-making.

2. Dataset Information:-

   The dataset contains sales and transaction records with the following columns:

     - Transaction ID: Unique identifier for each transaction.
     - Item: Product purchased.
     - Quantity: Number of units purchased.
     - Price Per Unit: Price of one unit.
     - Spent: Total amount spent per transaction.
     - Payment Method: Method used for payment.
     - Location: Transaction location.
     - Transaction Date: Date of the transaction.

   The dataset is used to analyze revenue, product performance, transaction patterns, payment methods, and location-wise sales.

3. Data Cleaning Process:-

   The dataset was inspected using Pandas to identify missing values, duplicate records, and incorrect data types.

   The cleaning process included:

   - Checking dataset dimensions and column information.
   - Identifying and removing duplicate records.
   - Handling missing values in important fields.
   - Converting numerical columns to appropriate numeric data types.
   - Converting Transaction Date into datetime format.
   - Checking invalid quantities and negative monetary values.
   - Creating Year, Month, Month Name, and Day columns.
   - Exporting the cleaned dataset for further analysis.

4. Exploratory Data Analysis:-

   Exploratory Data Analysis (EDA) was performed using Python and Pandas to understand business performance.

   The analysis covered:

   - Total sales and transaction count.
   - Total quantity sold and average transaction value.
   - Item-wise sales performance.
   - Location-wise sales comparison.
   - Payment method distribution.
   - Monthly sales trends.
   - Identification of top-performing products and locations.

   Matplotlib was used to visualize sales trends and support data-driven analysis.

5. Power BI Dashboard:-

   An interactive Power BI dashboard was developed to present the key findings of the sales analysis.

   The dashboard includes:

   - KPI cards for sales, transactions, quantity, and average transaction value.
   - Monthly and daily sales trends.
   - Top-performing items by revenue.
   - Location-wise sales analysis.
   - Payment method distribution.
   - Interactive slicers for Year, Month, Item, Location, and Payment Method.

   The dashboard helps users explore sales performance across different time periods, products, and locations.

6. BUSINESS INSIGHTS:-

 Sales & Transaction Analysis

    1:- Top-Selling Item -> Identify the item with the highest total quantity sold.
    2:- Highest Revenue Item -> Identify which item generated the highest Total Spent.
    3:- Payment Preference -> Identify the most commonly used payment method.
    4:- Location Performance -> Identify the location that generating the highest total sales.
    5:- Sales Trend -> Identify that which month had the highest or lowest sales.


   Business Recommendations:

   - Focus on the products that generate the highest revenue.
   - Investigate low-performing locations to identify improvement opportunities.
   - Use monthly sales trends to support inventory and sales planning.
   - Make payment processes convenient for customers using popular payment methods.

6. Tools and Technologies:-
   - Python
   - Pandas and NumPy
   - Matplotlib
   - Microsoft Excel
   - Microsoft Power BI
   - GitHub
7. Project Structure
   - data/ — Cleaned dataset
   - Sales_Analysis.ipynb — Python analysis notebook
   - Sales_Dashboard.pbix — Power BI dashboard
   - dashboard_screenshot.png — Dashboard preview
   - Business_Insights.txt — Key findings and recommendations
   - README.md — Project documentation
8. Conclusion

   This project demonstrates the complete data analytics workflow, from data cleaning and exploratory analysis to interactive dashboard development and business insights. It helped develop practical skills in Python, Pandas, data visualization, Power BI, and business reporting.

   The project provides a structured approach to understanding sales performance and supporting data-driven business decisions.


