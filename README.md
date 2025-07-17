# FedEx Logistics Performance Analysis 

## 📝 Overview

This project presents an in-depth exploratory data analysis (EDA) of a FedEx logistics dataset. The primary goal is to uncover key operational insights, identify performance trends, and analyze cost structures to support strategic business decisions. By visualizing shipment data, we can understand key markets, warehouse efficiency, shipping mode preferences, and cost-driving factors.

The analysis is contained within the `FedEx Logistics Performance Analysis.ipynb` Jupyter Notebook.

## ❓ Key Business Questions Addressed

This analysis seeks to answer several critical business questions:
1.  **Geographic Performance:** Which countries are our primary markets by shipment volume?
2.  **Warehouse Efficiency:** Which warehouse handles the most shipments and how is the workload distributed?
3.  **Cost Analysis:** What is the relationship between shipment weight and cost? Are there any pricing anomalies?
4.  **Shipment Mode Utilization:** Which shipping modes (Air, Road, Sea) are most common in our top markets?
5.  **Time-Series Trends:** How do shipment volumes fluctuate over time, and can we identify any seasonal patterns or peak periods?

## 💡 Key Insights & Findings

The analysis revealed several actionable insights:
* **Top Markets:** **South Africa** and **Nigeria** are the dominant markets, representing a significant portion of the total shipment volume. Focusing marketing and operational efforts on these regions could yield high returns.
* **Central Hub:** **Warehouse J** is the most critical node in the logistics network, handling an overwhelming majority of all shipments. Its operational efficiency is paramount to the entire system's performance.
* **Cost-Weight Correlation:** There is a strong, positive linear relationship between shipment weight and cost. However, several outliers indicate potential pricing inconsistencies or special handling charges that warrant further investigation.
* **Dominant Shipping Mode:** **Air freight** is the most utilized shipping mode across all major countries, suggesting a demand for speed and reliability.
* **Peak Volume Day:** A significant spike in shipment volume was identified on **April 5, 2021**, indicating a potential large-scale order, a data anomaly, or the start of a major logistics event.

## 💻 Technical Stack

* **Python 3.x**
* **Pandas:** For data manipulation and analysis.
* **NumPy:** For numerical operations.
* **Matplotlib & Seaborn:** For data visualization and creating insightful plots.
* **Jupyter Notebook:** As the environment for interactive analysis and reporting.
