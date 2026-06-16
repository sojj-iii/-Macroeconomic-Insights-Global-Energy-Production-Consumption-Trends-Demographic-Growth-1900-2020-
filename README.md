# 🌍 Macroeconomic Insights: Global Energy Production, Consumption Trends & Demographic Growth (1900–2020)

<img width="1919" height="1044" alt="Screenshot 2026-05-27 031122" src="https://github.com/user-attachments/assets/5ab3fd58-eb20-4f43-924b-3361a82aa450" />


## 📌 Project Overview

This multi-layered macroeconomic dashboard examines **120 years of human development and resource utilization** (1900–2020) by cross-referencing global population expansion and GDP growth with total energy production and annual consumption shifts across **coal, gas, hydro, and oil** energy sectors.

The dashboard helps economists, researchers, and policy analysts understand how demographic growth and economic development have shaped — and been shaped by — global energy demand over more than a century.

---

## 🎯 Problem Statement

Understanding the relationship between population growth, economic output, and energy consumption is critical for informing modern energy policy and sustainability strategies. Yet this data is rarely presented in a way that allows meaningful cross-sector comparison across time.

This dashboard bridges that gap by presenting a unified, interactive view of these interconnected trends — making complex macroeconomic data accessible and actionable.

---

## 📊 Key Insights

- Revealed a strong **positive correlation between GDP growth and energy consumption** from 1900 to 2020
- Identified the **decade-by-decade shift** from coal dominance toward gas and oil as primary energy sources
- Highlighted how **population booms in Asia and Africa** from the 1950s onward drove the sharpest increases in global energy demand
- Showed the **relative flattening of hydro energy growth** despite rising consumption needs globally
- Pinpointed key **geopolitical events** (World Wars, oil crises) reflected as disruptions in the energy trend lines

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Tableau Desktop | Dashboard development & interactive visualizations |
| Python (Pandas, NumPy) | Data cleaning, transformation & exploratory analysis |
| Excel | Raw data preprocessing and validation |
| Tableau Calculated Fields | Custom measures and KPI logic |
| Tableau Prep | ETL pipeline and data shaping |

---

## 📁 Repository Structure

```
macroeconomic-energy-dashboard/
│
├── data/
│   └── global_energy_population_gdp.csv   # Cleaned dataset (1900–2020)
│
├── sql/
│   └── data_queries.sql                   # SQL queries for data extraction
│
├── python/
│   └── data_cleaning.ipynb                # Jupyter notebook for data preprocessing
│
├── dashboard/
│   └── Macroeconomic_Energy_Dashboard.twbx  # Tableau packaged workbook file
│
├── assets/
│   ├── dashboard-preview.png              # Main dashboard screenshot
│   ├── page1_overview.png
│   ├── page2_energy_trends.png
│   └── page3_gdp_population.png
│
└── README.md
```

---

## 🖥️ Dashboard Pages

1. **Global Overview** — High-level KPIs: Total Energy Production, Total Consumption, Global Population, Cumulative GDP (1900–2020)
2. **Energy Production Trends** — Year-by-year breakdown of coal, gas, hydro, and oil production volumes
3. **Consumption vs Production Gap** — Analysis of supply-demand dynamics across decades and regions
4. **GDP & Population Growth** — Economic output and demographic expansion mapped against energy trends
5. **Regional Deep Dive** — Continent-level breakdown of energy production and consumption shifts
6. **Key Events Timeline** — How major global events impacted energy patterns across the century

---

## 🚀 How to View the Dashboard

### Option 1 — Tableau Workbook File
1. Download `Macroeconomic_Energy_Dashboard.twbx` from the `/dashboard` folder
2. Open with [Tableau Desktop](https://www.tableau.com/products/desktop) or [Tableau Public](https://public.tableau.com/) (free)
3. Use filters and interactive controls to explore by year range, energy type, or region

### Option 2 — Live Demo on Tableau Public
👉 **[View Live Dashboard on Tableau Public]([LINK_HERE]) https://public.tableau.com/app/profile/elisha.olusoji.soji.isola/viz/WORLDENERGYCONSUMPTIONDASHBOARD_16622911238680/WORLDENERGYCONSUMPTIONDASHBOARD**
<!-- Publish your dashboard to Tableau Public and paste the link above -->

---

## 📸 Dashboard Preview

| Global Overview | Energy Trends |
|---|---|
| ![Overview](assets/page1_overview.png) | ![Energy](assets/page2_energy_trends.png) |

| GDP & Population | Regional Breakdown |
|---|---|
| ![GDP](assets/page3_gdp_population.png) | ![Regional](assets/page4_regional.png) |

---

## 📂 Data Sources

| Dataset | Source |
|---------|--------|
| Global Energy Production & Consumption | [Our World in Data](https://ourworldindata.org/energy) |
| World Population Data (1900–2020) | [World Bank Open Data](https://data.worldbank.org/) |
| Global GDP Historical Data | [Maddison Project Database](https://www.rug.nl/ggdc/historicaldevelopment/maddison/) |

> All datasets used are publicly available and open source.

---

## 💡 Skills Demonstrated

- Macroeconomic data analysis and interpretation
- Multi-source data integration and relationship modelling
- Time-series analysis across 120 years of historical data
- Python data cleaning and exploratory data analysis (EDA)
- Advanced Tableau calculated fields and LOD expressions
- Time-series visualization across 120 years of historical data
- Storytelling with data for policy and research audiences
- Interactive dashboard design for non-technical stakeholders
