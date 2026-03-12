# Customers-Shopping-Behaviour-Analysis
This project analyzes customer shopping behavior to uncover patterns in purchasing habits, spending trends, and product preferences. The analysis includes data cleaning, exploratory data analysis (EDA), and visualizations to generate meaningful insights for business decision-making.
- [Project Objectives](#project-objectives)
-  [Dataset Overview](#dataset-overview)
-  [Dataset Preparation](#dataset-preparation)
-  [Dataset](#dataset)
-  [Sales Overview (Page 1)](#sales-overview-(page-1))
-  [Product and Purchases Insight (Page 2)](#product-and-purchases-insight-(page-2))
-  [Customers' Performance (Page 3)](#customers'-performance-(page-3))
-  [Strategic Recommendations](#strategic-recommendations)
-  [Conclusions](#conclusions)

  # Shoppping Behaviour And Product Ranking Analysis

# Project Objectives
- Analyze Customer Purchasing Behavior
To understand how customers shop by examining purchase frequency, spending patterns, and buying trends.
- Evaluate Product Performance
To identify the best-performing product categories and top-selling items that contribute most to overall revenue.
- Measure Business Performance
To track key metrics such as total revenue, average revenue per transaction, total customers, and average customer spending
-  Understand Customer Demographics
To analyze customer segments based on age group, gender, and location in order to identify the most valuable customer groups.
-  Identify Sales Trends and Patterns
To explore seasonal sales trends and understand how different periods of the year influence purchasing behavior.
-  Examine Payment Preferences
To determine the most commonly used payment methods among customers.
-  Support Data-Driven Decision Making
To provide clear insights that help businesses improve marketing strategies, product planning, and inventory management.
-  Improve Product and Inventory Strategy
To identify popular product attributes such as size and item type so businesses can optimize stock levels and meet customer demand.

# Dataset Overview
Dataset contains information about customer demographics, purchasing patterns, product preferences, and engagement behavior. The dataset is designed to help analyze how different factors such as age, gender, product category, discounts, and subscription status influence customer spending and loyalty.
The dataset includes 3,900 customer records with multiple attributes describing customer transactions and behaviors. Each record represents a purchase made by a customer and includes details about the product purchased, the amount spent, payment method, purchase frequency, and customer review ratings.
The data provides valuable insights into customer segmentation, revenue drivers, shopping habits, and engagement levels, making it suitable for building a business intelligence dashboard that supports data-driven decision making.
Key areas of analysis supported by this dataset include:
•	Customer demographics and segmentation
•	Sales and revenue performance
•	Product category performance
•	Customer engagement and loyalty
•	Discount and promotion impact
•	Payment method preferences
•	Customer satisfaction through review ratings
Overall, this dataset enables analysts to explore patterns in consumer behavior, identify opportunities for improving customer retention, and support strategic decisions in marketing, sales, and product management.

# Dataset Preparation
1.	Data Import: The dataset was imported into the analytics environment (Power BI) as a CSV file. Each row represents a customer transaction, while columns contain demographic, transactional, and behavioral information.
2.	Creation of DAX and KPIs.
3.	Checked for blank columns and rows, duplicate or errors (none identified).

# Dataset
[Uploading shopping_behavior_updated (1).csv…]()

# Sales Overview (Page 1)
- Key KPI insight
REVENUE PERFORMANCE
. Total Revenue: $ 233,081
. Average Revenue per customer: $ 59.76
Revenue distribution is relatively balanced across purchase frequency groups.
Insights: The company benefits from consistent purchasing patterns rather than heavy dependence on one customer segment.

- Revenue by Purchase Frequency
1.	Highest Revenue comes from every three months ($ 35.1k)
2.	Closely followed by annually ($ 34.4k) and quarterly ($33.8k).
3.	Weekly purchases generate the least ($31.8k) but the gap is small.
Insights: Customers who purchase less frequently actually generate slightly more revenue than frequent weekly buyers.

Recommendations: Introduce loyalty and subscription incentives to increase purchase frequency without reducing basket value.

- Revenue by Category
1.	 Clothing: $104k (highest)
2.	Accessories: $74k
3.	Footwear: $36k
4.	Outerwear:$19k (lowest)
Insights: Clothing contribute nearly 45% of total revenue, making it the core revenue driver.
Business implications: 
1.	Expand clothing inventory and promotions.
2.	Bundle low performing categories (outerwear) with clothing.
3.	Cross sell accessories with clothing items.
   
- Top 5 Revenue Generating Items
1.	Blouse -$10.4k
2.	Shirt -$10.3k
3.	Dress -$10.3k
4.	Pants -$10.1k
5.	Jewelry -$10.0k
Insights: Top performing items are primarily clothing products, reinforcing the category dominance.

Recommendations: 
1.	Promote bundles (blouse + jewelry)
2.	Ensure constant stock availability of top 5 items.
3.	Use these items for marketing campaigns.

![SALES OVERVIEW](https://github.com/user-attachments/assets/bb5ba210-2646-4a0c-ab03-27cae361b84f)

# Product and Purchases Insight (Page 2)

Total Revenue: $233,081
. Best Category: Clothing ($ 104.26k)
.  Average Reviews Rating: 3.75
. Number of Unique Items: 25

- Revenue by Season
Seasonal breakdown observations:
Spring ($28k clothing) - Highest clothing sales
Winter ($27k clothing) - Strong seasonal demand
Fall ($26k clothing) – Stable
Summer ($23k clothing) – Slight dip
Insights:
1.	Clothing performs well year round.
2.	Seasonal impact exists but is not extreme
3.	Outerwear increases slightly in winter/ fall as expected
Recommendation:
1.	Push seasonal promotions (e.g Outerwear in winter).
2.	Offer summer fashion bundles to boost summer revenue.

- Category Performance Insights
. Clothing dominates by generating 45% of total revenue, performs strongly across all seasons and clearly the core revenue driver.
. Accessories is the second best performer with stable contribution across seasons ads good cross selling potential with clothing.
. Footwear and Outerwear are moderate but have consistent performance.
. Outerwear is the lowest contributor.
Recommendation:
The company is highly dependent on clothing sales. Diversifying growth into Accessories and Footwear could reduce category risk.

- Sales by Payment Method
1.	Credit Card - $40k
2.	Paypal - $40k
3.	Cash - $39k
4.	Debit Card - $39k
5.	Venmo - $37k
6.	Bank Transfer - $37k
Insights: Payment usage is evenly distributed.
This means Customers are comfortable with multiple payment options and no strong dependency on a single payment channel.
Recommendation:
1.	Offer small incentives for digital payments to reduce cash handling.
2.	Partner with digital payment providers for cashback campaigns.

- Purchases by size
Medium size dominates significantly with 44k.
Recommendations:
1.	Maintain higher inventory levels for size M
2.	Avoid overstocking XL and S.
3.	Use sales/discounts to clear slower sizes.

- Top Purchase Counts
1.	Jewelry (Gray, M) - 262 purchases
2.	Coat ( Violet , M)- 228
3.	Skirt (Black , L)- 224
4.	Handbag (Charcoal , M) -224
5.	Pants (Charcoal , M) -218
  
Observations:
-	Medium size appears repeatedly.
-	Neutral colours (Gray, Black, Charcoal) performs best.
-	Accessories like Jewelry and handbags are high volume items.
Recommendation:
1.	Stock more neutral coloured products.
2.	Promote bundles (Handbag + Jewelry).
3.	Focus marketing on best-selling colours.
   
![PRODUCT](https://github.com/user-attachments/assets/c97da8a1-994a-4e48-a917-f3e885914579)

# Customers' Performance (Page 3)

Total Customers: 3.9k
Total Orders: 4k
Average Spend per Customer : $60
Repeat Customer Rate: 1.00
This shows a strong customer retention level, where most customers return to make additional purchases.

- Sales by Age
1.	25-34 and 45-54 age group generate the highest sales.
2.	Customers aged 18-24 contribute the least revenue among active buyers.
3.	Middle-aged customers (25-54) dominate spending.
4.	Customers in the working class age range have the highest purchasing power.
Recommendation:
1.	Target 25-54 age group with premium offers and loyalty programs.
2.	Use student discounts or youth campaigns to grow the 18-24 segment.
  
- Sales by Gender
Male customers (67.74%) contribute over two-thirds of total revenue. The business appears to attract more male buyers or higher male spending.
Recommendation:
1.	Introduce marketing campaigns targeting female customers.
2.	Expand female-oriented product offerings.
  
- Sales by Discount
More sales occur without discounts ($134k) and discounts still drive a significant portion of sales.
Insights: Customers are willing to purchase even without price reductions, suggesting: 
1.	Strong product value.
2.	Brand or product loyalty.
Recommendation:
1.	 Use discounts strategically during slow sales period.
2.	Avoid over-discounting to maintain profit margins.
   
- Sales by Subscription
More revenue comes from non-subscribed customers (73%).
The subscription program may be underutilized.
Recommendation:
1.	Introduce exclusive benefits for subscribers.
2.	Offer early product access, discount rewards, free-shipping.
By doing these could help increase loyalty and predictable profit.

- Sales by Location
Sales distribution across states is relatively balanced and no single state dominates overall revenue.
Montana - $5.8k, Illinois - $5.6K, California - $5.6k, Idaho - $5.6k, Nevada - $5.5k
The company has a diverse geographic customer base.
Recommendation:
1.	Identify high-potential states for regional marketing campaigns.
2.	Expand advertising in top-performing locations.


![CUSTOMER PERFORMANCE](https://github.com/user-attachments/assets/93d3a520-fbab-4ea7-b4fb-c839ebea9305)

# Strategic Recommendations
1.	Introduce personalized promotions based on purchase frequency.
2.	Increase marketing focus on clothing (core revenue driver).
3.	Improve customer experience to raise review ratings.
4.	Optimize inventory around size M and neutral colors.
5.	Increase Female customer engagement.
6.	Expand subscription program.

# Conclusions
The analysis shows that the business generated $233k in revenue from 3.9k customers with clothing emerging as the top-performing category. Products such as Blouses, Shirts and Dresses drive the highest sales. Customer purchases are consistent across different buying frequencies, with medium-sized items being the most demanded. Sales are also evenly distributed across payment methods and seasons, indicating stable customer behavior. A dominant middle-age purchasing segment, strong repeat customer behavior, high male spending contribution. Overall, the insights highlight opportunities to improve customer satisfaction, target younger demographics, optimize inventory and grow lower-performing product categories.
