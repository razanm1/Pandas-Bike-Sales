# Data Analysis of Amazon Products

![download](https://github.com/user-attachments/assets/8fc29671-d89f-4eb9-bfba-d50ebb232a22)

### Project Review 
This project aims to analyze a dataset related to Amazon products, which contains key information about each product, such as the ASIN number, title, price, list price, ratings, reviews, best-selling status, and other sales-related data such as Amazon Prime shipping and Amazon's Choice. The goal of this analysis is to extract valuable insights from the data to assist in making strategic decisions regarding products on Amazon. The available data includes: ASIN, title, price, list price, rating, number of reviews, sales in the past month, whether the product is a bestseller, whether it is eligible for Amazon Prime shipping, if it is Amazon's Choice, whether it has sustainability features, the number of available offers, the type of Amazon's Choice, brand, and delivery dates including the fastest delivery options.


### Tools 
- Python - Using pickle, matplotlib.pyplot,  pandas
- Excel - cleaning data
- Power Bi - creatig reports

### Data Source 
- [Click here](https://www.kaggle.com/mohammedalsubaie)
### Data Cleaning / Preparation
- 127 duplicates were found and removed in EXCEL AND PYTHON 
- I replaced the 'K' in  sold_past_month with '000' to convert shorthand values (like 5K) into their full numeric form (5000) in EXCEL.
- Standardizing Dates in EXCEL.
- Handling Missing Data.
- Setting up relationships in Power BI involves creating a star schema by establishing connections between the Fact Table and the Dimension Tables.


  ![-](https://github.com/user-attachments/assets/c41a0708-541e-4553-8420-dc970e0d51fa)

### Python Code
![fafbdaa9-6150-433e-9009-11774a3918a7](https://github.com/user-attachments/assets/f043e388-dce8-4d05-9c66-6c55110e7749)
![e28daffd-c4fa-4ebf-be11-2076ec4e606d](https://github.com/user-attachments/assets/e4b08b6a-d7e0-4cc0-b2ce-8de6c087fde8)


### Data visualization





https://github.com/user-attachments/assets/b9b97f64-a739-4e93-be1a-766d6c9d21f7



### Results/Findings

- Brand Variety: There are 32 brands represented in the dataset, indicating a diverse range of sellers and product offerings. However, the number of brands decreased slightly from 32 to 30 in the last month.

- Product Portfolio: The total number of products increased from 837 to 938 in the last month, showing a positive trend in product variety and availability.

- Product Ratings: The number of products with a perfect 5-star rating is relatively low, with only 28 products achieving this rating. However, there is a substantial number of products with a 4.5-star rating (162 products), which suggests that a significant portion of products perform well in terms of customer satisfaction.

- Customer Preferences: The number of favorite products has remained consistent at 6, indicating that certain products have become particularly popular or are highly recommended by customers.

- Revenue Insights: The total revenue of 7 million indicates that the analyzed products are performing well in terms of sales, suggesting strong demand and profitability.


