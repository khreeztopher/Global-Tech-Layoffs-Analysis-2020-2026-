# 📊 Global Tech Layoffs Analysis (2020–2026)

## 📌 Overview

This project analyzes global tech layoffs to uncover trends across companies, industries, regions, and funding stages. The focus is on both **volume (total layoffs)** and **intensity (layoff rates)** to better understand workforce impact.

---

## 🎯 Objectives

* Identify companies with the highest layoffs
* Analyse industry impact
* Detect peak periods and shock events
* Compare layoffs across startup stages and company sizes
* Evaluate the relationship between funding and layoffs
* Measure workforce impact using layoff and survival rates

---

## 🛠️ Tools Used

* SQL (Microsoft SQL Server)
* Power BI (Data Visualisation & Dashboarding)

---

## 🗂️ Dataset Features

* Company information (name, industry, stage)
* Geographic data (country, continent)
* Layoff metrics (number laid off, dates)
* Funding and company size data

---

## 🔍 Analysis Breakdown

### Company Analysis

* Top companies by total layoffs
* Layoff rate across companies

### Industry Analysis

* Total layoffs by industry
* Layoff intensity (rate) by industry

### Geographic Analysis

* Layoffs by country and continent

### Time Series Analysis

* Yearly and monthly trends
* Shock event detection using month-over-month changes

### Business Structure Analysis

* Layoffs by company stage
* Layoffs by company size

### Funding Analysis

* Layoffs by funding level
* Relationship between funding and layoff rate

### Impact Analysis

* Survival rate of companies after layoffs

---

## 📊 Dashboard Features

* KPI cards (Total Layoffs, Layoff Rate, Company Count)
* Time-series visualization of layoffs
* Industry and company comparisons
* Funding vs Layoff Rate scatter plot
* Survival analysis
* Yearly interactive filter

---

## 📈 Key Insights

* Layoffs peaked during major global disruptions (2020 and 2022–2023)
* Some industries experienced both high volume and high severity of layoffs
* Highly funded companies were not immune to layoffs
* Late-stage companies contributed significantly to total layoffs
* Layoff rates provided deeper insight into workforce impact than totals alone

---

## 📁 Project Structure

```
Tech-Layoffs-Analysis/
│
├── data/
│   └── layoffs.csv
│
├── sql/
│   ├── data_cleaning.sql
│   ├── analysis_queries.sql
│   └── views.sql
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
└── README.md
```

---

## 🚀 How to Use

1. Run SQL scripts to clean and transform the data
2. Use the created views for analysis
3. Open the Power BI dashboard file to explore insights

---

## 💡 Conclusion

This project demonstrates a full analytics workflow:

* Data cleaning and transformation
* SQL-based analysis
* Data modeling using views
* Interactive dashboard development
---

