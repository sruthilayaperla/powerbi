# Dirty Employees – Power BI Data Cleaning & Analysis

## 📊 Project Overview

This project focuses on **cleaning, transforming, and analyzing employee data using Microsoft Power BI**.

The dataset contains employee information such as employee ID, name, email, gender, age, city, salary, and joining date. Since the original dataset contains data-quality issues, the main purpose of this case study is to identify and clean the problems before creating meaningful analysis and visualizations.

This project demonstrates a practical **data cleaning and Power BI reporting workflow**.

---

## 🎯 Objectives

The main objectives of this project are:

* Identify errors and inconsistencies in the employee dataset.
* Clean and transform the raw data.
* Handle missing or incorrect values.
* Standardize employee information.
* Prepare the dataset for analysis.
* Create useful Power BI visualizations.
* Generate insights about employees, salaries, locations, demographics, and joining dates.

---

## 📁 Project Files

The project contains the following files:

| File                      | Description                                                    |
| ------------------------- | -------------------------------------------------------------- |
| `dirty_employee_data.csv` | Raw employee dataset containing data-quality issues            |
| `Dirty employees.pbix`    | Power BI report containing the cleaned data model and analysis |

The files are available in this GitHub case-study folder.

---

## 🗃️ Dataset

The employee dataset contains the following columns:

| Column         | Description                                    |
| -------------- | ---------------------------------------------- |
| `Employee_ID`  | Unique identifier for an employee              |
| `Name`         | Employee name                                  |
| `Email`        | Employee email address                         |
| `Gender`       | Employee gender                                |
| `Age`          | Employee age                                   |
| `City`         | Employee's city                                |
| `Salary`       | Employee salary                                |
| `Joining_Date` | Date when the employee joined the organization |

The raw CSV contains 21 lines and is approximately 1.46 KB in size.

---

## 🧹 Data Cleaning

The dataset is intentionally treated as a **dirty dataset**, so data preparation is an important part of this project.

The cleaning process includes:

1. Importing the raw CSV file into Power BI.
2. Checking the structure and data types of each column.
3. Identifying missing and inconsistent values.
4. Removing or correcting invalid records where required.
5. Standardizing text values.
6. Checking employee IDs for consistency.
7. Validating email values.
8. Checking age and salary fields for incorrect values.
9. Converting `Joining_Date` into the correct date format.
10. Ensuring the final dataset is suitable for analysis.

Power Query in Power BI can be used to perform these transformation and cleaning operations.

---

## 📈 Analysis

After cleaning the data, the employee information can be analyzed from different perspectives.

### Employee Demographics

Analysis can include:

* Total number of employees
* Employees by gender
* Employees by age
* Age distribution
* Employees by city

### Salary Analysis

Salary-related analysis can include:

* Total salary
* Average salary
* Minimum salary
* Maximum salary
* Salary distribution
* Salary comparison across cities or employee groups

### Employee Joining Analysis

The `Joining_Date` column can be used to analyze:

* Employees joining over time
* Hiring trends
* Employees joining by year/month
* Distribution of employee joining dates

---

## 📊 Power BI Dashboard

The Power BI report can be used to present the cleaned employee data through interactive visuals.

Possible dashboard elements include:

* KPI cards
* Employee count
* Average salary
* Gender distribution
* Employee distribution by city
* Salary analysis
* Age distribution
* Joining-date trends
* Interactive slicers and filters

The included `.pbix` file is the Power BI report for this case study.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **CSV**
* **Data Cleaning & Transformation**
* **Data Visualization**

---

## 🔄 Project Workflow

```text
Raw Employee Data
        ↓
Import into Power BI
        ↓
Data Quality Check
        ↓
Clean & Transform Data
        ↓
Create Data Model
        ↓
Create Measures / Calculations
        ↓
Build Visualizations
        ↓
Interactive Power BI Report
        ↓
Business Insights
```

---

## 💡 Key Learnings

Through this project, the following concepts are practiced:

* Working with messy real-world-style data
* Data cleaning using Power Query
* Handling inconsistent data
* Data type conversion
* Creating calculated measures using DAX
* Building interactive Power BI dashboards
* Turning raw data into meaningful information
* Presenting data in a clear and understandable way

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open `dirty_employee_data.csv` to inspect the raw dataset.
3. Open `Dirty employees.pbix` using Microsoft Power BI Desktop.
4. Review the Power Query transformations.
5. Explore the data model and calculations.
6. Interact with the dashboard and visuals.

---

## 📌 Conclusion

The **Dirty Employees** case study demonstrates how raw and inconsistent employee data can be transformed into a structured dataset suitable for analysis.

The project covers the complete basic workflow of a Power BI data-analysis project:

**Data Cleaning → Transformation → Modeling → Visualization → Insights**

It is a useful practice project for learning how Power BI can be used to prepare and analyze employee data and create interactive business reports.

---

## 👤 Author

**Sruthilayaperla**

GitHub Repository:
https://github.com/sruthilayaperla/powerbi
