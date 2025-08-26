E-commerce Customer Intelligence Dashboard
!(./Screenshot%202025-08-26%20075131.png)

1. Business Problem & Objective
I took on the role of a data analyst for a UK-based e-commerce retailer. The company had a large, raw dataset of over 500,000 transactions but lacked clear insights into customer behavior. The objective was to transform this data into an interactive dashboard that could answer critical business questions about sales trends, customer value, and retention, ultimately providing actionable intelligence to drive growth.

2. Tools Used
Excel: Power Query, PivotTables, PivotCharts, Formulas (XLOOKUP, IF statements), Data Analysis ToolPak (Regression).

3. The Analytical Process
A. Data Cleaning and Preparation (with Power Query)
The analysis began with cleaning and preparing the raw transactional data using Power Query. The automated pipeline handled common real-world issues such as missing CustomerIDs, duplicate entries, and canceled orders (indicated by negative quantities), ensuring a reliable foundation for analysis.

B. Exploratory Data Analysis (EDA)
Initial EDA was conducted using PivotTables to answer fundamental business questions. This revealed key insights into sales trends, top products, and geographic distribution.

Monthly Sales Trend: The analysis revealed a clear seasonal trend, with sales peaking in November. Crucially, it also identified that the sharp drop in December 2011 was a data artifact due to an incomplete dataset (ending Dec 9th), a critical insight that prevents misleading conclusions.

Geographic Sales: The data showed that sales are heavily dominated by the United Kingdom. This insight led to the recommendation of creating a separate chart for "Top International Markets" to analyze those opportunities without the UK skewing the visual.

Top Products: A bar chart was created to identify the top 10 revenue-generating products, providing key information for inventory and marketing strategies.

C. Advanced Analysis: Uncovering Deeper Insights
To move beyond basic reporting, several advanced analytical techniques were employed:

Customer Lifetime Value (CLV): CLV was calculated for each customer to understand their long-term profitability. Customers were then segmented into value tiers ("Platinum," "Gold," "Silver," "One-Time Buyer") using this metric, allowing for more strategic marketing efforts.

Cohort Analysis: A cohort analysis was performed to visualize customer retention over time. The resulting heat map tracks each group of new customers and shows what percentage of them returned to make a purchase in subsequent months. This provides a clear view of customer loyalty and the effectiveness of retention strategies.

Churn Driver Analysis: A regression model was built to identify the key drivers of customer churn. The analysis proved that CustomerLifespan was the most statistically significant predictor, providing a clear, data-driven mandate for the business to focus on nurturing long-term relationships.

D. The Final Deliverable: The Interactive Dashboard
All analyses were synthesized into a single, interactive executive dashboard. The dashboard features high-level KPIs, detailed charts, and strategic slicers, such as the CLV_Segment filter. This tool transforms the complex data into a user-friendly format, empowering stakeholders to explore the findings and make data-driven decisions.

4. Key Insights & Actionable Recommendations
The analysis yielded several actionable insights that can directly inform business strategy:

Insight 1: Focus on Long-Term Relationships. The churn analysis proved CustomerLifespan is the key to retention. Recommendation: Implement a tiered loyalty program that rewards customers on their anniversaries to encourage longevity.

Insight 2: Not All Customers Are Equal. The CLV analysis segmented customers into distinct value tiers. Recommendation: Use the CLV_Segment slicer on the dashboard to analyze the purchasing habits of "Platinum" customers and create targeted marketing campaigns to retain this highly valuable group.

Insight 3: Seasonality is Predictable. The sales trend chart shows a clear peak in November. Recommendation: The business should plan inventory and marketing efforts to capitalize on this predictable holiday rush.

Conclusion
This project successfully completed the full data analysis lifecycle—from cleaning messy data with Power Query to delivering strategic, forward-looking recommendations via an interactive dashboard. It transformed a raw dataset into a powerful, holistic tool for data-driven decision-making.
