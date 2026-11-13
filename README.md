# E commerce Sales Analyisit
I analyzed 100,000 e-commerce orders from 2020-2024. My Main Questions were; What drives

##Steps I Took
1. Cleaning: checked for missing values and dulpicates- found 0 missing valuesand 0 duplicate. Coverted OrderDate t0 datetime.
2. Manipulation: Used groupby and sort_valuesto aggreaye salesby category, product, state. payment method, and month.
3. Visualtions: Creted 3 charts- mouthly trend linecharts, sales by state bar charts, sales by payment method bar chart.
4. Staristical Analysis: Calculated descriptive statistics (mean, median, std) and correlation between Discount, Quantity, andTotalAmount.

## Key Insights
-Average order is $918.26 with an average of 3 items per order.
-A11 categories and products sell almostequally- no singlewinner.
-TX(`~$23M) and CA (~$18M) dominate sales. All other staes are ~$4M each.
-Credit Card is the top payment method at ~$32M in sales.
-74.6% of orders are delivered, only 6% are returned/cancelled.
-Mouthly sales are flat from 202-2024 between $1.35M-$1.65M- stable but no growth.
-Discounts do not work: Correlation between Discount and Quantity is ~0, and Discount vs TotalAmount is -0.11. Discountjust lower revene without increasing items bought. Quantity vs Total Amount is 0.59- Selling more items is whatincreasesrevene


# Recommendation
Stop relying on big discounts. Focus on getting customers in TX and CA to add more items to their cart, and try to grow sales in other state, since overall sales are flat.

