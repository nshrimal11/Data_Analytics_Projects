# Coffee Sales Data Analysis Project


#### Preview of Dashboard:
<p align="center">
    <img src="Coffee_Sales_Dashboard_Thumbnail.jpg" alt="Spotify Dashboard Preview" width="85%">
</p>

## Project Overview

This project involves analyzing a sample dataset of coffee sales to derive actionable insights through data cleaning, transformation, and visualization in Microsoft Excel. The goal was to create an interactive dashboard that provides a clear overview of sales performance, customer behavior, and product trends. This project demonstrates proficiency in data manipulation, advanced Excel functions, and data visualization techniques, showcasing a structured approach to data analysis suitable for a data analyst role.

The dataset was sourced from: https://github.com/mochen862/excel-project-coffee-sales/blob/main/coffeeOrdersData.xlsx

## Dataset Description

The dataset consists of three tables:

- **Orders**: Contains transactional data, including order ID, date, customer ID, product ID, and sales details.
- **Customers**: Includes customer information such as customer ID, name, email, country, and loyalty card status.
- **Products**: Details product attributes like product ID, coffee type, roast type, size, unit price, and sales.

## Project Objectives

- Clean and preprocess the dataset to ensure data integrity.
- Enrich the Orders table by integrating relevant data from the Customers and Products tables.
- Build an interactive dashboard with PivotTables, PivotCharts, and slicers to visualize key metrics.
- Derive insights to understand sales trends, customer preferences, and product performance.

## Methodology

The project followed a systematic approach to data analysis, with the following key steps:

### 1. Data Preparation and Cleaning

- **Data Integration**:
  - Used **XLOOKUP** to populate customer-related columns in the Orders table (Customer Name, Email, Country) by referencing the Customers table. The formula was applied three times, once for each column, ensuring accurate data retrieval.
  - Implemented **INDEX MATCH** to dynamically populate product-related columns (Coffee Type, Roast Type, Size, Unit Price, Sales) from the Products table. A single formula was designed to flexibly retrieve all product attributes, improving efficiency.
- **Data Formatting**:
  - Formatted the Date column to ensure consistent date representation.
  - Converted the Size column to include units (e.g., "kg") for clarity.
  - Applied currency formatting to the Unit Price and Sales columns to enhance readability.
- **Duplicate Removal**:
  - Selected the entire dataset and used the **Remove Duplicates** feature under the 'Data' tab to eliminate redundant records, ensuring data accuracy.
- **Table Conversion**:
  - Converted the cleaned dataset into an Excel **Data Table** (using `Ctrl + T`) to enable dynamic referencing and simplify further analysis.

### 2. Data Analysis and Visualization

- **PivotTables and PivotCharts**:
  - Created PivotTables to summarize key metrics, such as total sales, sales by country, and customer purchase patterns.
  - Generated PivotCharts to visualize trends, including:
    - **Total Sales Over Time**: A line chart to track sales performance across dates.
    - **Sales by Country**: A bar chart to compare sales across different regions.
    - **Top 5 Customers**: A column chart to highlight the most valuable customers based on total purchases.
- **Slicers and Timeline**:
  - Added interactive slicers for filtering by:
    - Date (via a Timeline slicer)
    - Product Size
    - Loyalty Card Status
    - Roast Type
  - Configured slicers under **Report Connections** to ensure all PivotCharts were synchronized with the selected filters, enabling seamless interactivity.
- **Dashboard Creation**:
  - Designed an interactive dashboard consolidating the visualizations and slicers. The dashboard provides a user-friendly interface to explore sales data, filter by key dimensions, and uncover insights.

## Insights Gained

- **Sales Trends**: Identified seasonal patterns in coffee sales, with peaks during specific months, suggesting opportunities for targeted marketing campaigns.
- **Geographic Performance**: Certain countries contributed disproportionately to sales, indicating potential for region-specific promotions.
- **Customer Behavior**: Loyalty card holders accounted for a significant portion of sales, highlighting the effectiveness of the loyalty program.
- **Product Preferences**: Specific roast types and sizes were more popular, informing inventory and product development strategies.

## Tools and Techniques Used

- **Microsoft Excel**: Data cleaning, transformation, and visualization.
- **Excel Functions**: XLOOKUP, INDEX MATCH for data integration.
- **Features**: Data Tables, PivotTables, PivotCharts, Slicers, Timeline, Remove Duplicates.
- **Dashboard Design**: Interactive visualization layout for stakeholder engagement.

## Key Learnings

- **Data Integration**: Gained proficiency in using XLOOKUP and INDEX MATCH to merge data from multiple tables efficiently.
- **Dynamic Analysis**: Learned to create dynamic formulas and Data Tables to streamline data processing.
- **Visualization Best Practices**: Understood the importance of interactive elements like slicers and timelines in enhancing user experience.
- **Insight Communication**: Developed skills in translating raw data into actionable business insights through clear visualizations.

## Future Improvements

- Incorporate additional datasets, such as marketing spend or inventory levels, to provide a more holistic analysis.
- Explore advanced visualization tools like Power BI or Tableau to enhance dashboard interactivity.
- Apply statistical analysis to identify correlations between customer demographics and purchasing behavior.

## How to Run the Project

1. Download the dataset from the source repository.
2. Open the dataset in Microsoft Excel.
3. Follow the steps outlined in the Methodology section to replicate the data cleaning, transformation, and visualization process.
4. Explore the dashboard by interacting with the slicers and timeline to uncover insights.

## Conclusion

This project showcases a comprehensive data analysis workflow, from data preparation to interactive visualization. By leveraging Excel's advanced features, I was able to transform raw coffee sales data into a professional dashboard that delivers actionable insights. This experience has strengthened my skills in data manipulation, analysis, and storytelling, preparing me to tackle real-world data challenges in a data analyst role.

---

Feel free to connect with me on LinkedIn or explore my other projects on GitHub!
