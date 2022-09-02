# Case: Senior Tableau Developer
The case resolves around a hypothetical online store. They're selling merchandise
in different product categories to customers within the United States. Attached to the document you will find CSV files
which cover information about orders, returns and area managers of the e-commerce company. Please use this data
to prepare the following tasks.

### Tasks

1. Attached to this document you will find three CSV files:
    1. Orders.csv
    2. People.csv
    3. Returns.csv

Please load these files into a database of your choice. This database needs to be accessible to the analytical tool you select for the subsequent tasks. 
Examples for potential databases include SQLite (stored locally), a Postgres database (server running on localhost or a location of your choice) and BigQuery. These are just examples, please feel free to make your own choice. Just
don't work simply based on the CSV files. You can choose whether to import the data into your database via a data import wizard (e.g. provided as part of the SQL IDE Dbeaver) or by writing a Python script.


2. Using a free trial or an existing paid license open up a Tableau Desktop and connect to the database instance.


3. Using SQL and Tableau Desktop, please complete the following task:

   Imagine you – in the role of a BI consultant – had a meeting with one of the area managers coming up next week (which of them you'd like to meet is up to your choice). 

   I. Can you prepare a dashboard which allows you to evaluate key performance indicators (KPI) of the region. The manager didn't provide you with many requirements and except the ones below; however, the manager wants you to take your own initiative and have something ready when you meet.


    _"I want to be able to quickly compare current period vs previous period for each KPI for my region. Ideally, I would have a filter with these options: This Year, This Quarter and This Month. When one of those selected, I would also see the performance of one of those: Previous Year, Previous Quarter and Previous Month. Additionally, it would be great to have one compeletly custom date range option, e.g., 1/2/2021 as a start data and 15/3/2022 as an end date. Do you think you make this happen?"_


   II. The area manager is interested in evaluating performance of different products and their sub-/categories. Can you prepare a data product which allows to do so intuitively and efficiently?


    _"I want to be able to quickly review and compare performance of products in my region. See if there are some products or categories picking up on sales or problematic products or categories."_

4. Archive your work and send it to the person who provided you the case via email.
NOTE: The archive file should contain your SQL queries and Tableau Packaged Workbook with active data source extracts
   
### What we’ll be evaluating your submissions on

1. Your work is accurate, easy to read, follow & interpret and shows tendency for reusability & maintainability
2. Your work follows general best data visualisation practices, e.g., appropriate chart types, suitable dashboard structure
3. Your work considers the business / data at hand and the likely requirements of the stakeholder
