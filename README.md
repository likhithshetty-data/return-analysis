E-commerce return rate reduction
The data swt which i have used included 1000 synthetic order records with fields like order_is,product_id, customer_id, and product details like category, supplier, price and order-level fields like order_date,delivery_days,region.
Python
Using pyhton i found that certain product categories and specific suppliers had significantly higher return rates, customers from some regions also showed higher tendencies of return products.
I used logistic regression model to [redict the probability of return
the model output was a probability score for each order the product with high score were labeled as high risk. we exported there risky orders as a CSV.
Power Bi Dashboard
KPI Cards for overall return stats
Bar charts showing return % by supplier and category
Slicers to filter data by Category, Supplier, Region
Pie chart to analyse  the return reasons

Key Takeaways
Categories like Clothing and Electronics have higher return rates
Some suppliers consistently have products with high return probabilities
Fast delivery and mid-range prices reduce return chances

