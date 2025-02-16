# HSBC-Analytics-Customer-Segmentation-of-a-Banking-Financial-Services-Clustering
Customer Segmentation of HSBC using credit card usage data - K-Means Clustering


## Industry Context
In the highly competitive **Banking and Financial Services Industry**, understanding customer needs and behaviors is crucial for retaining clients, cross-selling products, and increasing overall customer satisfaction. Traditional segmentation methods often fail to capture the nuances of customer profiles, making it essential to employ advanced techniques like **K-Means Clustering** for more precise segmentation.

## Objective
The objective of this project is to segment customers in the banking and financial services industry based on their behaviors and characteristics using K-Means Clustering. This segmentation will help in tailoring marketing strategies, improving customer retention, and optimizing product offerings.

## Dataset Description


The dataset used in this project is focused on customer credit card usage data within the banking and financial services industry. Below is a detailed description of each attribute in the dataset:

- **CUST_ID**: Unique identifier for each customer.
- **BALANCE**: The current balance on the credit card account.
- **BALANCE_FREQUENCY**: Frequency of balance updates; measures how often the balance is updated.
- **PURCHASES**: Total amount of purchases made with the credit card.
- **ONEOFF_PURCHASES**: Total amount of purchases made in a single transaction.
- **INSTALLMENTS_PURCHASES**: Total amount of purchases made in installments.
- **CASH_ADVANCE**: Total amount of cash advances taken using the credit card.
- **PURCHASES_FREQUENCY**: Frequency of purchases made with the credit card.
- **ONEOFF_PURCHASES_FREQUENCY**: Frequency of one-off purchases made with the credit card.
- **PURCHASES_INSTALLMENTS_FREQUENCY**: Frequency of installment purchases made with the credit card.
- **CASH_ADVANCE_FREQUENCY**: Frequency of cash advances taken.
- **CASH_ADVANCE_TRX**: Total number of cash advance transactions.
- **PURCHASES_TRX**: Total number of purchase transactions.
- **CREDIT_LIMIT**: The credit limit assigned to the credit card.
- **PAYMENTS**: Total amount of payments made towards the credit card balance.
- **MINIMUM_PAYMENTS**: Minimum amount required to be paid towards the credit card balance.
- **PRC_FULL_PAYMENT**: Percentage of total balance paid off in full each month.
- **TENURE**: Duration of the credit card account in months.

This dataset captures a comprehensive range of credit card usage behaviors and financial attributes, which are critical for performing customer segmentation and understanding different spending patterns within the banking sector.


## Methodology
The project follows these steps:
1. **Data Collection & Preprocessing**: Collected customer data and cleaned it by handling missing values, outliers, and normalizing the data.
2. **Feature Selection**: Key features relevant to customer segmentation were selected for clustering.
3. **K-Means Clustering**: Implemented K-Means algorithm to identify distinct customer segments.
4. **Determination of Optimal Clusters**: Used the **Elbow Method** and **Silhouette Score** to determine the optimal number of clusters.
5. **Cluster Analysis**: Analyzed the characteristics of each cluster to derive actionable insights.

## K-Means Clustering
K-Means Clustering was employed to group customers into clusters based on their behaviors and features. The **Elbow Method** and **Silhouette Score** were utilized to identify the optimal number of clusters.

**Optimal Clusters Identified**: The analysis determined that the optimal number of clusters is **[mention the number of clusters here]**.

### Cluster Characteristics
- **Cluster 1**:
  - **High Purchase Frequency:** These customers are actively using their credit cards, indicating they are engaged and value financial tools. This makes them receptive to offers that can enhance their spending experience, such as credit card upgrades and investment products. Additionally the high purchase frequency and high percentage of full payments indicate that these customers are financially responsible and could be interested in savings plans to maximize their benefits.

  - **Low Balance:** Their low balance suggests they are managing their finances well and may be looking for ways to save and invest their money effectively, making savings plans and investment products highly relevant, and small loans might be more suitable as they might not require large amounts of credit.
- **Cluster 2**:
  - **High Balance and High Cash Advance Usage:** These customers have substantial balances and frequently use cash advances, indicating a need for accessible funds and potentially greater financial stability. The high balance and high cash advances suggest a need for liquid cash, making larger loans, and debt consolidation services might be an attractive option for managing finances.

  - **Frequent Cash Advances & high credit limit:** This behavior suggests a higher risk profile, making insurance products a relevant offer to mitigate financial risks. The high credit limit and substantial payments suggest that these customers have the capacity to handle larger financial products, making premium savings plans suitable.
- **Cluster 3**:
  - **Moderate Balance and Usage:** These customers exhibit stable financial behavior, making them ideal candidates for consistent savings and investment products.

  - **Moderate Usage:** Their balanced approach to credit card use suggests they are likely to be receptive to medium-sized loans and retirement plans that support their long-term financial stability.

## Insights 
- **Customer Diversity**: The analysis revealed significant diversity in customer behaviors and needs, emphasizing the importance of targeted strategies.
- **Strategic Focus**: Clusters with high profitability potential should be the focus of strategic efforts to maximize revenue.
- **Actionable Insights**: The segmentation provides actionable insights into how to approach different customer groups with tailored solutions.

## Recommendations
Based on the cluster analysis, the following recommendations are made:
1. **Tailored Marketing Strategies**: Develop personalized marketing campaigns targeting specific clusters.
2. **Product Optimization**: Introduce or modify products that align with the needs of high-value clusters.
3. **Customer Retention Programs**: Implement loyalty programs for clusters identified as at-risk for churn.


## Actionables
1. **Marketing**: Customize campaigns based on cluster profiles to increase engagement.
2. **Product Development**: Align product offerings with the specific needs identified within each cluster.
3. **Customer Service**: Enhance service delivery for high-value segments to improve satisfaction and loyalty.




## Conclusion
This project successfully segmented customers into distinct clusters, providing valuable insights into customer behaviors and enabling more effective marketing, product development, and customer retention strategies. The approach demonstrates the power of K-Means Clustering in revealing underlying patterns within customer data in the banking and financial services industry.

[Processed Dataset Link - Output](https://github.com/ShouvikSaha504/Customer-Segmentation-of-a-Banking-Financial-Services-/blob/9e7a0c10f0a974d2f798f5f3d3653a50e901ecf6/Clustered_Customer_Data.csv)

