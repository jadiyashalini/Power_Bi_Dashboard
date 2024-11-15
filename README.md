# Dynamic Car Sales Dashboard in Power BI

## Project Overview
The goal of this project is to design and develop a dynamic, interactive Car Sales Dashboard using Power BI. This dashboard will visualize key performance indicators (KPIs) related to car sales, enabling us to monitor sales performance over time, identify trends, and make data-driven decisions to drive growth.

## Objectives
1. **KPI Analysis**: The dashboard should deliver real-time insights into key performance indicators (KPIs) related to sales, helping us monitor progress, identify growth opportunities, and make informed decisions.
2. **Visual Analytics**: Utilize various charts, maps, and grids to represent sales data comprehensively, covering sales trends, body styles, colors, regions, and company performance.

## Problem Statements

### Problem Statement 1: KPIs Requirement
The dashboard will focus on visualizing the following KPIs to help track and analyze sales performance effectively.

#### 1. Sales Overview
   - **Year-to-Date (YTD) Total Sales**
   - **Month-to-Date (MTD) Total Sales**
   - **Year-over-Year (YOY) Growth in Total Sales**
   - **Difference between YTD Sales and Previous Year-to-Date (PTYD) Sales**

#### 2. Average Price Analysis
   - **YTD Average Price**
   - **MTD Average Price**
   - **YOY Growth in Average Price**
   - **Difference between YTD Average Price and PTYD Average Price**

#### 3. Cars Sold Metrics
   - **YTD Cars Sold**
   - **MTD Cars Sold**
   - **YOY Growth in Cars Sold**
   - **Difference between YTD Cars Sold and PTYD Cars Sold**

### Problem Statement 2: Charts Requirement

#### 1. YTD Sales Weekly Trend
   - Display a line chart to illustrate the weekly trend of YTD sales.
   - **X-axis**: Weeks
   - **Y-axis**: Total Sales Amount

#### 2. YTD Total Sales by Body Style
   - Use a pie chart to show the distribution of YTD total sales across different car body styles.

#### 3. YTD Total Sales by Color
   - Use a pie chart to present the contribution of various car colors to the YTD total sales.

#### 4. YTD Cars Sold by Dealer Region
   - Showcase the YTD car sales data by dealer regions using a map chart to visualize the geographical distribution of sales.

#### 5. Company-Wise Sales Trend (Tabular Grid)
   - Create a tabular grid that displays each company's name and their corresponding YTD sales figures.

#### 6. Detailed Car Sales Information (Grid)
   - Include a grid that provides detailed information on each car sale, such as car model, body style, color, sales amount, dealer region, date, etc.

---

## Implementation Steps

1. **Data Preparation**: Import and clean the data to ensure accurate representation of all necessary KPIs and metrics.
2. **KPI Calculation**: Use Power BI’s DAX functions to calculate YTD, MTD, YOY, and PTYD metrics for Total Sales, Average Price, and Cars Sold.
3. **Visualization Development**: Implement the required visualizations using Power BI’s charting tools:
   - Line chart for weekly trends
   - Pie charts for body style and color distributions
   - Map chart for regional sales
   - Tabular grid for company-wise sales trends
   - Detail grid for individual car sale records
4. **Styling and Formatting**: Ensure that all visuals and grids are formatted consistently for ease of readability and professional presentation.

## Dashboard Features

- **Real-Time KPI Updates**: The dashboard will update KPIs dynamically as data is refreshed.
- **Interactive Filtering**: Allow users to filter by date, body style, color, and region to explore specific segments of the data.
- **Geographical Sales Insights**: The map visualization provides insights into regional sales trends.
- **Detailed Sales View**: Users can explore each car sale's details using a comprehensive grid with relevant information.

