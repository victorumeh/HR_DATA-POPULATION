# HR_DATA-POPULATION
Critical analysis on a data set for employees and population data of 2006 and 2019
# 📊 HR & Population Data Analysis Dashboard

> **Dual-Dashboard Power BI Project** — Comprehensive workforce analytics and Nigeria population insights for data-driven decision making.

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Data Analysis](https://img.shields.io/badge/Data%20Analysis-4285F4?style=for-the-badge&logo=google-analytics&logoColor=white)](https://github.com)
[![HR Analytics](https://img.shields.io/badge/HR%20Analytics-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://github.com)

---

## 🎯 Project Overview

This repository contains a **Power BI (.pbix) file** featuring **two integrated dashboards**:

1. **HR Workforce Dashboard** — Analytics on 1,470 employees across HR, R&D, and Sales departments
2. **Nigeria Population Dashboard** — Census data analysis covering 35 states (2006 vs. 2019)

Both dashboards are designed for **non-technical stakeholders** and provide actionable insights for leadership decision-making.

---

## 📁 Repository Contents

```
├── NEW_HR_DATASET_POWER_BI.pbix    # Main Power BI file with both dashboards
├── README.md                        # This file
├── screenshots/                     # Dashboard preview images
│   ├── hr_dashboard_page1.png
│   ├── hr_dashboard_page2.png
│   ├── hr_dashboard_page3.png
│   └── population_dashboard.png
└── Stakeholder_Report.docx          # Executive summary (plain-language)
```

---

## 🔍 Dashboard 1: HR Workforce Dashboard

### Key Metrics Tracked
- **Total Employees:** 1,470 active staff
- **Departments:** HR | R&D | Sales
- **Age Distribution:** Under 25 to Over 55 (5 age bands)
- **Attrition Tracking:** Yes/No classification
- **Overtime Status:** Yes/No monitoring

### Insights Delivered

#### 👥 Demographics
- **Age Profile:** Majority (554 employees) in the 25–34 age band
- **Gender Split:** Male and Female representation tracked
- **Marital Status:** Married (34%), Divorced (34%), Single (32%)

#### 💰 Compensation Analysis
- **Highest Earners:** Managers ($17K–$19K/month average)
- **Lowest Earners:** Sales Representatives ($2K–$3K/month average)
- **Education Field:** Life Sciences leads in hourly rate generation ($66.83K total)

#### 😊 Job Satisfaction
- **Most Satisfied Role:** Healthcare Representative (2.79/scale)
- **Least Satisfied Role:** Human Resources (2.56/scale)
- **Most Satisfied Department:** Sales
- **Least Satisfied Department:** HR ⚠️

#### 📈 Career Progression
- **Longest Without Promotion:** Managers (~5 years average)
- **Average Tenure:** 7+ years across all departments
- **Manager Relationship Duration:** Sales department leads (~4+ years)

#### ✈️ Travel Distribution
- **Non-Travel:** Largest category
- **Travel Rarely:** Second largest
- **Travel Frequently:** Smallest group

---



## 🗺️ Dashboard 2: Nigeria Population Dashboard

### Key Metrics Tracked
- **States Covered:** 35 out of 37 (including FCT)
- **Census Years:** 2006 and 2019 comparison
- **Population Growth:** +59M people over 13 years
- **Growth Rate:** ~43% increase

### Insights Delivered

#### 📍 Geographic Coverage
- **Northern States:** Kano, Kaduna, Katsina, Borno, Bauchi, Jigawa
- **Southern States:** Rivers, Lagos, Delta, Anambra, Oyo
- **Central/Middle Belt:** Benue, Niger, and surrounding areas

#### 🏙️ Top Populated States (2006 & 2019)
1. **Kano** — Largest population consistently
2. **Lagos** — Second largest, fast-growing commercial hub
3. **Kaduna** — Major northern state
4. **Katsina** — High population density
5. **Oyo** — Southwestern population center
6. **Rivers** — Key southern state


#### 📊 Population Growth Analysis
- **2006 Total:** 137 million
- **2019 Total:** 196 million
- **Absolute Growth:** +59 million people
- **Percentage Increase:** ~43% over 13 years

---

## 🎨 Dashboard Features

### Interactive Elements
- ✅ **Slicers/Filters:** Department, Age Range, Gender, Marital Status, Attrition, Overtime
- ✅ **Cross-Filtering:** Click any chart to filter related visuals
- ✅ **Drill-Through:** Navigate between dashboard pages seamlessly
- ✅ **Geographic Maps:** Interactive Nigeria state-level visualization
- ✅ **Tooltips:** Hover for detailed breakdowns

### Visualizations Used
- 📊 Bar Charts (Horizontal & Vertical)
- 📈 Line Charts (Trends)
- 🗺️ Map Visualization (Latitude/Longitude)
- 🔢 KPI Cards (Summary Metrics)
- 📉 Area Charts (Distributions)
- 🎯 Clustered Column Charts (Comparisons)

---

## 🚀 How to Use This Dashboard

### Prerequisites
- **Power BI Desktop** (Latest version recommended)
- Download from: [Microsoft Power BI](https://powerbi.microsoft.com/desktop/)

### Steps to Open
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/hr-population-analysis.git
   ```
2. Navigate to the project folder:
   ```bash
   cd hr-population-analysis
   ```
3. Open `NEW_HR_DATASET_POWER_BI.pbix` in Power BI Desktop

4. Explore the dashboards:
   - **HR_DATA page:** Workforce analytics
   - **DASHBOARD pages (1-3):** Detailed HR metrics
   - **POPULATION page:** Nigeria census data

### Recommended Navigation Flow
```
Start → HR_DATA (Overview) → DASHBOARD (Deep-dive) → POPULATION (Geographic insights)
```

---

## 📊 Key Findings & Recommendations

### 🔴 Critical Action Items

| Priority | Area | Recommendation |
|----------|------|----------------|
| **HIGH** | HR Department Satisfaction | Launch engagement survey — HR scores lowest (2.56) |
| **HIGH** | Manager Promotions | Review promotion pipeline — managers waiting ~5 years |
| **HIGH** | Attrition Risk | Cross-analyze low satisfaction + overtime for flight risk |
| **MEDIUM** | Compensation Equity | Address $16K pay gap between roles |
| **MEDIUM** | Succession Planning | Build leadership pipeline for young workforce (25–34 majority) |
| **MEDIUM** | Population Growth | Infrastructure review for 43% growth in 13 years |
| **LOW** | Travel Burnout | Monitor frequent travelers for workload balance |

---

## 📈 Data Sources

### HR Dataset
- **Records:** 1,470 employee entries
- **Fields:** 30+ attributes including demographics, compensation, satisfaction, tenure
- **Time Period:** Current workforce snapshot (as of 2026)
- **Departments:** HR, R&D, Sales

### Population Dataset
- **Records:** 35 state-level entries (x2 years)
- **Fields:** State name, population (2006), population (2019), latitude, longitude
- **Source:** Nigeria census and population estimates
- **Coverage:** Near-complete national dataset

---

## 🛠️ Technical Details

### Power BI Features Utilized
- **DAX Measures:** Custom calculations for averages, sums, percentages
- **Data Modeling:** Relationships between HR and reference tables
- **Conditional Formatting:** Color-coded metrics for quick insights
- **Bookmarks:** Saved views for common filter combinations
- **Custom Visuals:** Enhanced chart types for better storytelling

### Performance Optimization
- ✅ Efficient data model (star schema where applicable)
- ✅ Indexed columns for faster filtering
- ✅ Aggregated measures to reduce query load
- ✅ Optimized visuals for quick rendering

---

## 📄 Stakeholder Report

A **plain-language executive summary** is included as `Stakeholder_Report.docx`:
- No technical jargon
- Key findings highlighted
- Actionable recommendations table
- Suitable for C-suite and board presentations

---

## 🤝 Use Cases

### For HR Leaders
- Identify attrition risk factors
- Plan compensation reviews
- Track satisfaction trends
- Monitor promotion pipelines

### For Finance Teams
- Budget planning based on salary distributions
- Headcount forecasting
- Department cost analysis

### For Operations
- Travel policy optimization
- Workload distribution insights
- Tenure and retention metrics

### For Government/NGOs (Population Data)
- Infrastructure planning for high-density states
- Resource allocation based on population growth
- Regional development priorities

---


## 🔧 Customization Guide

### Adding New Data
1. Open Power BI Desktop
2. Go to **Home → Transform Data**
3. Update source tables or append new records
4. Click **Close & Apply**

### Modifying Visuals
1. Select any chart/visual
2. Use **Visualizations pane** to change type/formatting
3. Adjust **Fields** to change metrics displayed

### Creating New Pages
1. Click **+** icon at bottom of screen
2. Duplicate existing page for consistent styling
3. Add new visuals using drag-and-drop

---

## 📌 Important Notes

### Data Privacy
- ⚠️ This dashboard contains **confidential employee data**
- Do not share publicly without anonymization
- Follow GDPR/data protection guidelines

### Data Accuracy
- HR data reflects a specific snapshot period
- Population data is based on official census estimates
- Verify assumptions before making strategic decisions

### Update Frequency
- Recommended refresh: **Monthly** for HR data
- Population data: **Annual** updates when census is released

---


## 🚀 Future Enhancements

- [ ] Add predictive attrition modeling (ML integration)
- [ ] Include quarterly trend analysis for satisfaction scores
- [ ] Expand population dashboard to include GDP/economic indicators
- [ ] Add drill-through pages for individual employee profiles
- [ ] Implement row-level security for department-specific access

---

## 📞 Contact & Support

**Project** victorumeh2015@gmail.com  
**LinkedIn:** (https://linkedin.com/in/victorumeh)  

For issues or feature requests, please [open an issue](https://github.com/yourusername/hr-population-analysis/issues).


---

## 🙏 Acknowledgments

- Power BI community for visualization best practices
- Nigeria National Population Commission for census data
- HR team for providing anonymized workforce data

---

## ⭐ Star This Repository

If you find this dashboard useful, please consider giving it a ⭐ to help others discover it!

---

<div align="center">

**Built with ❤️ using Power BI**

[Report an Issue] (https://github.com/victorumeh/hr-population-analysis/issues) • [Request Feature](https://github.com/victorumeh/hr-population-analysis/pulls) • [View Demo](https://github.com/victormeh/hr-population-analysis)

</div>

