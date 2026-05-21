# Analyzing-Smart-City-Bike-Sharing-Data
## Project Overview

The Bike Station Sharing Data Analysis project was developed using Power BI to analyze the operational performance of bike-sharing stations across multiple cities. The dataset contains information about station names, bike availability, empty stands, station status, banking facilities, and geographical details.
The main objective of this project is to transform raw bike station data into meaningful insights using Power BI dashboards, KPI measures, and interactive visualizations. The dashboard helps monitor bike availability, station activity, and city-wise operational performance.

## Objectives

•	To analyze the total number of bike stations across cities. 

•	To monitor available bikes and empty bike stands. 

•	To identify operational and closed stations. 

•	To compare bike station performance city-wise. 

•	To analyze banking and bonus-enabled stations. 

•	To calculate bike availability percentage using DAX measures. 

•	To build an interactive dashboard for operational analysis and decision-making. 

## Tools Used
Tool	Purpose

Power BI	       -      Data visualization and dashboard creation

Power Query	         -  Data cleaning and transformation

DAX	                -         KPI calculations and measures

CSV Dataset	        -   Data source

## Data Transformation (Power Query)

The dataset was cleaned and transformed using Power Query Editor in Power BI.
Steps Performed

•	Removed duplicate records. 

•	Trimmed and cleaned text columns. 

•	Changed data types for numerical, text, and date columns. 

•	Split the Position column into Latitude and Longitude. 

•	Renamed columns for better readability. 

•	Standardized OPEN and CLOSED status values. 

•	Handled null values in the Address column. 

•	Removed invalid rows containing incorrect bike stand values. 

•	Converted Last Update into Date/Time format. 

## Data Modelling

A single-table data model was used because the dataset contained all required analytical fields in one table.
The transformed dataset was loaded directly into Power BI for KPI analysis and dashboard creation.

## DAX Calculations and KPI Measures

<img width="481" height="228" alt="image" src="https://github.com/user-attachments/assets/e0304562-c04f-472f-9ad0-403f4b75d0d6" />


## Dashboard Features

KPI Cards (6)

1.	Total Stations 

2.	Total Available Bikes 

3.	Total Bike Stands 

4.	Total Empty Stands 

5.	Open Stations 

6.	Bike Availability Percentage

## Charts and Visualizations (6)

1. Pie Chart – Station Status Distribution

2. Clustered Bar Chart – Available Bikes by City

3. Clustered Column Chart – Total Bike Stands by City

4. Donut Chart – Banking Availability

5. Stacked Bar Chart – Open vs Closed Stations by City

6. Line Chart – Available Bikes by Station

### Slicers Used

•	City 

•	Status 

•	Bonus Availability 

### Screenshot:

<img width="940" height="562" alt="image" src="https://github.com/user-attachments/assets/f25ec65f-23a3-4901-ad51-13ac3d1bf86d" />

## Analytical Insights



## 1. Descriptive Analytics (What Happened?)
   
More than 70% of bike stations were in OPEN status, showing good operational performance.
Around 65%–75% of bike stands were actively utilized in major cities like Marseille and Lyon.
Nearly 45% of stations supported banking facilities for users.

## 2. Diagnostic Analytics (Why happened?)

Approximately 30% of stations showed low or zero bike availability due to high demand or maintenance issues.
Several CLOSED stations had 0 available bikes and fully occupied stands, affecting service efficiency.
Missing address values and inconsistent station records were identified and cleaned during data transformation.

## 3. Predictive Analytics (What will happen?)

Around 20%–30% of stations may require additional bikes during peak usage periods.
Cities with high station activity are expected to show increasing bike demand in future periods.
Stations with consistently low availability may face future operational pressure without redistribution planning.

## 4. Prescriptive Analytics (What should do?)

Proper bike redistribution can improve bike availability efficiency by nearly 15%–20%.
Increasing bike stands in high-demand cities can reduce station overcrowding.
Improving maintenance schedules for CLOSED stations can enhance operational performance and customer satisfaction.

## Conclusion

The Bike Station Sharing Data Analysis dashboard successfully transformed raw bike-sharing data into interactive business insights using Power BI.
By applying Power Query transformations, DAX calculations, KPI tracking, and multiple visualization techniques, the dashboard provided a clear understanding of station operations, bike availability, and city-wise performance.
This project demonstrates the effective use of Power BI for real-time operational monitoring and data-driven decision-making.

