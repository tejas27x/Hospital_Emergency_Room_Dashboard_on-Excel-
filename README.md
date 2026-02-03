# 🏥 Hospital Emergency Room Dashboard (Excel)

An interactive **Hospital Emergency Room Analysis Dashboard** built using **Microsoft Excel** to monitor patient flow, wait times, admissions, referrals, and satisfaction metrics.  
This project helps healthcare stakeholders make **data-driven decisions** to improve emergency room efficiency and patient experience.

---
## 📷 Dashboard Preview

![Hospital Emergency Room Dashboard](imagesdashboard.png)

---
## 📊 Project Overview

The dashboard provides a **monthly performance report** of the hospital emergency room with dynamic filtering by **year and month**.  
It visualizes key operational KPIs to identify bottlenecks, trends, and improvement areas.

---

## 🎯 Project Objective

- Analyze emergency room performance
- Monitor patient admission patterns
- Reduce average wait time
- Improve patient satisfaction
- Track department referrals and demographics

---

## 🔑 Key KPIs

- **Total Patients**
- **Average Wait Time**
- **Patient Satisfaction Score**
- **Admission vs Not Admitted**
- **On-Time vs Delayed Attendance**
- **Gender-wise Distribution**
- **Age Group Analysis**
- **Department Referral Analysis**

---

## 📈 Dashboard Visuals

- KPI Cards for quick insights
- Age group bar chart
- Department referral horizontal bar chart
- Admission status table
- Patient attend status (On-time vs Delay)
- Gender-wise donut chart
- Monthly & yearly slicers

---

## 🛠 Tools & Technologies Used

- Microsoft Excel
- Pivot Tables & Pivot Charts
- Slicers (Month & Year)
- Excel Formulas
- Dashboard Design & Data Modeling

---

## 🧮 Key Formulas Used

### Age Group Categorization
```excel
=IF([Patient Age]>=70,"70-79",
IF([Patient Age]>=60,"60-69",
IF([Patient Age]>=45,"45-59",
IF([Patient Age]>=30,"30-44",
IF([Patient Age]>=15,"15-29",
IF([Patient Age]>=5,"05-14","0-4"))))))
