# FoodHub Order Analysis
Exploratory Data Analysis of **FoodHub** food delivery orders using Python

---

## Project Overview
This project uncovers demand patterns, delivery performance issues, and revenue insights across 1,898 orders.

---

## Objective
Analyze order patterns to identify key insights and provide 
actionable business recommendations.

---

## Key Findings

- **American** and **Japanese** cuisines are most popular.
- **Shake Shack** is the #1 restaurant with 219 orders (11.5% of total)
- **Weekends drive 2.5× more orders** than weekdays (1,351 vs 547)
- **Weekday deliveries take 26% longer** despite fewer orders (28.3 min vs 22.5 min)
- **10.5% of orders exceed 60 minutes** total from placement to delivery
- **38.8% of orders are unrated** — a significant customer feedback gap
- **Net revenue: $6,166.30** across all orders

---


## Project Structure

```
foodhub-analysis/
├── data/
│   └── foodhub_order.csv       # Raw dataset
├── notebooks/
│   └── foodhub_analysis.ipynb  # Main analysis notebook
├── requirements.txt
└── README.md
```

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.2.2-green)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13.2-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.10.0-red)

---

## How to Run

```bash
# 1. Clone the repository
git clone https://github.com/your-username/foodhub-analysis.git
cd foodhub-analysis

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch the notebook
jupyter notebook notebooks/foodhub_analysis.ipynb
```

> **Note:** The dataset `foodhub_order.csv` should be placed in the `data/` folder.

---

## Analysis Sections

| Section | Description |
|---|---|
| Data Overview | Shape, dtypes, missing values, statistical summary |
| Demand Analysis | Cuisine popularity, weekday vs weekend, top restaurants |
| Time & Delivery Analysis | Prep and delivery distributions, 60-min threshold, weekday vs weekend delivery |
| Revenue Analysis | Cost distribution, commission tiers, net revenue |
| Rating Analysis | Correlation with measurable factors, promotional restaurant criteria |
| Conclusions | 7 data-backed business recommendations |

---

## Recommendations Summary

1. **Expand high-demand cuisines** — reduce over-reliance on Shake Shack
2. **Fix weekday delivery** — deploy more agents during weekday hours
3. **Reduce 60-min orders** — implement SLAs for slow restaurants
4. **Close the rating gap** — incentivize customers to rate after delivery
5. **Promote top 4 restaurants** — Shake Shack, Meatball Shop, Blue Ribbon Sushi & Fried Chicken
6. **Drive weekday volume** — targeted weekday promotions
7. **Grow high-value orders** — bundle deals and free delivery thresholds

---

*Dataset provided as part of a data science course project. Analysis and recommendations are original.*
