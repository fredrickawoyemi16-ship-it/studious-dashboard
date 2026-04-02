# 🎓 University Performance & Finance Analytics Dashboard

## 📌 Project Overview
This project is a multi-page **Power BI dashboard** designed to provide university administrators with a comprehensive, data-driven view of institutional performance.  

It integrates **student demographics, academic performance, and financial data** to support strategic decision-making, improve student outcomes, and enhance financial sustainability.

---

## 📊 Dashboard Preview


![Finance_Overview](/Images/Student%20PowerBI/Finance%20Overview.png)


---

## 🏗️ Data Architecture & Modeling

This project is built using a **Star Schema** data model to ensure efficient querying, scalability, and seamless filtering across multiple report pages.

### 🔷 Schema Design


![Data_Modelling](/Images/Student%20PowerBI/Data%20Modelling.png)


- **Fact Table:** `school_fact`  
  Stores quantitative metrics such as:
  - Scores  
  - Tuition Fees  
  - Pass/Fail Status  

- **Dimension Tables:**
  - `dim_student`
  - `dim_lecturer`
  - `dim_course`
  - `dim_date`

### 🔗 Key Relationships
- One-to-Many relationships between dimension tables and the fact table
- Enables **drill-through analysis** from high-level summaries to detailed records
- Optimized for performance and interactive filtering across report pages

---

## 📊 Dashboard Modules



![Finance_Overview](/Images/Student%20PowerBI/Finance%20Overview.png)

### 💰 Finance Overview
- Total Revenue: **142.55bn**
- Peak Revenue: **1.31bn (2023)**
- Payment Status Insight:
  - Only **33.38%** of students have fully paid tuition
- Identified top student segments contributing an average of **475K per student**

**Impact:**
- Highlights gaps in tuition collection
- Supports strategies for improving revenue collection

---

### 👨🎓 Student Demographics

![School_Overview](/Images/Student%20PowerBI/School%20Overview.png)



- Total Student Population: **300K**
- Gender Distribution:
  - Male: **50.09%**
  - Female: **49.91%**
- Average Age: **27.5 years**
- Geographic Distribution:
  - High concentrations in **Oyo, FCT, Rivers, and Lagos**

**Impact:**
- Supports targeted recruitment and resource allocation
- Helps design student-focused programs and services

---

### 📚 Academic Performance & Lecturer Excellence

#### Student Performance

![Academic_Overview](/Images/Student%20PowerBI/Academic%20Overview.png)


- Global Pass Rate: **74.74%**
- Average Score: **59.45**
- Identified departments maintaining strong academic standards:
  - Computer Science  
  - Law  

#### Lecturer Performance

![Lecturer_Overview](/Images/Student%20PowerBI/Lecturer%20Overview.png)


- Evaluated **99 lecturers**
- Ranked based on:
  - Student volume handled  
  - Pass rates achieved  
- Top performer example:
  - **Dr.Eze Okeke** with a **75.8% pass rate**

**Impact:**
- Identifies areas requiring academic intervention
- Supports lecturer performance evaluation and workload optimization

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Data visualization and dashboard development  
- **DAX (Data Analysis Expressions)** – Advanced calculations and dynamic measures  
- **Power Query** – Data cleaning, transformation, and ETL processes  
- **Microsoft Excel** – Data source and initial data preparation  
- **Star Schema Data Modeling** – Optimized relational data structure  

---

## 📐 Key Measures & Metrics

- Total Revenue  
- Average Score  
- Pass Rate (%)  
- Payment Completion Rate  
- Lecturer Performance Ranking  
- Student Distribution Metrics  

---

## 💡 Business Impact & Recommendations

- **Revenue Optimization:**
  - Convert pending payments into completed payments using automated reminders and improved billing strategies  

- **Resource Allocation:**
  - Increase staffing in high-demand departments such as Computer Science and Law  

- **Academic Improvement:**
  - Identify and support courses with high failure rates (e.g., Financial Accounting) through tutoring and curriculum review  

- **Strategic Decision-Making:**
  - Enable leadership to make informed, data-driven decisions using real-time insights  

---

## 💼 Skills Demonstrated

- Data Modeling (Star Schema)  
- Data Visualization (Power BI)  
- Business Intelligence  
- Data Cleaning & Transformation (Power Query)  
- Advanced DAX Calculations  
- Analytical & Problem-Solving Skills  

---

## 🧠 Conclusion

This dashboard transforms raw academic and financial data into actionable insights, empowering university administrators to:
- Improve student success rates  
- Optimize financial performance  
- Enhance operational efficiency  

---

## 📬 Contact

If you’d like to connect or collaborate:

- LinkedIn: *www.linkedin.com/in/fredrick-awoyemi-3ba76a3a2*  

---
