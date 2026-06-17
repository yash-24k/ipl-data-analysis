# IPL Complete Analysis (2008–2024)
### Excel-Based Cricket Data Analytics Project | Yash V. Kulkarni

---

## Overview

A complete end-to-end data analysis project covering **17 seasons of IPL** (2008–2024), built using **1,095 match records** and **260,921 ball-by-ball delivery records**. The project demonstrates the full data analyst workflow — data cleaning, custom calculated fields, pivot table analysis, dashboard design, and business storytelling — entirely in Microsoft Excel.

---

## Tools & Skills Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning, analysis, visualization |
| Pivot Tables | Multi-dimensional data aggregation |
| Excel Charts | Bar, Column, Pie, and Line charts |
| Dashboard Design | Dark-themed KPI dashboard |
| GitHub | Version control and project hosting |

---

## Project Structure

```
ipl-data-analysis/
│
├── IPL_analysis.xlsx
│   ├── Matches Raw      → 1,095 cleaned match records + 2 custom columns
│   ├── Deliveries Raw   → 260,921 cleaned ball-by-ball records + Ball Type column
│   ├── Analysis Sheet   → 6 Pivot Tables
│   ├── Dashboard        → 4 KPI cards + 6 charts (dark theme)
│   └── Insights         → 7 business insights with impact ratings
│
└── README.md
```

---

## What Was Done

### 1. Data Cleaning
- Removed duplicate match records based on match ID
- Handled missing city values, standardized to "Unknown"
- Formatted date fields for consistency
- Added custom calculated column **Win Type** (Batting First Won / Bowling First Won)
- Added custom calculated column **Close Match** (margin under 10 runs or 3 wickets)
- Added custom calculated column **Ball Type** (Dot Ball / Four / Six / Other) across 260,921 deliveries

### 2. Analysis — 6 Pivot Tables
| # | Analysis | Key Finding |
|---|---|---|
| 1 | Team Win Records | Mumbai Indians lead with 144 wins |
| 2 | Toss Decision Impact | Fielding first wins 64% of matches |
| 3 | Top 10 Venues | Eden Gardens hosted 77 matches |
| 4 | Orange Cap Race | Virat Kohli leads with 8,014 runs |
| 5 | Purple Cap Race | Yuzvendra Chahal leads with 213 wickets |
| 6 | Matches per Season | Tracks IPL growth from 2008–2024 |

### 3. Dashboard
A single-page, dark-themed professional dashboard featuring:
- 4 KPI cards — Total Matches, Top Team, Total Seasons, Close Matches
- Horizontal bar chart — Team Wins
- 3D pie chart — Toss Impact on Winning
- Column chart — Purple Cap Race (Top Wicket Takers)
- Bar chart — Top 10 Venues
- Column chart — Orange Cap Race (Top Run Scorers)
- Line chart — IPL Growth Over the Years

### 4. Business Insights
Derived 7 actionable insights with Critical / High / Medium / Action impact ratings.

---

## Key Findings

- **Mumbai Indians** are the most successful IPL franchise with **144 wins**, 6 ahead of Chennai Super Kings
- **Fielding first after winning the toss** results in a win 64% of the time — a statistically smarter strategy
- **Virat Kohli** is the all-time leading run scorer with **8,014 runs**, well ahead of Shikhar Dhawan (6,769)
- **Yuzvendra Chahal** tops the wicket-taking charts with **213 wickets**
- **Eden Gardens** is the most-used IPL venue, hosting 77 matches
- **118 matches (10.7%)** were decided by close margins, reflecting IPL's reputation for thrilling finishes

---

## Business Recommendation

> Franchises should prioritize bowling-first strategies after winning the toss, given the clear statistical advantage. Investment in venues with strong home-team advantage records, such as Eden Gardens and Wankhede Stadium, may further strengthen fan engagement and team performance.

---

## Dataset

- **Source:** IPL Complete Dataset (2008–2024) — [Kaggle](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)
- **Files used:** matches.csv (1,095 rows), deliveries.csv (260,921 rows)
- **Seasons covered:** 2008–2024

---

## About Me

**Yash V. Kulkarni** — BCA Graduate | Aspiring Data Analyst  
Skills: SQL · Excel · Data Analysis · Windows Server · AWS Basics  
📧 yashk9119@gmail.com  
🔗 www.linkedin.com/in/yash-kulkarni-30459130b · (https://github.com/yash-24k?tab=overview&from=2025-12-01&to=2025-12-31)

---

*This project was built as part of my data analyst portfolio to demonstrate hands-on skills in large-scale data cleaning, multi-table analysis, and dashboard storytelling.*
