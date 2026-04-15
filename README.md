# VistaRetail Myanmar: Quarterly Sales Dashboard (2019)

## Overview
This project is a two-part Excel dashboard built to analyze Q1 2019 sales data for a fictional retail company.

The goal was simple: take a messy transactional dataset and turn it into something interactive that can answer basic business questions — what’s selling, where revenue is coming from, and how performance is changing over time.

---

## The Problem
The dataset wasn’t ready for analysis:

- Transaction dates were inconsistent (Excel mixed up days and months)
- No clear structure for analysis (everything was raw rows)
- No easy way to compare performance across categories, locations, or time

---

## What I Did

### 1. Data Cleaning
- Fixed broken date formats using **Text-to-Columns**
- Rebuilt a reliable timeline for accurate analysis

### 2. Data Structuring
- Created useful groupings:
  - Price categories (Expensive vs Less Expensive)
  - Age groups
  - Other analysis dimensions  
- Optimized the dataset for **Pivot Tables**

### 3. Dashboard Development

#### Dashboard 1 — Distribution & Segments
Focus: *Where revenue is coming from*
- Product categories  
- Locations  
- Age groups  
- Payment methods  

#### Dashboard 2 — Trends & Growth
Focus: *How performance changes over time*
- Month-over-Month (MoM)  
- Week-over-Week (WoW)  
- Daily trends  

---

## Key Features

- **Slicers** for interactive filtering (location, product line, age group)  
- **Toggle buttons** to switch between:
  - Actual values  
  - Percentages  
  - % change  
- **Lollipop chart** for daily revenue ranking  
- **Sparklines** for quick trend visibility  
- **Dynamic captions** powered by formulas (auto-update with data)  
- **ISO week logic ("Thursday rule")** for accurate weekly comparisons across months  

---

## What I Learned

- Data cleaning is often the hardest and most important step  
- Structuring data properly simplifies analysis  
- Small details (like correct week logic) can significantly affect insights  
- Excel can go far beyond basic charts when used properly  

---

## Files

- `VistaRetail_Dashboard.xlsm` — Main Excel dashboard file  

### Screenshots
- `dashboard_1.png` — Distribution & Segments view  
- `dashboard_2.png` — Trends & Growth view  
- `formulas_view.png` — Example of dynamic formulas (INDEX/MATCH, captions)  
- `data_transformation.png` — Data cleaning and structuring process  

---

## Preview

