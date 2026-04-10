<div align="center">

[![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)]()
[![DataCamp](https://img.shields.io/badge/DataCamp-DataLab-03EF62?style=for-the-badge&logo=datacamp&logoColor=white)]()
[![Status](https://img.shields.io/badge/Status-Completed-A855F7?style=for-the-badge)]()

</div>

---

## 📌 Project Overview

This project performs a comprehensive **Diversity, Equity & Inclusion (DEI) analysis** on a workforce dataset of **10,000 employees** across 7 divisions using SQL. The analysis is structured across 4 phases, progressing from basic exploration to advanced window functions and composite DEI scoring.

> 🎯 **Goal:** Identify underrepresented groups, measure DEI sentiment, and surface actionable insights for HR leadership.

---

## 📂 Dataset

| Detail | Info |
|--------|------|
| Total Employees | 10,000 |
| Divisions | IT, Sales, Finance, Marketing, Operations, HR, R&D |
| Locations | Dubai, Abu Dhabi, Riyadh, Doha |
| Key Variables | Gender, Ethnicity, Disability, LGBTQ+, Veteran, Minority, Age, Nationality, DEI Scores |

---

## 🔍 Project Structure

### Phase 1 — Data Exploration
- Preview dataset & check structure
- Total employee count by division
- Gender, ethnicity & LGBTQ+ breakdowns
- Disability, veteran & minority counts
- Average age by division

### Phase 2 — Group-Level Analysis
- Gender & ethnicity breakdown per division
- Age group distribution using `CASE WHEN`
- Disability & LGBTQ+ representation per division
- Unique nationalities per division
- Divisions with underrepresented employees

### Phase 3 — Data Joining & DEI Scoring
- Merged employee table with division metadata (location, DEI budget, remote policy)
- Average diversity, equity & inclusion scores by gender, ethnicity & division
- Negative sentiment analysis by ethnicity and gender
- DEI budget vs inclusion score comparison
- Remote policy vs diversity sentiment

### Phase 4 — Advanced SQL
**Part A — CASE & Subqueries**
- Composite DEI sentiment labels per employee
- Divisions below average minority representation
- Most at-risk demographic group
- DEI sentiment breakdown by ethnicity

**Part B — CTEs (Common Table Expressions)**
- Composite DEI score per division
- Most at-risk demographic identification
- Gender sentiment comparison
- Underrepresented vs general workforce sentiment

**Part C — Window Functions**
- Ranked divisions by composite DEI score
- Running totals of underrepresented employees
- Ethnicity ranking by inclusion score within each division
- Division DEI score vs company average

---

## 🏆 7 Key D&I Findings

| # | Finding | Result |
|---|---------|--------|
| 1 | Most ethnically diverse division | **IT** (7 unique ethnicities) |
| 2 | Gender that feels least included | **Transgender** (avg score: 0.85) |
| 3 | Ethnicity with lowest equity score | **Other** (avg score: 1.63) |
| 4 | Division with lowest DEI composite | **Operations** (score: 4.37) |
| 5 | Do underrepresented employees feel less included? | **Yes** (1.52 vs 1.65) |
| 6 | Age group with most negative diversity sentiment | **30–45** (score: 1.13) |
| 7 | Overall company DEI health | Diversity: 1.1 · Equity: 1.83 · Inclusion: 1.6 · **Total: 4.53** |

---

## 🛠️ SQL Concepts Used

`SELECT` · `WHERE` · `GROUP BY` · `ORDER BY` · `JOIN` · `CASE WHEN` · `SUBQUERIES` · `CTEs` · `Window Functions` · `RANK()` · `SUM() OVER` · `AVG()` · `COUNT()` · `HAVING`

---

## 💡 Key Insights

- **IT division** is the most diverse by ethnicity but still ranks 4th in DEI composite score
- **Transgender employees** report the lowest inclusion sentiment — a key area for HR intervention
- **Remote policy** correlates with slightly higher diversity scores (2.67) vs on-site (2.65)
- **RD division** leads in composite DEI score (4.95) despite being the smallest division
- Underrepresented employees consistently report lower inclusion and equity scores than the general workforce

---

## 👩‍💻 Author

**Samruddhi Pathak**
MSc Business Analytics · Aston University, Birmingham

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/samruddhi-pathak-0412s)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github)](https://github.com/samruddhispathak)

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer&animation=twinkling" width="100%"/>
</div>
