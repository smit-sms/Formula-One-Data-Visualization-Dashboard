# Formula-One-Data-Visualization-Dashboard

![F1_Dashboard](https://github.com/smit-sms/Formula-One-Data-Visualization-Dashboard/assets/52400400/5517412a-b042-4bba-95d3-5de4081dcc06)


## Introduction

This project involves creating an interactive and comprehensive Formula One data visualization dashboard using Microsoft Power BI. The dashboard is designed to analyze various metrics related to Formula One races, drivers, and teams from 1950 to 2023. The main goal is to provide insights into race wins, championships, and performance metrics across different periods and circuits.

## Project Overview

### Purpose

The purpose of this project is to analyze and visualize Formula One race data to provide insights into factors contributing to race wins, team performance, and historical trends. The dashboard enables users to explore metrics such as win percentages, race wins by circuit, and the impact of starting positions on race outcomes.

### Tools Used

- **Microsoft Power BI**: A powerful business analytics tool used to create interactive visualizations and dashboards.

### Data Sources

- **Kaggle**: [Formula 1 World Championship (1950-2023)](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)
- **Wikipedia**: 
  - [List of Formula One World Drivers' Champions](https://en.wikipedia.org/wiki/List_of_Formula_One_World_Drivers%27_Champions)
  - [List of Formula One World Constructors' Champions](https://en.wikipedia.org/wiki/List_of_Formula_One_World_Constructors%27_Champions)

## Features

- **Race Wins by Decade**: Visual representation of race wins per team on a yearly and decade basis.
- **Championships Won, Podiums, and Race Wins**: Metrics displayed in big number tiles for quick insights.
- **Race Wins by Circuit**: Geographic visualization showing race wins across different circuits worldwide.
- **Starting Position Affect on Race Wins**: Analysis of how starting positions influence race outcomes.
- **Interactive Filters**: Dropdown menus to filter data by drivers, teams, and years for customized views.

## Data Preprocessing

1. **Initial Data Loading**: The dataset was loaded into Power BI using CSV files from Kaggle and championship data from Wikipedia.
2. **Data Cleaning**: Data types were analyzed, duplicates removed, null values handled, and unnecessary columns eliminated.
3. **Data Integration**: The F1 dataset was merged with championship data to provide comprehensive insights.
4. **Data Transformation**: Additional cleaning, column renaming, data type adjustments, and error rectifications were performed.

## Visualizations

- **Sunburst Chart**: Depicts the distribution of race wins by team and decade.
- **Line Chart**: Shows the impact of starting positions on race outcomes.
- **Geographic Map**: Displays race wins by circuit across continents.
- **Bar Charts**: Illustrate race wins and podiums achieved by different teams and drivers.

## Instructions to Run the Dashboard

1. **Download Power BI Desktop**: [Download Link](https://powerbi.microsoft.com/en-us/desktop/)
2. **Download and Unzip the Project Files**
3. **Open the Power BI File**:
    - Locate and open `F1_dashboard.pbix` in Power BI Desktop.
4. **Resolve Dataset Errors (if any)**:
    - Go to `Transform Data` -> `Data Source Settings`.
    - Change the data source path to the correct dataset files in your local system.
    - Apply changes and refresh the dataset.

## How to Use the Dashboard

1. **Explore the Interactive Elements**: Use dropdown menus to filter data by specific drivers, teams, and years.
2. **Analyze Metrics**: Examine various metrics like win percentages, race wins by circuit, and the impact of starting positions.
3. **Compare Performance**: Compare the performance of different teams and drivers across decades and continents.

## Critical Analysis

### Strengths

- **Clarity and Focus**: Key metrics are highlighted using big number tiles.
- **Comparative Analysis**: Bar charts and sunburst charts facilitate comparison.
- **Detailed Insights**: Multi-level visualizations provide in-depth analysis.

### Weaknesses

- **Complexity**: Some charts may be complex for users unfamiliar with data visualization.
- **Potential Misinterpretation**: Mixed charts combining different data sets could lead to confusion.

## References

1. [Microsoft Power BI](https://www.microsoft.com/en-us/power-platform/products/power-bi)
2. [Formula 1 World Championship (1950-2023) on Kaggle](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)
3. [Wikipedia - List of Formula One World Drivers' Champions](https://en.wikipedia.org/wiki/List_of_Formula_One_World_Drivers%27_Champions)
4. [Wikipedia - List of Formula One World Constructors' Champions](https://en.wikipedia.org/wiki/List_of_Formula_One_World_Constructors%27_Champions)
