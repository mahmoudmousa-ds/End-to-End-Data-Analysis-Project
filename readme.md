# 📊 End-to-End Project - Data Analysis & Power BI Dashboard Development
![imgae](img.png)
## 🚀 Overview

This project involves end-to-end data handling, from data scraping and organization to building an interactive dashboard using Power BI. The goal is to manage workforce data, assess financial risks, and monitor project health effectively.

## 🔧 Tools & Technologies Used

- **Excel**: Used to organize and clean the scraped data.
- **Microsoft SQL Server**: Data was imported for better management and structure.
- **CTEs (Common Table Expressions)**: Used to simplify complex queries, making them easier to read and maintain..
- **Power BI**: Used for building the final interactive dashboard that tracks project and employee performance.

## 🧱 Project Workflow

1. **Data Collection & Organization**:
    - Scraped data was organized in Excel for easy access and cleaning.
    - The Excel sheets were then imported into **Microsoft SQL Server** to centralize and structure the data.

2. **Security via CTEs**:
    - Built **queries using CTEs** to ensure that sensitive data is accessible only by authorized personnel.
    - This step guarantees that the data analyst can only view the necessary parts of the data.

3. **Data Analysis**:
    - Data was handed over to the **Data Analyst** to analyze using the Power BI dashboard.
    - The dashboard focuses on key metrics such as employee performance, department goals, budget analysis, and project health.

4. **Power BI Dashboard**:
    - A comprehensive Power BI dashboard was developed to display the data.
    - The dashboard allows users to filter and drill down on department-wise data, project status, salary distributions, and more.

## 🎯 Key Use Cases Addressed

- **Risk Management**: Flagging over-budget departments and underperforming projects for corrective action.
- **Budget Management**: Assessing if annual budgets are sufficient to cover expenses based on department goals and project costs.
- **Workforce Management**: Tracking employee performance, salary distribution, and department-wise allocation.

## 🔍 Key Questions Answered

- **Which departments are over budget?**
- **Which projects are underperforming or need attention?**
- **How are employee performances tracked across different departments?**

## 📊 Dashboard Features

- **Project Budget Distribution**: Visualizes total budget per project and per department.
- **Department Goals**: Provides insights on department-wise budget allocation and performance.
- **Employee Data**: Displays employee details, including salary, performance, and department allocation.

## 🛠️ How to Run

1. **Set up the SQL Server** and import data into the respective tables as per the schema provided.
2. **Load Data into Power BI** using the SQL queries provided.
3. **Explore Visual Insights** through filters such as project status, department, or salary.
