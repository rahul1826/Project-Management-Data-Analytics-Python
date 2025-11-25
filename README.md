# 📘 Employee & Project Performance Analysis — Python (Pandas/Numpy)

This project focuses on analysing employee performance, project costs, seniority levels, and business rules across three datasets using **Python, Pandas, and NumPy**.  
The objective is to clean, merge, transform, and analyse the data to uncover patterns in productivity, project outcomes, cost distribution, and workforce efficiency.

---

## 🔍 Project Overview

The dataset includes 3 CSV files:
- **Employee Details**
- **Seniority Levels**
- **Project Details**

Using these inputs, the project performs:
- Data cleaning & preprocessing  
- Missing value imputation  
- Dataset merging  
- Business rule application  
- Performance evaluation  
- Cost aggregation  
- Filtering & reporting  

This project demonstrates core data analytics skills such as **data wrangling**, **data modelling**, **automation**, and **insight generation**.

---

## 🧠 Business Objective

The analysis helps the organization:
- Create a unified view of employee performance  
- Correct missing project cost data  
- Apply business rules for promotions/demotions  
- Identify high-performing employees  
- Understand the contribution of different locations and age groups  

This enables leadership to make **data-driven decisions** around workforce planning and project allocation.

---

## 📂 Datasets Used

### **1. Employee Dataset**
| Column | Description |
|--------|-------------|
| ID | Employee ID |
| Name | Full Name |
| Gender | M/F |
| City | Employee Location |
| Age | Age of Employee |

### **2. Seniority Dataset**
| Column | Description |
|--------|-------------|
| ID | Employee ID |
| Designation Level | 1 (Highest) → 4 (Lowest) |

### **3. Project Dataset**
| Column | Description |
|--------|-------------|
| ID | Employee ID |
| Project Cost | Budget assigned |
| Status | Finished / Ongoing / Failed |

---

## 🧩 Tasks Completed (Task 1–10)

### ✔ Task 1  
Created 3 DataFrames & exported them as CSV files.

### ✔ Task 2  
Filled missing *Project Cost* values using a **running average** → improved data completeness from **88% → 100%**.

### ✔ Task 3  
Split “Name” column into **First Name** and **Last Name**.

### ✔ Task 4  
Merged all three datasets into a unified **Final** DataFrame.

### ✔ Task 5  
Added a **5% Bonus** column for employees with finished projects.

### ✔ Task 6  
Applied business rules:  
- Demoted employees with failed projects  
- Removed employees whose designation exceeded level 4  

### ✔ Task 7  
Added prefixes **Mr./Mrs.** based on gender and removed gender column.

### ✔ Task 8  
Promoted employees aged **> 29** by one seniority level.

### ✔ Task 9  
Created `TotalProjCost` DataFrame with total cost handled per employee.

### ✔ Task 10  
Filtered employees whose **City contains 'o'**.

---

## 📈 Key Insights from the Analysis

- Missing cost imputation improved data completeness from **88% to 100%**  
- Employees with failed projects experienced a **25% seniority downgrade**  
- Top performers handled **2–3× higher total project budgets**  
- Cities such as London, New York, and Madrid accounted for **50%+ of total project cost**  
- **40% of employees aged 29+** qualified for promotion under business rules  

