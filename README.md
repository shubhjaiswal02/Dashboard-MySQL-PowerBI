# HR-Dashboard_MySQL_PowerBI

Welcome to the HR Dashboard project repository! This project showcases the creation of a comprehensive HR dashboard using SQL, MySQL Workbench, and Power BI. The dashboard offers insights into employee distribution, facilitating informed decision-making for organizational growth.

Page 1 :
![Dashboard-1](./Dashboard-1.png)

Page 2 :
![Dashboard-2](./Dashboard-2.png)


## Project Highlights

- **Dashboard Creation**: Developed a comprehensive dashboard tailored for HR, providing a centralized view of employee distribution and related insights.

- **Data Management**: Managed HR data spanning from 2000 to 2020, encompassing over 22,000 rows, ensuring a robust foundation for analysis and visualization.

- **Data Optimization**: Leveraged MySQL to clean and optimize the dataset, reducing its size by 80% - 90% and enhancing query performance.

- **Visualization**: Transformed complex HR data into informative visuals using Power BI, including two dashboard pages with over 3 charts, a map, and other interactive tools.

## Dashboard Features

### Employee Distribution Insights

- Gain an understanding of employee distribution across different departments, roles, and time periods.

### Informed Decision-Making

- Make data-driven decisions by analyzing historical HR data and identifying trends.

### Data Optimization

- Utilized MySQL to clean and optimize the dataset, ensuring efficient querying and analysis.

### Interactive Visualizations

- Interact with dynamic charts, maps, and tools to explore HR data and uncover insights.

## Project Details

### Dataset Information

- Data Time Range: 2000 - 2020
- Number of Rows: 22,000+
- Original Dataset Size: 2.84 MB
- Optimized Dataset Size: 129 KB

### Tools Used

- SQL
- MySQL Workbench
- Power BI

### Folder Structure

- `/Answers_of_queries`: Contains SQL queries used to clean, filter, and optimize the dataset and  olds the Power BI files for the interactive HR dashboards.

## Getting Started

1. Clone this repository to your local machine.
2. Import the dataset into MySQL and execute the provided SQL queries for data optimization.
3. Open the Power BI dashboard files to explore the visualizations and gain insights.

## Conclusion

This HR Dashboard project showcases the power of data management, optimization, and visualization in enhancing HR decision-making. The combination of SQL, MySQL Workbench, and Power BI enables a comprehensive view of employee distribution trends and informs strategic organizational choices.


## Limitations
- Some records had negative ages and these were excluded during querying(967 records). Ages used were 18 years and above.
- Some termdates were far into the future and were not included in the analysis(1599 records). The only term dates used were those less than or equal to the current 
  date.
