
# Optimizing IT Support Team

## Project Overview

This project focuses on analyzing IT support ticket data to improve the efficiency and performance of an IT support team. By examining support requests, response times, issue types, and customer satisfaction, the project aims to identify patterns and suggest strategies to optimize resource allocation and reduce resolution time.

The dataset contains support ticket records including ticket ID, issue type, priority, department, assigned team, resolution time, and customer satisfaction scores.

---

## Objectives

* Analyze IT support ticket data to understand common issues.
* Identify factors affecting ticket resolution time.
* Evaluate team workload distribution.
* Improve customer satisfaction by optimizing support processes.
* Provide data-driven insights for better IT support management.

---

## Dataset

The dataset used in this project contains the following fields:

| Column Name           | Description                                 |
| --------------------- | ------------------------------------------- |
| Ticket_ID             | Unique identifier for each support ticket   |
| Date                  | Date when the ticket was raised             |
| Time                  | Time when the ticket was reported           |
| Issue_Type            | Type of IT issue reported                   |
| Priority              | Priority level (Low, Medium, High)          |
| Department            | Department requesting support               |
| Assigned_Team         | IT team responsible for resolving the issue |
| Resolution_Time_Hours | Time taken to resolve the issue             |
| Status                | Ticket status                               |
| Customer_Satisfaction | User rating after issue resolution          |

---

## Project Workflow

### 1. Data Collection

Raw IT support ticket data was collected and stored in Excel format.

### 2. Data Cleaning

The raw dataset contained:

* Missing values
* Inconsistent text formatting
* Duplicate ticket IDs
* Mixed date formats

These issues were corrected using data cleaning techniques.

### 3. Exploratory Data Analysis (EDA)

EDA was performed to identify:

* Most frequent IT issues
* Average resolution time
* Priority distribution
* Team workload
* Customer satisfaction trends

### 4. Insights and Optimization

Based on the analysis, strategies were proposed to:

* Improve ticket response time
* Balance workload across support teams
* Reduce recurring issues
* Improve user satisfaction

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Microsoft Excel

---

## Key Analysis Performed

* Ticket distribution by issue type
* Average resolution time by team
* Priority vs resolution time analysis
* Department-wise issue frequency
* Customer satisfaction analysis

---
## Results

The analysis helped identify:

* Frequently occurring IT issues
* Departments generating the most support tickets
* Average resolution time for different teams
* Key areas where support efficiency can be improved

---

## Future Improvements

* Implement machine learning models to predict ticket resolution time.
* Build an automated ticket classification system.
* Develop a real-time dashboard for IT support monitoring.

---

---
