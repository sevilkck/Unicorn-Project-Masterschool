# Unicorn Company Business Performance Analysis Report


Prepared for: Master School Unicorn Project

Date: July 25, 2025

**Team**

- Tehmina Aziz
- Sevil Kücük
- Rutvik Pimpalkar
- Hande Gabrali-Knobloch

# References

Tableau Link: 

https://public.tableau.com/app/profile/sevil.k.c.k/viz/UnicornCompanyBusinessInsightsPerformanceTrends/UnicornProject

Google Sheets Link:

https://docs.google.com/spreadsheets/d/1A0pxUhfjoE3QrVV9f47qjHR61X-crIvakbLTxAq4tKQ/edit?gid=1868140062#gid=1868140062 

YouTube Presentation Link

https://youtu.be/pqJtQQNRlN0



# 1. Executive Summary
This report provides a comprehensive analysis of the company's business performance from 2015 to 2018, leveraging key operational and financial metrics. Overall, the period showcased robust sales growth, culminating in Total Sales of $2,297,355 and Total Profit of $286,347, yielding an Overall Profit Margin of 12%. While growth trends were generally positive through 2017, a notable decline in Q4 2018 warrants further investigation. Performance is concentrated in key product categories (Technology, Office Supplies) and specific regions (East, West, New York City). A critical challenge identified is persistent negative profitability in certain product lines, likely influenced by aggressive discounting and/or high Cost of Goods Sold (COGS). This report integrates insights from both Marketing Specialist and Data Scientist perspectives to offer actionable recommendations for optimized financial health and sustained growth.


# 2. Key Performance Indicators (KPIs)

- Total Sales: $2,297,355

- Total Profit: $286,347

- Profit Ratio: 1.205

- Average Sales per Order: $230

- Average Profit per Order: $29

- Overall Profit Margin: 12%

- Total Units Sold: 37,873

# 3. Sales & Profit Performance Over Time (2015-2018)
- **Fluctuating Growth Trajectory (2015-2018):** Overall positive but inconsistent sales and profit trends.

- **Mid-Period Peak Performance (2017 Q3):** Achieved highest quarterly performance at **~$30.09K**.

- **Significant 2018 Q4 Decline:** Sharp drop to **~$9.14K**, contrasting prior growth.

- **Actionable Insight:** Requires further analysis to understand drivers of strong mid-period growth and recent decline.

# 4. Geographic Sales Distribution: Sales by State
- **Concentrated Sales Regions:** Sales volume is notably concentrated in specific geographic clusters, particularly in the Northeastern and West Coast (California, Washington) regions of the U.S.

- **Varying State-Level Performance:** There's a clear disparity in sales performance across states, with several states exhibiting significantly higher sales volumes (represented by larger circles) compared to the majority.

- **Sparse Central U.S. Activity:** Sales activity appears relatively sparse across the central United States, indicating potential untapped markets or lower penetration in these areas.

- **Regional Dominance:** The visual data suggests that sales are heavily driven by a few dominant states or metropolitan areas within the identified high-performance regions.

# 5. Revenue Share by Customer Segment
- **Consumer Segment Dominance:** The Consumer segment accounts for the largest share of revenue at **50.6%**, indicating it's the primary revenue driver.

- **Significant Corporate Contribution:** The Corporate segment contributes a substantial **30.7%** of total revenue, making it the second most impactful segment.

- **Lower Home Office Share:** The Home Office segment represents the smallest portion of revenue at **18.7%.**

- **Segmented Revenue Focus:** Over **80%** of revenue is derived from the Consumer and Corporate segments, highlighting these as core target groups.

# 6. Most Profitable Product Categories
- **Technology Leads Profitability:** Technology is the most profitable category, generating significantly higher profit compared to others.

- **Strong Office Supplies Contribution:** Office Supplies is a substantial contributor to profit, closely following Technology.

- **Lower Furniture Profitability:** Furniture shows considerably lower profit generation compared to Technology and Office Supplies.

- **Category Profit Disparity:** There's a clear disparity in profit contribution across categories, with Technology and Office Supplies being the primary profit drivers.

# 7. Top 10 Manufacturer by Total Sales
- **"Other" Category Dominance:** A collective group of lower-volume manufacturers category significantly leads in total sales, surpassing individual manufacturers.

- **Top Tier Performance:** Hon and Global are the leading named manufacturers, demonstrating substantial sales contributions.

- **Long-Tail Distribution:** A considerable drop-off in sales volume is observed after the top few manufacturers, indicating a long-tail distribution where many smaller manufacturers contribute less individually.

- **Key Manufacturer Contribution:** The top 5-6 manufacturers (excluding "Other") collectively represent a significant portion of total sales, highlighting their importance to revenue generation.

# 8. Sales Volume by Season
- **Fall Season Dominance:** The Fall season exhibits the highest sales volume, accounting for **36.6%** of annual sales.

- **Consistent Performance Across Other Seasons:** Winter **(21.2%)**, Spring **(21.3%)**, and Summer **(20.8%)** show relatively consistent and balanced sales contributions.

- **Seasonal Peak Identification:** The data clearly identifies Fall as the peak sales period, indicating strong seasonal demand.

# 9. Total Sales vs. Region
- **West Region Leads Sales:** The West region generates the highest total sales, indicating it as the primary revenue driver.

- **Significant East Region Contribution:** The East region is a strong second in total sales, showing robust market presence.

- **Lower Southern and Central Sales:** The South and Central regions contribute comparatively less to overall sales.

- **Regional Disparity:** Sales performance varies significantly by region, with a clear concentration in the West and East.

# 10. Top 10 Loss-Making Products
- **Significant Product-Level Losses:** A concentrated number of products are generating substantial negative profit, with "Cubify CubeX 3D Printer Double Head Print" leading losses at **-$8,880**.

- **Technology & Office Supplies Concentration:** Loss-making products are primarily found within Technology (e.g., 3D Printers, Laser Printers) and Office Supplies/Furniture (e.g., various tables, binding systems) categories.

- **Urgent Profitability Review:** The magnitude of individual product losses necessitates an immediate review of pricing, discounting, and/or cost structures for these specific items.

# 11. Discount vs. Profit Correlation
- **Weak Negative Correlation:** The R-squared value of 0.048 indicates a very weak negative correlation between Discount and Profit, suggesting that only **4.8%** of the variance in profit can be explained by discount variations.

- **Scattered Data Points:** The scatter plot shows widely dispersed data points, reinforcing the minimal linear relationship between these two variables.

- **Limited Predictive Power:** Discount alone is a poor predictor of profit outcomes, implying other factors significantly influence profitability.

# 12. Recommendations
Based on the integrated analysis the following recommendations are proposed:

- **Strategic Profitability Intervention for Loss-Making Products:**
Conduct a granular, product-specific root cause analysis for the top loss-making items. This involves deep dives into COGS, supply chain inefficiencies, return rates, and the specific discount application logic. Build predictive models to forecast profitability under various pricing and discount scenarios.
Immediately review and revise pricing strategies and discount policies for identified loss-making products. Implement stricter controls on maximum discount percentages. Explore alternative promotional strategies (e.g., bundling with profitable items, value-added services) instead of aggressive price reductions. Consider strategic discontinuation for persistently unprofitable products.

- **Optimize Seasonal & Regional Marketing Spend:**
Develop predictive models for seasonal demand forecasting to optimize inventory and resource allocation, especially for the Fall peak. Analyze sales data by sub-region within the Central and South U.S. to identify specific pockets of opportunity.
Capitalize on the strong Fall season with intensified marketing campaigns and product launches. Develop targeted campaigns for underperforming regions (Central, South U.S.) focusing on localized messaging and distribution channels. Allocate marketing budget more efficiently by re-evaluating ROI in lower-performing geographic areas.

- **Enhance Customer Segment Engagement:**
Further segment Consumer and Corporate groups based on purchasing behavior, value, and loyalty. Develop customer churn prediction models for each segment.
Tailor marketing messages and product offerings specifically for the dominant Consumer and Corporate segments. Develop loyalty programs for high-value customers within these segments. Explore A/B testing for different marketing approaches to optimize conversion and retention.

- **Deepen Profitability Drivers Analysis:**
Move beyond simple correlation for profit analysis. Implement multivariate regression or machine learning models to identify the key drivers of profit (e.g., product features, customer demographics, sales channel, operational costs) and quantify their impact. This will provide a more robust understanding of profitability beyond just discount.
Utilize insights from advanced profitability models to inform pricing, product development, and promotional strategies, ensuring that marketing efforts are aligned with maximizing profitable growth rather than just sales volume.
