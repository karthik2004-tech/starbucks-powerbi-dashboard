# Starbucks Beverage Nutrition & Store Insights Dashboard

> **Brewing Insights. Fueling Connections.**
> An interactive Power BI dashboard that turns Starbucks beverage nutrition data and global store locations into a clear, one-page view for non-technical readers.

![Dashboard preview](dashboard.png)

---

## Overview

Which Starbucks drinks are the heaviest in calories? Which categories deliver the most caffeine? And where in the world are the stores?

This project answers those questions in a single interactive report. It combines a **beverage nutrition table** with a **worldwide store-location table**, adds **DAX measures** for the headline KPIs, and lets users filter by protein range and beverage preparation type.

**Tools:** Power BI Desktop, DAX

---

## Key Metrics

| Metric | Value |
|---|---|
| Total beverages analysed | 33 |
| Average calories | 193.78 |
| Average sugar | 32.90 |
| Average caffeine | 82 |

---

## Key Insights

- **Coffee has the highest average caffeine by a wide margin** and also the lowest average calories, making it the lightest category on the menu.
- **Smoothies and Frappuccino Blended drinks sit at the top of average calories**, while plain coffee and shaken iced beverages sit at the bottom.
- **Classic Espresso Drinks are the largest category**, at 7 of the 33 beverages (20.59%).
- **White Chocolate Mocha, Tazo Green Tea Latte, Java Chip, Hot Chocolate and Caffè Mocha** have the highest total calories among the beverages shown.
- **Stores are concentrated in North America, Europe and East Asia**, as shown on the global presence map.

*(Insights are read from the dashboard's current filters. Update this section if you change the data or filters.)*

---

## Dashboard Features

- **KPI cards:** total beverages, average sugar, average calories, average caffeine
- **Average calories by beverage category:** compares categories at a glance
- **Beverage category distribution:** share of the menu by category (donut chart)
- **Total calories by beverage:** ranks the highest-calorie drinks
- **Average caffeine by category:** shows which categories deliver the most caffeine
- **Global store map:** plots store locations by latitude and longitude
- **Slicers:** filter by **Protein Range** and **Beverage Prep**

---

## Data Model

| Table | Purpose | Key fields |
|---|---|---|
| `starbucks` | Beverage nutrition data | Beverage, Beverage category, Calories, Sugar, Caffeine, Protein |
| `directory` | Worldwide store locations | Country, Latitude, Longitude |
| `Measures` | DAX measures | Total Beverages, Avg Calories, Avg Sugar, Avg Caffeine |

**DAX measures**

- **Total Beverages:** number of beverages in the current filter
- **Avg Calories:** average calories of the beverages in the current filter
- **Avg Sugar:** average sugar of the beverages in the current filter
- **Avg Caffeine:** average caffeine of the beverages in the current filter

---

## Data Sources

- Starbucks beverage nutrition dataset: [add source link]
- Starbucks store locations dataset: [add source link]

Data is used for educational and portfolio purposes.

---

## Repository Structure

```
starbucks-powerbi-dashboard/
├── starbucks-analysis.pbix   # Power BI report (open in Power BI Desktop)
├── dashboard.png             # Dashboard screenshot
├── dashboard.pdf             # PDF export of the report
├── data/                     # Source CSV files
└── README.md
```

---

## How to Open

1. Download or clone this repository.
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows).
3. Open `starbucks-analysis.pbix`.
4. Use the **Protein Range** and **Beverage Prep** slicers to explore.

If you only want a quick look, open `dashboard.pdf`.

---

## Skills Demonstrated

- Data modelling across multiple tables
- Writing DAX measures
- KPI design and dashboard layout
- Choosing the right chart for each question
- Turning raw data into insights for non-technical readers

---

## Possible Next Steps

- Add nutrition-per-size comparisons (tall, grande, venti)
- Add a "healthier swaps" view that suggests lower-sugar alternatives within each category
- Publish the report to the web for a live link

---

## Author

**Karthik Telukutla**
B.Tech, Artificial Intelligence & Data Science) | [GitHub](https://github.com/karthik2004-tech) | karthiktelukutla@gmail.com)
