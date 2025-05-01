# Microsoft Fabric - Getting Started with Lakehouse

I explored how Microsoft Fabric enables modern data engineering workflows using **Lakehouse architecture**. I completed the full data pipeline — from setting up the environment, uploading files, creating Delta tables, running SQL queries, to visualizing data in a Power BI report.

## 🎯 Objective

- Create a workspace with Fabric capacity  
- Set up a Lakehouse to manage data  
- Upload and ingest CSV data  
- Query structured data using SQL  
- Build a visual report using Power BI  
- Understand how Delta Lake and OneLake work together in Microsoft Fabric  

## 🔧 What I Did

### 1. Created a Fabric Workspace  
I logged into Microsoft Fabric and created a new workspace with Fabric Trial capacity. This workspace served as the central place to manage data assets and analytics.

### 2. Created a Lakehouse  
I created a new Lakehouse within the workspace. The Lakehouse consists of two sections:  
- **Tables** (for Delta Lake tables with schema)  
- **Files** (for raw data files in OneLake)  

### 3. Uploaded a CSV File  
I downloaded the sales.csv file and uploaded it to a new subfolder named `data` inside the Files section of the Lakehouse.

### 4. Loaded File into a Table  
Using the "Load to Tables" option, I created a Delta table named `sales` from the uploaded CSV file. The schema was inferred, and I verified that the data loaded correctly.

### 5. Queried the Data with SQL  
Using the SQL analytics endpoint, I wrote a query to calculate revenue by product by grouping items and multiplying quantity by unit price.  
This helped identify the top-performing products based on total revenue.

### 6. Created a Visual Query  
I used the visual query builder to:  
- Select SalesOrderNumber and SalesOrderLineNumber  
- Group by SalesOrderNumber  
- Count distinct line items per order  

### 7. Built a Power BI Report  
I used the default semantic model and Power BI tools to create a report:  
- Visualized Item and Quantity using a clustered bar chart  
- Saved the report as **Item Sales Report**

### 8. Verified All Resources  
The workspace now contains:  
- The Lakehouse  
- SQL analytics endpoint  
- Default semantic model  
- Power BI report  

## 🧠 What I Learned

- How Lakehouse architecture blends data lake flexibility with warehouse-style structure  
- Hands-on experience with Delta Lake tables and SQL queries in Fabric  
- Seamless data-to-visual pipeline using Microsoft Fabric and Power BI  
- Importance of metadata layers for managing file-based data at scale  
- How OneLake centralizes storage across services in Microsoft Fabric  

## 🔗 Connect with Me

👉 [Follow me on LinkedIn](https://www.linkedin.com/in/eyilan/)
