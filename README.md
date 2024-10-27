# Maven-Market

MavenMarket Dashboard Project
![image](https://github.com/user-attachments/assets/ce95c2c9-58ae-4ac6-8cfc-4333d0dc7543)


Overview: The MavenMarket Dashboard project is an end-to-end Business Intelligence solution developed for Maven Market, a multinational grocery chain with locations across Canada, Mexico, and the United States.

Project Objectives:

Track and analyze key performance indicators (KPIs).
Connect and transform data for meaningful insights.
Build a robust relational data model.
Design an interactive, user-friendly dashboard.
Identify and segment high-value customers.

Data Source:
The project utilizes raw CSV data files provided by Maven Analytics.

Project Workflow:

Data Extraction: Imported raw CSV files into Power Query Editor for data processing.

Data Cleaning and Transformation: Standardized data types, promoted headers, and cleaned the data by removing null values and duplicates.

Data Enrichment: Added new columns for improved date-time analysis, including a calendar. Full names and email domains were also extracted for enhanced customer profiling.

Data Modeling: Built a relational data model using star and snowflake schema designs with one-to-many relationships unidirectional filter flow for optimal query performance.

Data Processing: Created essential KPIs and explicit measures using DAX (Data Analysis Expressions), including Total Revenue, Total Sales, and Total Profit and many more. Calculated columns were added as needed to facilitate deeper analysis.

Data Visualization and Dashboard Design: Developed a fully interactive dashboard featuring geospatial, transactional, and target-based insights. Visuals such as gauges, KPI cards, and Tree Maps were used to deliver intuitive, impactful representations of the data.
![image](https://github.com/user-attachments/assets/4c8f3461-f298-48bc-bbdf-f56e03b656ae)


Key Insights:

* Country Performance: The United States leads in profit, transactions, revenue, and orders across all three countries.
* Brand Analysis: "Hermanos" emerges as the top-performing brand in both profit and transaction volume, despite having high quantity of returns.
* Revenue Insights: Mexico generates more revenue than Canada, even though it has almost half the sales volume.





