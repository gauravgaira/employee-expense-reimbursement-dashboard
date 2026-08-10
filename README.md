# Employee Expense & Reimbursement Analytics Dashboard

## 📊 Power BI | SQL Server | DAX | Power Query

An interactive Power BI dashboard developed to analyze employee expenses, reimbursement status, approval performance, expense trends, and employee-level spending.

The dashboard connects to SQL Server and transforms transactional expense data into interactive KPI reports for management and operational analysis.

---

## 🚀 Project Overview

The Employee Expense & Reimbursement Analytics Dashboard provides a centralized view of organizational expense data.

The dashboard helps users monitor:

- Total Expenses
- Approved Amount
- Rejected Amount
- Pending Amount
- Expense by Expense Type
- Monthly Expense Trends
- Employee-wise Expenses
- Employee-wise Approved Amount
- Employee-wise Pending Amount
- Expense Status
- Reimbursement Performance
- Expense Patterns

The report includes interactive filters and drill-down functionality for detailed employee and expense analysis.

---

## 🎯 Business Objective

The objective of this project is to provide management with a centralized and interactive reporting solution for monitoring employee expenses and reimbursement activities.

The dashboard helps identify:

- High expense categories
- Employees with higher spending
- Pending reimbursements
- Rejected expense amounts
- Monthly expense trends
- Approval patterns
- Expense distribution by type
- Overall reimbursement performance

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Power BI | Dashboard development and visualization |
| SQL Server | Data source and data extraction |
| DAX | KPI and business metric calculations |
| Power Query | Data transformation and cleaning |
| SQL | Data querying and analysis |
| Data Modeling | Relationships and analytical model |
| GitHub | Project version control and documentation |

---

## 📌 Key KPIs

The dashboard provides the following key performance indicators:

- Total Expense
- Approved Amount
- Rejected Amount
- Pending Amount
- Total Claims
- Total Employees
- Average Claim Amount
- Expense per Employee
- Approved Expense
- Rejected Expense
- Pending Expense

---

## 📈 Dashboard Features

### 1. Expense Overview

The main dashboard provides an overview of organizational expenses through KPI cards and interactive visualizations.

Key metrics include:

- Total Expense
- Approved Amount
- Rejected Amount
- Pending Amount

---

### 2. Expense Type Analysis

The dashboard analyzes expenses by different expense categories such as:

- Local Conveyance
- Tour Expense
- Other Expense
- Office Expense

This helps identify which categories contribute most to total expenses.

---

### 3. Monthly Expense Analysis

A monthly trend visualization is used to analyze approved expenses over time.

Users can identify:

- Monthly spending patterns
- High-expense months
- Low-expense months
- Changes in reimbursement activity

---

### 4. Employee-wise Expense Analysis

The employee analysis section provides detailed information about individual employees.

Metrics include:

- Total Expense
- Approved Amount
- Pending Amount

This enables detailed employee-level expense monitoring.

---

### 5. Expense Status Analysis

Expenses are categorized based on their current status:

- Approved
- Rejected
- In Progress

This provides visibility into reimbursement processing and pending claims.

---

## 🔎 Interactive Filters

The dashboard includes interactive filters for:

- Year
- Expense Type
- Status
- Employee Name
- Date Range

Users can dynamically filter the report to perform detailed analysis.

---

## 🗂️ Data Model

The Power BI model contains transactional and supporting tables.

### Main Tables

#### ExpenseSubmission

Contains expense transaction information such as:

- expenseId
- employeeId
- amount
- expenseType
- expenseTypeId
- expenseDate
- startDate
- endDate
- status
- remarks
- createdAt
- Org

#### EMP DATA

Employee-related information.

#### Calendar

Date dimension used for:

- Year analysis
- Month analysis
- Date filtering
- Time-series analysis

---

## 🧮 DAX & Measures

Key calculated measures include:

- Total Expense
- Approved Amount
- Rejected Amount
- Pending Amount
- Total Claims
- Total Employees
- Average Claim Amount
- Expense per Employee

Example:

```DAX
Total Expense =
SUM(ExpenseSubmission[amount])
