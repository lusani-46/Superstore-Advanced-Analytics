**Superstore Advanced Analytics 📊**

**Turning Data into Actionable Business Insights**

This project is a deeper analysis of the Superstore sales dataset, building on the executive dashboard developed in Week 2 of the AnalystLab Africa Data Analytics Internship Programme.

The focus of this analysis is to understand what is driving profitability, where the business is losing money, and what areas may require further attention.

At a high level, the business generated $2.30M in sales, $286.40K in profit, and a 12.47% profit margin between 2014 and 2017. Looking deeper into the data, however, reveals several specific areas that are affecting profitability.

**🎯 Project Objectives**

The main objectives of this analysis were to:

Investigate the causes of low profitability in specific product sub-categories.
Analyse the relationship between discount levels and profit margins.
Identify loss-making states and investigate their performance.
Compare customer segments using both revenue and profitability.
Compare sales growth with profit growth over time.
Develop practical recommendations based on the findings.

**📊 Dashboard**

The Power BI file contains the original Week 2 executive dashboard together with a new Advanced Analysis page.

The Advanced Analysis page includes:

7 KPI cards
4 interactive visuals
Year slicer
Region slicer
Profitability analysis
Discount analysis
Customer segment analysis
Regional and state analysis

Dashboard exports are available in the Dashboard Export3/ folder.

**🔑 Key Findings**
1. Furniture's Low Profitability is Concentrated in Two Sub-Categories

Furniture has an overall profit margin of 2.5%.

Further analysis shows that the main contributors to this weak performance are:

Tables: -8.6% margin
Bookcases: -3.0% margin

Chairs and Furnishings perform better.

Insight: The profitability problem is concentrated in specific Furniture sub-categories rather than the entire category.

2. Higher Discounts are Associated with Negative Margins

The discount analysis shows that discount bands above 20% consistently have negative average margins in the dataset.

At discount levels above 50%, the average loss becomes particularly severe.

Insight: High discount levels are associated with significant margin pressure and should be monitored carefully.

3. Five States are Loss-Making

The analysis identified five states with negative overall profit:

Texas
Ohio
Pennsylvania
Illinois
North Carolina

This provides a more detailed view than looking at regional performance alone.

Insight: Regional averages can hide problems at state level, making it important to investigate individual locations.

4. Consumer Generates the Most Revenue but Has the Lowest Margin

The Consumer segment contributes approximately 50.6% of total revenue, making it the largest customer segment.

However, it has the lowest profit margin at 11.5%.

The Home Office segment is smaller by volume but has the highest margin at 14.0%.

Insight: The customer segment generating the most revenue is not necessarily the most profitable, so both revenue and margin should be considered when evaluating customer performance.

5. Sales Growth is Outpacing Profit Growth

In 2017:

Sales growth: +20.4%
Profit growth: +14.2%

Sales therefore grew faster than profit.

Insight: This is an important trend to monitor because continued growth in sales without similar growth in profit could indicate increasing pressure on profitability.

**💡 Recommendations**

Based on the analysis, I recommend the following actions:

1. Review High-Discount Orders

Introduce clearer guidelines for discounts above 20% and evaluate whether heavily discounted orders remain profitable.

2. Investigate Tables and Bookcases

Review pricing, costs, discounts, shipping, and customer/order characteristics to better understand the losses in these sub-categories.

3. Investigate the Five Loss-Making States

Conduct a more detailed analysis of Texas, Ohio, Pennsylvania, Illinois, and North Carolina to identify factors contributing to their negative profitability.

4. Evaluate Customer Segments Using Both Revenue and Profit

Consumer generates the largest share of revenue, but its margin is lower than the other segments. Customer performance should therefore be evaluated using both sales contribution and profitability.

5. Monitor Sales and Profit Growth Together

Track sales growth and profit growth as complementary KPIs to identify whether the business is growing profitably over time.

**🛠️ Tools Used**
Power BI Desktop – Data analysis, data modelling, Power Query, DAX, KPI development, and interactive dashboards.
Microsoft Word – Detailed analysis, business insights, and recommendations.

**📁 Repository Structure**
File / Folder	Description
Superstore Sales Analysis3.pbix	Power BI file containing the Executive Dashboard and Advanced Analysis pages.
Advanced_Data_Analysis.docx	Detailed analysis covering sales, profit, categories, sub-categories, regions, states, customer segments, discounts, and seasonality.
Business_Insights_and_Recommendations_Report.docx	Report containing key insights, risks, opportunities, and recommendations.
DAX_Measures_Documentation.docx	Documentation of the 7 DAX measures used in the dashboard.
Dashboard Export3/	PNG and PDF exports of the dashboard pages.

**🧩 DAX Measures**

I created 7 DAX measures to support the KPI and profitability analysis.

The measures are:
Total Sales
Total Profit
Profit Margin
Total Orders
Avg Sales per Order
Sales Growth %
Loss-Making Orders

The formulas, definitions, and explanations for these measures are documented in:

DAX_Measures_Documentation.docx

**📚 Related Work**

This project builds on my Week 2 Superstore Power BI project, which focused on business understanding, data preparation, exploratory analysis, and an initial executive dashboard.

Week 2 Project:
Superstore-PowerBI

👤 About the Author
Lusani Judith Nempumbuluni
AnalystLab Africa — Data Analytics Internship Programme
This project demonstrates practical experience in:
Data Analysis · Business Intelligence · Power BI · DAX · KPI Development · Profitability Analysis · Customer Segmentation · Data Storytelling

If you find this project useful, feel free to ⭐ the repository.
