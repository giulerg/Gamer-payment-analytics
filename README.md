# Revenue Metrics Dashboard (MRR, ARPPU, Churn, LTV, LT)

## Project Description
This project focuses on analyzing subscription-based revenue metrics and visualizing them in an interactive dashboard. 
The goal is to provide insights into recurring revenue, user dynamics, and churn, enabling better decision-making for product and financial teams.

## Data Source
Data was taken from a PostgreSQL database and exported to CSV files. The CSV files are included in this repository.

## Tools and Technologies
- SQL (PostgreSQL)
- Tableau Public

## Workflow
1. Wrote SQL queries to extract relevant data.
2. Exported the results to CSV for reproducibility.
3. Built a Tableau Public dashboard with multiple visualizations, including:
   - Monthly Recurring Revenue (MRR) and paid users over time,
   - New and churned users,
   - ARPPU,
   - Revenue Churn,
   - Customer Lifetime (LT) and Customer Lifetime Value (LTV) and etc.
4. Added filters by date, user language, and user age.

## Results
- A dashboard was created to track the dynamics of revenue and key growth/decline factors.
- Flexible filters were implemented for interactive analysis.
- The dashboard provides a tool for assessing the financial health of the product and monitoring user behavior.

## Conclusions
As a result of the analysis, key subscription metrics were calculated and visualized.  
The dashboard revealed several important insights:
- The peak revenue was reached in **October 2022**, even though the largest number of **new paid users** was recorded in **August 2022**.  
- After October, there is a noticeable decline in revenue growth.  
- This trend is reflected in the contraction of recurring revenue (Contraction MRR), highlighting the impact of reduced payments from existing users.  

Overall, the analysis allowed us to identify growth and churn dynamics and laid the foundation for future forecasting.

## Materials
- [SQL queries](./queries.sql)
- [Dashboard on Tableau Public](https://public.tableau.com/views/GamerpaymentsAnalytics/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- [`games_paid_users.csv`](./games_paid_users.csv)  user data  
- [`games_payments.csv`](./games_payments.csv)  payments data  
