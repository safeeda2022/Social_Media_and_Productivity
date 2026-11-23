# Social Media Habits And Productivity
Data Analysis Project

## Project Introduction
Social media has become an essential part of students' daily lives, influencing how they communicate, access information, and spend their free time. Although social media platforms provide educational and entertainment opportunities, excessive usage may negatively affect students' academic performance, concentration, sleep patterns, and productivity.
This project, "Students' Social Media Habits vs. Productivity," aims to analyze the relationship between students' social media usage patterns and their productivity levels using a dataset containing information about screen time, study hours, sleep habits, notifications, distractions, and addiction levels.

## Problem objective
Students often struggle to balance their academic responsibilities with their social media activities. Spending excessive time on social media may reduce study time, interrupt concentration through frequent notifications, and affect sleep quality.
However, not all students who use social media extensively experience low productivity. Factors such as study habits, sleep duration, breaks, and self-control may also influence productivity.
The main objectives of this project are:
1.	Analyze students' daily screen time and social media usage patterns.
2.	Examine the relationship between social media hours and study hours.
3.	Investigate the impact of sleep duration on productivity.
4.	Identify whether frequent notifications contribute to distractions.
5.	Study the relationship between nighttime usage and sleep patterns.
6.	Analyze how coffee consumption and daily breaks relate to focus and productivity.
7.	Investigate the relationship between addiction levels and distraction scores.
8.	Identify the most important factors associated with students' productivity.
9.	Present meaningful insights through statistical analysis and data visualizations

## Dataset Description
- Source - kaggle
- Number of rows - 10000
- Number of fields - 13

## Tools and Technologies
The following tools can be used to complete the project:
Tool|Purpose|
|---|---|
Python|	Data analysis and manipulation|
Pandas	|Data cleaning and processing|
NumPy|	Numerical calculations|
Matplotlib|	Data visualization|
Seaborn	Statistical| Data visualization|
Jupyter Notebook|	Analysis and documentation|

## Data Analysis Methodology
The project will follow these major stages:
#### Data Collection
•	Import the dataset from a CSV or Excel file using Python.
#### Data Cleaning
•	Identify missing values.
•	Remove duplicate records.
•	Check incorrect or inconsistent values.
•	Identify and investigate outliers.
•	Correct data types and categorical values.
#### Exploratory Data Analysis (EDA)
•	Calculate mean, median, mode, standard deviation, minimum, and maximum.
•	Examine the distributions of important variables.
•	Identify patterns and trends.
#### Data Visualization
•	Create charts to identify trends, comparisons, distributions, and relationships.
#### Correlation Analysis
•	Examine relationships between social media habits, lifestyle factors, distraction, focus, and productivity.
#### Interpretation and Conclusion
•	Summarize findings and provide recommendations for improving students' productivity.

## Conclusion
This project aims to explore how students' social media habits relate to their productivity by analyzing digital usage patterns, academic routines, and lifestyle behaviors.
Through exploratory data analysis, statistical techniques, and data visualization, the study will identify important relationships between social media consumption, concentration, sleep, distraction, and productivity

## Project phases

### Phase 1
In phase 1 the data is found , SRS is developed and initial findings are observed through jupyter notebook.

### Phase 2
In phase 2 data wrangling is performed for more accurate analysis.
- Number of null values in each field is found. Every field consisted null values.
- No duplicates where found
- From the statistical details, three columns where observed to have unrealistic values and outliers. Its found through IQR method and treated with cap values.
- The null values in each column is imputed appropriately using the statistical measures mean, median and mode.
- The fields which takes values as integers are converted from float to int and score columns are rounded to 2 decimals.
- A cleaned dataset is obtained by retaining all the columns.

### Phase 3
In phase 3 Exploratory Data Analysis is performed.
- Statistical measures are evaluated for observations.
- Univariate analysis is carried out on fields including age, notifications per day, various hours spent, addiction level and scores.
- Correlation analysis is carried out to establish various relationships among social media habits, lifestyle factors, distraction, focus, and productivity.
- Data visualisation is carried out appropriately.
- Final observations are noted.

### Phase 4
- Documentation of the project.
