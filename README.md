# Supermarket Customer Analysis
## Overview
This project involves analyzing supermarket customer data to get insights that can help improve business strategies and customer engagement. The analysis focuses on understanding customer behaviour, spending pattern, and demographics in order to optimize marketing efforts and sales strategies.

The dataset includes customer transactions, including how much customers spend on products, how frequently they buy from the supermarket, how often they engage with marketing campaigns, and customer demographics, such as their year of birth, education level, and marital status.

## Objective
Supermarket chains operate in a highly competitive environment where customer satisfaction and retention are critical. Understanding customer segmentation, product preferences, purchasing patterns, and campaign contribution can help in targeted marketing and customer retention. Thus, this analysis aim to:
- Identifying which product brings in the most revenue
- Evaluating the acceptance rate for each campaign
- Identifying which customer groups are most responsive to the campaigns
- Understanding if segmentation influences spending behaviour or campaign acceptance

## Dataset
The dataset used in this analysis can be found in this repository under the file `Supermarket Customers.csv`.

It consists of 2240 rows and 29 columns.

## Analysis
**1. RFM Analysis**
- Analyze customers using Recency, Frequency, and Monetary metrics to categorize them into segments, such as champions, loyal, hibernating, or lost customers.

**2. Customer Demographics Analysis**
- Analyze how demographic, such as age, marital status, and the existence of minor influence purchasing behaviour.

**3. Product Analysis**
- Analyze which products generate the most and lowest sales.

**4. Campaign Analysis**
- Analyze which campaign is outperform and underperform.
- Analyze how each segment respond to the campaigns.

## Visualizations
- Line Chart: showing the number of customers enrolled by month
- Bar Chart: showing the number of customers in each segment, total sales of products, spending patterns by segments
- Heatmap: showing the acceptance rate and number of customers by segments

A tableau dashboard is also available, which can be accessed [here](https://public.tableau.com/views/SupermarketCustomerFinal/Customer?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

## Key Findings
- Most customers are in the Hibernating and At Risk segment.
- Wine and meat generate the most sales, while fruit generate the lowest sales.
- A high total sales does not necessarily indicate a high median sales value.
- The last campaign outperformed the others, while the second campaign underperformed.

## Recommendations
- Focus on winning the "Can't Lose Them" segment back by offering them exclusive deals on products they have purchased in the past or give them loyalty rewards. Additionally, monitor their spending patterns to ensure they don't fully churn.
- Offer the Champions and Loyal Customers segment exclusive deals, personalized offers, loyalty rewards, and regular engagement/communication to make them feel valued.
- Develop targeted campaigns aimed to re-engaging customers in the Hibernating and "At Risk" segment. Offer them personalized promotion or re-engagement emails.
- Develop special offer or product bundles for wine and meat.
- Create promotional campaigns to boost fruit sales, we can offer discount or provide information about the benefit of fruits.
- Offer time-sensitive deals or referral program.
- Conduct a detailed review of the second campaign's strategy, content, or external factors to identify factors that make it underperform.
- Analyze the last campaign to know what factors contributed to its success and implement these successful elements in future campaigns.


## Tools
- Programming Language: Python
- Data Processing: Jupyter Notebook
- Libraries: Pandas, NumPy, Matplotlib, Seaborn
