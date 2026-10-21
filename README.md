# Maven-Toys-Challenge-Dashboard
Using Microsoft Excel to analyze sales performance, profitability, and historical trends to support data-driven retail expansion decisions.
## Introduction
Maven Toys plans to expand its business by opening new stores. To support this decision, an analysis of sales performance, profitability, historical trends, and the contribution of each location to sales revenue across different cities is required to identify cities and specific locations with strong potential to support business expansion.
This project is part of the Maven Toys Challenge, in which the role of a Business Intelligence Consultant is undertaken to analyze data and develop data-driven recommendations for business expansion.
The analysis is conducted using Microsoft Excel, leveraging its data processing, data modeling, analytical, and interactive visualization features to develop a single-page dashboard.
## Project Goals
The primary objective of this project is to identify cities and locations with strong potential for new store expansion based on several key business indicators :
  1. **Sales Performance** : Comparing sales revenue across cities to identify those with the strongest sales performance.
  3. **Profitability** : Evaluating the profit contribution of each city to identify those with the highest profitability.
  4. **Historical Trend** : Understanding the consistency and changes in bussiness performance over time to assess growth potential.
  5. **Location Revenue Contribution** : Comparing revenue across locations within selected cities to identify the most promising locations for new store openings.

The analysis results are presented in a single-page dashboard to support the evaluation of expansion candidates and data-driven business decision-making.
## Data Sourcing
This data was gotten from the Maven Analytics playground as part of the Maven Toys challenge. Here is a **[link to the dataset](https://mavenanalytics.io/challenges/maven-toys-challenge)** for your reference.

Disclaimer: The data in this dataset is fictitious and was made for the purpose of learning and practice.
## Tools and Features Used
The following Microsoft excel features were used in this analysis :

1. Power Query : Imports, cleans, transforms, and prepares data for analysis.
2. Power Pivot : Builds data models and manages relationships between tables to enable cross-table analysis.
3. DAX (Data Analysis Expressions) : Creates measures to calculate business metrics used in the analysis and dashboard.
4. PivotTable : Summarizes and calculates business performance metrics, KPIs, and historical trends by city, location, category, and time period before visualization.
5. PivotChart : Visualizes performance comparisons and historical trends.
6. Slicer : Provides interactive filters to explore data in the dashboard.
## Analysis Workflow

### 1. Data Prepation
Data is prepared using Power Query by checking data structures and making necessary   adjustments to ensure readiness for analysis.
![Data Prepation](Images/data-prepation.png)
### 2. Data Modeling and Calculations
Power Pivot is used to build data models and table relationships, while DAX creates measures to calculate key business metrics, such as revenue and profit.
![Data Modeling](Images/data-modeling.png)
### 3. City Performance Analysis
Cities are ranked by revenue and profit. Cities that rank in the top five for both metrics are selected as potential expansion candidates.
![City Performance Analysis](Images/city-performance-analysis.png)
### 4. Historical Trend Analysis
Revenue and profit trends are analyzed over time to identify cities with stable or growing performance and distinguish them from those experiencing declines.
![Historical Trend Analysis](Images/historical-trend-analysis.png)
### 5. Location Revenue Contribution Analysis
Calculates each location’s revenue contribution as a percentage of the city’s total revenue to identify the highest-contributing locations.
![Location Revenue Contribution Analysis](Images/location-revenue-contribution.png)





