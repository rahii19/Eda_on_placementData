# 🎓 Student Placement Performance – Exploratory Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on a student placement dataset to identify the key factors that influence **placement outcomes** and **salary packages**.

---

## 📊 Dataset Overview

- **Total Students:** 5,000  
- **Features:** 18  
- **Data Quality:**  
  - No missing values  
  - No duplicate records  

The dataset includes academic performance, skills, internships, backlogs, and placement status.

---

## 🎯 Objective

- Analyze **what factors affect student placement**
- Compare **placed vs non-placed students**
- Understand **salary patterns** among placed students
- Provide **actionable insights** for students and institutions

---

## 🔍 Key Findings

### 📌 Placement Statistics
- **Placement Rate:** 17.32% (866 students placed)
- **Average Salary:** 9.21 LPA  
- **Salary Range:** 3.01 – 14.99 LPA
- **Gender Distribution:** Almost equal (Male ~50%, Female ~50%)

---

### ✅ Factors That Strongly Impact Placement

1. **CGPA (Most Important)**
   - Placed: **8.43**
   - Not Placed: **7.52**

2. **Technical Skills**
   - Placed: **78.91**
   - Not Placed: **67.71**

3. **Backlogs (Negative Impact)**
   - Placed students have **~64% fewer backlogs**

4. **Soft Skills**
   - Higher scores increase placement chances

---

### ❌ Factors With Low Impact

- Internships
- Work experience
- Certifications
- Entrance exam scores
- Gender

These showed **very weak or no correlation** with placement.

---

## 💰 Salary Insights

- Academic and skill metrics show **weak correlation with salary**
- Salary is likely influenced by:
  - Company type
  - Job role
  - Industry
  - Location
  - Negotiation skills

> **Insight:** Getting placed depends on skills and CGPA, but salary depends on external factors.

---

## 📈 Correlation Summary

| Feature | Correlation with Placement |
|------|----------------------------|
| CGPA | 0.279 |
| Technical Skills | 0.247 |
| Soft Skills | 0.198 |
| Internships | 0.011 |
| Certifications | 0.008 |
| Entrance Exam | 0.001 |

---

## 📊 Visualizations

  - Distributions
  - Comparisons (Placed vs Not Placed)
  - Correlation heatmaps
  - Salary analysis

All plots are clean, labeled, and presentation-ready.

---

## 🛠 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ✅ Conclusion

**Placement success depends mainly on:**

> **CGPA + Technical Skills + Low Backlogs**

Other factors add value but have limited impact on final placement outcomes.

---

📌 *This project is ideal for showcasing EDA, data cleaning, visualization, and insight generation skills.*


