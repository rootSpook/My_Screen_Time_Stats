# Screen Time and Notifications Analysis

## Description

Sabanci University DSA210 Introduction to Data Science Course Fall 2024-2025 Term Project.  
This project analyzes the relationship between screen time and notifications received across different apps.

For the final report, see [here](https://github.com/rootSpook/My_Screen_Time_Stats/).

## Table of Contents
**[Motivation](#motivation)**  

**[Tools](#tools)**  

**[Data Source](#data-source)**  

**[Data Processing](#data-processing)**  

**[Data Visualizations](#data-visualizations)**  

**[Data Analysis](#data-analysis)**  

**[Findings](#findings)**  

**[Limitations](#limitations)**  

**[Future Work](#future-work)**  

## Motivation

The motivation for this project stems from a curiosity about how app notifications impact screen time. By exploring this relationship, I aim to uncover patterns in my own device usage and derive actionable insights.

## Tools

- **[Jupyter Notebook](https://jupyter.org/):** For coding and documentation.  
- **[Pandas](https://pandas.pydata.org/):** For data manipulation and analysis.  
- **[Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/):** For creating static visualizations.  
- **[Scikit-learn](https://scikit-learn.org/):** For linear regression modeling.  
- **[Excel](https://www.microsoft.com/en-us/microsoft-365/excel):** For initial data collection and storage.  

## Data Source

The data for this project was manually collected from my personal device over a period of several days. It includes the following metrics:
- **Screen time (minutes):** Time spent on each app per day.
- **Notifications:** Number of notifications received from each app per day.
- **Pickups:** Number of times the device was accessed.

The dataset can be found [here](https://github.com/rootSpook/My_Screen_Time_Stats/tree/main/raw_data).

## Data Processing

The collected data underwent cleaning and preprocessing in `main.ipynb`. Key steps included:
- Removing incomplete entries.
- Aggregating data to calculate daily totals for screen time and notifications.
- Generating derived metrics like screen time per notification.

## Data Visualizations

Visualizations were created to explore trends and relationships within the dataset. Highlights include:
- Scatter plots to visualize app usage trends day by day.
- Bar charts for total screen time and notifications per day.
- Dual-axis plots to compare screen time and notifications.

## Data Analysis

The primary analysis involved:
1. Investigating the correlation between screen time and notifications.
2. Performing linear regression to quantify the relationship between the two variables.

Findings and detailed analysis steps can be found in `main.ipynb`.

## Findings

1. There is no significant correlation between screen time and notifications.  
2. Linear regression shows a weak relationship, with a very low R² value.  

_For detailed findings, see the [final report](https://github.com/rootSpook/My_Screen_Time_Stats/)._  

## Limitations

1. **Data Scope:** The dataset is limited to personal usage over a short time span, making generalizations difficult.  
2. **Data Completeness:** Not all apps reported notifications accurately, leading to potential biases.  

## Future Work

1. **Expand the Dataset:** Collect data over a longer period and from multiple devices.  
2. **Integrate Additional Metrics:** Include metrics like app categories or usage goals.  
3. **Advanced Analysis:** Explore machine learning techniques for deeper insights.  

