# Instacart Customer Analysis

## Introduction

Instacart is a technology company that operates as a same-day grocery delivery and pick up service in the U.S. and Canada. Customers shop for groceries through the Instacart mobile app or Instacart.com from various retailer partners. The order is shopped and delivered by an Instacart personal shopper. Their goal is to ensure customers get their groceries delivered reliably, to lift up our retail partners, and to provide flexible earnings opportunities for shoppers.

### Objectives:
- Analyze the anonymized [data](https://www.kaggle.com/c/instacart-market-basket-analysis/data) of 3 million grocery orders from more than 200,000 Instacart users open sourced by Instacart.
- Identify any pattern of what customers buy and how often they buy them.
- Use SQL, Python to perform EDA and Tableau for visualization.


## Data Description

- **aisles:** This file contains different aisles and there are total 134 unique aisles.

- **departments:** This file contains different departments and there are total 21 unique departments.

- **orders:** This file contains all the orders made by different users. From below analysis, we can conclude following:
    - There are total 3421083 orders made by total 206209 users.
    - The total orders per customer ranges from 0 to 100.
    - Based on the plot of 'Orders VS Day of Week' we can map 0 and 1 as Saturday and Sunday respectively based on the assumption that most of the people buy groceries on weekends.
    - Majority of the orders are made during the day time.  
    - Customers order once in a week which is supported by peaks at 7, 14, 21 and 30 in 'Orders VS Days since prior order' graph.
    - Based on the graph between 'Day of Week' and 'Hour of Day,' we can say that Saturday afternoons and Sunday mornings are prime time for orders.

 