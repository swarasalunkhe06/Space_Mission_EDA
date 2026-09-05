# 🚀 Space Missions: Exploratory Data Analysis

An exploratory data analysis (EDA) of global space missions, examining launch trends, organizations, rocket status, mission outcomes, and cost over time.

## 📌 Project Overview

This project analyzes historical space mission data to uncover patterns in:
- Launch frequency over time (by year, decade, month)
- Leading space agencies and private companies
- Mission success vs. failure rates
- Rocket/vehicle status (active vs. retired)
- Launch site and country-level activity
- Mission costs (where available)

The goal is to derive data-driven insights into how the space industry has evolved — from Cold War-era government programs to the current era of commercial spaceflight (SpaceX, Blue Origin, ISRO, etc.).


## 🎯 Objectives

1. Clean and preprocess raw mission data (handle missing values, parse dates, standardize company/country names)
2. Perform univariate and multivariate analysis on launch trends
3. Visualize mission success rates by organization, country, and era
4. Identify top-performing agencies/companies by volume and reliability
5. Summarize key findings and business/industry implications

## 🛠️ Tools & Libraries

- **Python 3.x**
- `pandas`, `numpy` – data wrangling
- `matplotlib`, `seaborn`, `plotly` – visualization
- `jupyter notebook` – analysis environment

## 📁 Project Structure

```
space-mission-eda/
├── data/
│   ├── raw/                # Original dataset
│   └── processed/          # Cleaned dataset
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 03_insights_and_visuals.ipynb
├── images/                 # Exported charts
├── requirements.txt
└── README.md
```

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/<your-username>/space-mission-eda.git
cd space-mission-eda

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

## 🔍 Key Questions Explored

- Which country/agency has launched the most missions?
- How has launch frequency changed year over year?
- What is the overall mission success rate, and how does it vary by organization?
- Which rockets are still active vs. retired?
- Is there a relationship between mission cost and success rate?
- How has the rise of private companies (SpaceX, Blue Origin) changed the launch landscape?

## 📊 Sample Insights

> *(Replace with your actual findings once analysis is complete)*
- Mission success rates have improved significantly since the 1990s.
- The United States and Russia/USSR account for the majority of historical launches, with China and private players growing fastest in recent years.
- SpaceX shows a rising launch cadence with a high success rate post-2015.

## 📈 Visualizations

Charts included in this analysis:
- Launches per year (line chart)
- Success vs. failure distribution (bar/pie chart)
- Top 10 companies by launch count
- Launch activity by country (map/bar chart)
- Cost vs. mission outcome (box plot)


## 🙋 Author

**Swara Salunkhe**
B.Sc. Information Technology | Data Analytics Enthusiast
📍 Mumbai, India
