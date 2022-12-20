# EDA & Customer Segmentation for E-Commerce Data

## Set up environment
```
$ pip install -r requirements.txt
```

## Analysis Process

### Define the business questions & the objective
* Do the RFM analysis to understand our customers
* Do customer segmentation based on RFM analysis
### RFM Analysis
RFM analysis is a marketing technique used to quantitatively rank and group customers based on their **recency**, **frequency**, and **monetary** to identify the best customers and perform targeted marketing campaigns.

* **Recency:** How recently has the customer made a transaction?
* **Frequency:** How often do customers order?
* **Monetary:** How much money have customers spent on products on this website/app?

| RFM Analysis | Avg Value
| --- | --- |
| Recency (in days) | 288.108797 |
| Frequency | 1.081075 |
| Monetary | 166.592492 |

## Customer Segmentation Base on RFM Analysis

Based on RFM analysis, we have 5 cluster of our customers, such as:

* **Cluster 0**: New Customers and low spenders
* **Cluster 1**: The Churn Customers (it's been more than a year (on avg) since the previous purchase)
* **Cluster 2**: The Big Spender
* **Cluster 3**: The Loyal Customers
* **Cluster 4**: The Loyal Customers & Slightly Higher Spenders