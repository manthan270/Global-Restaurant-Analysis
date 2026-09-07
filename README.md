<div align="center">

# Zomato Global Restaurant Analysis

### End-to-End Data Analysis | Market Intelligence | Business Strategy

[![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![PowerPoint](https://img.shields.io/badge/PowerPoint-B7472A?style=for-the-badge&logo=microsoftpowerpoint&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/powerpoint)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/manthan270/Global-Restaurant-Analysis)

![Dataset](https://img.shields.io/badge/Dataset-9%2C551%20Restaurants-red?style=flat-square)
![Countries](https://img.shields.io/badge/Countries-15-orange?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

</div>

---

## Executive Summary

A business intelligence analysis of **9,551 restaurant records** across **15 countries**, built to support Zomato's strategic decisions on market expansion, service mix, and cuisine positioning.

The analysis pipeline covered end-to-end data operations: raw data ingestion, quality cleaning, statistical analysis via Excel formulas and Pivot Tables, and final delivery as an **interactive slicer-driven dashboard** alongside a stakeholder presentation deck.

> **Core Objective:** Turn raw restaurant data into clear numbers that help Zomato leadership decide where to expand, what services to push, and which price tier to back.


---

## Dashboard Preview

![Dashboard Preview](dashboard/dashboard_preview.png)

> *Interactive Excel dashboard featuring KPI cards, regional breakdowns, cuisine distribution, service availability analysis, and year-over-year restaurant growth timelines.*

---

## Table of Contents

- [Executive Summary](#executive-summary)
- [Dashboard Preview](#dashboard-preview)
- [Dataset Overview](#dataset-overview)
- [Business Questions Addressed](#business-questions-addressed)
- [Tools and Technical Skills](#tools-and-technical-skills)
- [Key Findings and Strategic Recommendations](#key-findings-and-strategic-recommendations)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Author](#author)

---

## Dataset Overview

| Attribute | Detail |
|---|---|
| **Total Records** | 9,551 restaurants |
| **Geographic Coverage** | 15 countries |
| **Average Rating** | 2.89 / 5.00 |
| **Average Cost for Two** | ₹839 |
| **Total Customer Votes** | 1,498,645 |
| **Key Variables** | Ratings, Votes, Pricing Tiers, Cuisine Types, Table Booking, Online Delivery, Opening Dates |

---

## Business Questions Addressed

1. Which countries and cities present the highest opportunity for new restaurant expansion?
2. Do value-added services (table booking, online delivery) measurably improve customer ratings?
3. Which cuisine categories consistently outperform across markets?
4. What pricing tier delivers the optimal balance of customer satisfaction and market competition?
5. How does market saturation in India affect average quality perception?

---

## Tools and Technical Skills

| Tool | What Was Done |
|---|---|
| ![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=flat&logo=microsoftexcel&logoColor=white) **Microsoft Excel** | Cleaned 9,551 records across 3 sheets, built 7 Pivot Tables, and designed a slicer-driven dashboard with Country and Year filters. Used COUNTIFS, SUMPRODUCT, and VLOOKUP across 15 countries and 4 price tiers to answer 15 business questions. |
| ![Word](https://img.shields.io/badge/Microsoft%20Word-2B579A?style=flat&logo=microsoftword&logoColor=white) **Microsoft Word** | Documented full methodology and written responses to 15 business questions — covering market expansion, service feature impact, cuisine performance, pricing strategy, and India market saturation. |
| ![PowerPoint](https://img.shields.io/badge/Microsoft%20PowerPoint-B7472A?style=flat&logo=microsoftpowerpoint&logoColor=white) **Microsoft PowerPoint** | Translated data findings into an executive stakeholder presentation — structured around the five core business questions with supporting charts and actionable recommendations. |
| ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) **GitHub** | Hosted the full project — raw data, cleaned workbook, written report, presentation deck, and interactive dashboard screenshot — as a structured, navigable portfolio repository. |

---

## Key Findings and Strategic Recommendations

### 1. Market Expansion — High-Opportunity Geographies

| Market | Average Rating | Restaurants in Dataset | Opportunity Level |
|---|---|---|---|
| **Philippines** | 4.47 | 22 | Very High |
| **Indonesia** | 4.30 | 21 | Very High |
| **Qatar** | 4.06 | 20 | High |
| **Sri Lanka** | 3.87 | 20 | High |
| **Singapore** | 3.58 | 20 | High |
| **Canada** | 3.58 | 4 | High |
| **India** | 2.77 | 8,600+ | Saturated |

**Recommendation:** The Philippines and Indonesia demonstrate the highest quality-to-competition ratio in the dataset. With ratings of 4.47 and 4.30 respectively, alongside minimal existing platform presence, these markets represent strong candidates for accelerated restaurant onboarding and expansion investment.

---

### 2. Service Features — Impact on Customer Satisfaction

| Service Feature | Average Rating (Enabled) | Average Rating (Not Enabled) | Difference |
|---|---|---|---|
| **Table Booking** | 3.48 | 2.81 | +0.67 points |
| **Online Delivery** | 3.29 | 2.75 | +0.53 points |

**Recommendation:** Both features show a consistent rating lift in the data — 0.67 points for table booking, 0.53 for online delivery. The data suggests that encouraging more restaurant partners to enable these features is associated with higher average ratings, without requiring changes to the restaurant mix.

---

### 3. Cuisine Performance — Top-Rated Categories

**Continental** and **Italian** cuisines consistently achieve the highest average customer ratings across all markets in the dataset.

**Recommendation:** During new market entry, prioritise onboarding Continental and Italian restaurant partners to establish a strong initial quality perception among early platform users.

---

### 4. Pricing Strategy — Optimal Price Tier

| Price Range | Average Rating | Competition Level |
|---|---|---|
| Range 1 — Budget | Below average | Very High |
| Range 2 — Mid | Moderate | High |
| **Range 3 — Mid-High** | **3.71** | **Moderate** |
| Range 4 — Premium | Variable | Low |

**Recommendation:** Price Range 3 delivers the strongest balance of customer satisfaction and competitive space. Partner acquisition efforts and promotional investment should be weighted toward this segment for maximum return.

---

### 5. Market Saturation — India

India accounts for approximately **90% of the total dataset** (8,600+ restaurants) yet records an average rating of only **2.77**. The data shows an association between high market density and greater quality variance — markets with fewer restaurants tend to show higher average ratings in this dataset.

**Recommendation:** The India strategy should move from adding restaurants to curating them. A partner certification tier and a quality-filtered discovery mode would give users a reason to trust the platform in a market where the average rating is 2.77 across 8,600 restaurants.

---

## Repository Structure

```
zomato-project/
│
├── data/
│   └── Zomato_Restaurant_Analysis.xlsx    # Primary workbook: raw data, cleaned data,
│                                           # Pivot Tables and interactive slicer dashboard
│
├── reports/
│   ├── Zomato_Final_Submission.docx       # Complete written report: methodology,
│   │                                       # formulas used and all business question responses
│   └── Zomato_Restaurant_Analysis.pptx   # Stakeholder presentation slide deck
│
├── dashboard/
│   └── dashboard_preview.png             # Screenshot of the final interactive dashboard
│
├── .gitignore
└── README.md
```

---

## Getting Started

**Prerequisites:** Microsoft Excel 2016 or later is required to interact with slicers and dynamic dashboard elements.

**Step 1 — Clone the repository:**
```bash
git clone https://github.com/manthan270/Global-Restaurant-Analysis.git
cd Global-Restaurant-Analysis
```

**Step 2 — Open the primary workbook:**

Navigate to `data/Zomato_Restaurant_Analysis.xlsx` and open it in Microsoft Excel. Use the **Country** and **Year** slicers to filter the dashboard dynamically across all charts and KPI cards.

**Step 3 — Review supporting documentation:**

The `reports/` folder contains the complete written methodology and the executive presentation deck.

---

## ⚠️ Limitations & Assumptions

Every analysis has boundaries. Here is what this project cannot fully account for:

- Data is from 2010–2018 — market conditions, ratings, and competition levels may have changed significantly since then
- India dominates the dataset (90.6%) — this skews several global averages and should be kept in mind when reading overall metrics
- Ratings are user-submitted — they are subject to selection bias; highly engaged users may not represent the average customer
- Costs are in local currencies — no currency conversion was applied, so cost comparisons across countries are not direct
- Low restaurant counts in some countries — markets like Canada (4) and Singapore (20) have very small samples, so their averages should be interpreted with caution

---

## Author

<div align="center">

**Manthan Gadegone**
*Data Analyst*

[![GitHub](https://img.shields.io/badge/GitHub-manthan270-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/manthan270)
[![Email](https://img.shields.io/badge/Email-manthangadegone0%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:manthangadegone0@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-manthan270-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manthan270)

</div>

---

<!--
REPOSITORY SETUP NOTES (not rendered on GitHub)

To clone and explore this project locally:

1. Clone the repository:
   git clone https://github.com/manthan270/Global-Restaurant-Analysis.git
   cd Global-Restaurant-Analysis

2. Open data/Zomato_Restaurant_Analysis.xlsx in Microsoft Excel 2016 or later.
   Use the Country and Year slicers to filter the dashboard dynamically.

3. Review reports/Zomato_Final_Submission.docx for full methodology and findings.

4. Open reports/Zomato_Restaurant_Analysis.pptx for the executive presentation deck.

5. dashboard/dashboard_preview.png contains a static screenshot of the final dashboard.
-->

<!--
MANUAL SETUP STEPS (do these on GitHub.com — cannot be done via README):

1. Go to your repository page on GitHub
2. Click the gear icon next to "About" on the right sidebar
3. Add this description:
   End-to-end Excel data analysis of 9,551 restaurants across 15 countries,
   featuring data cleaning, Pivot Tables, business insights, and an interactive dashboard.
4. Add these topic tags:
   excel, data-analysis, dashboard, business-intelligence,
   data-visualization, pivot-tables, zomato
5. Click Save changes
-->
