<p align="center">
  <img src="images/banner.png" alt="United Airlines Network Performance Optimization" width="100%">
</p>

<h1 align="center">✈️ United Airlines Network Performance Optimization</h1>

<p align="center">
A business-focused airline operations analytics project using Python to identify delay patterns, evaluate route and airport performance, and recommend operational improvements.
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Dataset-U.S.%20DOT%20Flights-blue?style=for-the-badge)

</p>

---

# 📖 Executive Summary

Airline operations are highly interconnected, where delays at a single airport or route can propagate across the network, affecting aircraft utilization, crew scheduling, passenger connections, and overall operational reliability.

This project analyzes **472,355 United Airlines flights** from the **U.S. Department of Transportation (DOT) On-Time Performance Dataset (2015)** to identify operational bottlenecks, evaluate network performance, and provide actionable business recommendations.

Rather than focusing on machine learning, this project demonstrates how **business analytics** can support operational decision-making through data exploration, KPI analysis, and operational performance evaluation.

---

# 🎯 Business Problem

United Airlines operates one of the world's largest hub-and-spoke networks.

Small operational disruptions can lead to:

- Flight delays
- Missed passenger connections
- Increased crew costs
- Aircraft rotation issues
- Reduced aircraft utilization
- Lower customer satisfaction
- Network-wide delay propagation

The objective of this project is to identify where operational improvements would have the greatest impact using historical flight performance data.

---

# 🎯 Project Objectives

- Analyze operational performance across United Airlines' network
- Measure delay and cancellation performance
- Evaluate airport-level operational efficiency
- Identify high-risk routes
- Understand hourly and monthly delay trends
- Discover operational bottlenecks
- Provide actionable business recommendations

---

# 📊 Dataset

### Source

**U.S. Department of Transportation (DOT)**

On-Time Performance Dataset (2015)

---

### Dataset Summary

| Metric | Value |
|---------|------:|
| Original Flights | 5.8+ Million |
| United Airlines Flights | 515,723 |
| Final Analysis Dataset | 472,355 |
| Airports | 322 |

During data preparation, flights containing inconsistent airport identifiers were removed to ensure accurate route-level analysis and consistent airport mapping.

---

# 🔄 Project Workflow

```text
Business Problem
        │
        ▼
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Route Performance Analysis
        │
        ▼
Airport Performance Analysis
        │
        ▼
Time-Based Analysis
        │
        ▼
Business Recommendations
```

---

# 🛠 Tech Stack

| Category | Tools |
|----------|-------|
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib |
| Notebook | Google Colab / Jupyter |
| Dataset | U.S. DOT On-Time Performance Dataset |

---

# 📈 Key Performance Indicators

| KPI | Value |
|------|------:|
| Total Flights | 472,355 |
| Delay Rate | 21.10% |
| Cancellation Rate | 1.37% |
| Average Arrival Delay | 6.20 Minutes |

---

# 📊 Analysis Performed

## Operational Performance Overview

- Overall network performance
- Delay analysis
- Cancellation analysis
- Flight volume analysis

---

## Route Performance Analysis

- Top busiest routes
- Highest delay routes
- Average arrival delay
- Route-level operational evaluation

---

## Airport Performance Analysis

- Top departure hubs
- Top arrival hubs
- Airport delay performance
- Hub operational evaluation

---

## Time-Based Analysis

- Delay rate by departure hour
- Monthly operational trends
- Delay propagation analysis

---

# 💡 Key Business Insights

### ✈️ Network Hubs

Chicago (ORD), Houston (IAH), Denver (DEN), San Francisco (SFO), and Newark (EWR) represent the core of United Airlines' network. Operational improvements at these airports have the potential to improve reliability across a large portion of the network.

---

### 🛫 Route Performance

A relatively small number of routes experience consistently higher delay rates, suggesting opportunities for targeted operational improvements.

---

### 🏢 Airport Operations

Major hub airports experience greater operational complexity due to aircraft rotations, connecting passengers, gate utilization, and crew scheduling.

---

### ⏰ Delay Propagation

Delay rates generally increase throughout the day, indicating that operational disruptions accumulate as aircraft continue through their daily schedules.

---

### 📅 Seasonality

Monthly delay patterns suggest that operational performance varies throughout the year, highlighting periods where additional operational planning may improve reliability.

---

# 🚀 Business Recommendations

- Improve turnaround efficiency at major hubs
- Optimize departure bank scheduling
- Increase operational buffers during peak hours
- Improve aircraft rotation planning
- Monitor high-delay routes using KPI dashboards
- Develop predictive operational monitoring dashboards
- Prioritize operational improvements at high-volume airports

---

# 📁 Repository Structure

```text
united-airlines-network-performance-optimization
│
├── images
│   └── banner.png
│
├── notebook
│   └── United_Airlines_Network_Performance.ipynb
│
├── report
│   └── United_Airlines_Network_Performance_Report.pdf
│
├── data
│   └── README.md
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/yourusername/united-airlines-network-performance-optimization.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Open the notebook

```text
notebook/United_Airlines_Network_Performance.ipynb
```

Run all notebook cells to reproduce the analysis.

---

# 📄 Executive Report

A professionally formatted executive business report is included in the `report` folder.

```text
report/United_Airlines_Network_Performance_Report.pdf
```

---

# 📌 Future Enhancements

- Interactive Power BI dashboard
- Predictive delay modeling
- Weather data integration
- Airport capacity analysis
- Route profitability analysis
- Real-time operational monitoring dashboard

---

# ⚠️ Disclaimer

This project was created for educational and portfolio purposes using publicly available data from the U.S. Department of Transportation (DOT). It is an independent analysis and is not affiliated with, endorsed by, or produced for United Airlines.

---

# 👨‍💻 Author

## Gaurav Chauhan

**Data Analytics | Business Intelligence | Python | SQL | Power BI**

If you found this project useful, consider giving it a ⭐ to support the project.
