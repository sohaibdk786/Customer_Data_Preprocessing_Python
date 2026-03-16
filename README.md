# Customer Data Preprocessing and Analysis using Python

This project was completed as part of the **Programming for AI and Data Science** module during my **MSc Artificial Intelligence at the University of Hull**.

The aim of this project is to clean, process, and analyze a customer dataset using Python data science tools.

---

## Dataset

The dataset used in this project:

acw_user_data.csv

The dataset contains information such as:

- Customer age
- Salary
- Commute distance
- Employment status
- Credit card expiry
- Number of dependants

---

## Project Tasks

The project performs several data processing tasks:

### Data Loading
The dataset is loaded from a CSV file using Python.

### Data Cleaning
Data cleaning operations include:
- Removing extra spaces
- Converting data types
- Correcting inconsistent values

### Data Categorization
Customers are separated into different categories such as:
- Retired users
- Employed users
- Users with expired credit cards

### Feature Engineering
A new metric is created:

salary_commute = salary / commute_distance

This helps analyze the relationship between salary and commuting distance.

### Statistical Analysis
Basic statistics are calculated using Pandas:

- Mean Salary
- Median Age

### Data Visualization
Graphs are generated using:

- Matplotlib
- Seaborn

An age distribution histogram is also created.

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- JSON
- CSV

---

## Project Outputs

The project generates output files stored in:

acw_outputs/

Inside this folder:

- JSON files containing processed data
- PNG files containing visualization graphs

---

## Author

Sohaib Nasir  
MSc Artificial Intelligence  
University of Hull
