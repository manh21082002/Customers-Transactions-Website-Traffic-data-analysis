# Customers-Transactions-Website-Traffic-data-analysis
Data Source: Momo's Data Analyst Test

Description:
  Company A specializes in selling fashion products and has stores in the capitals of various countries: London (UK), Paris (France), Milan (Italy), and Berlin (Germany). Customers can make purchases directly at the physical stores or online.
The company also maintains an online sales website with information and images of its products. In many cases, website traffic increases when new products are added.

Key Questions:
-  Does website traffic affect revenue?
- Which products generate pageviews and revenue?
- What are the customer segments?
  
Data:
- Customers & Transactions: Information about customers and their transactions, both online and in-store.
- Website Traffic: Website traffic data for each product page.
  
Technology Used: Python

Results:
- Website traffic and revenue have a positive correlation, showing a clear linear relationship, especially over a certain period of time. The larger the time unit, the more pronounced the positive correlation.

#### CORRELATION COEFFICIENTS
![image](https://github.com/manh21082002/Customers-Transactions-Website-Traffic-data-analysis/assets/100988312/995f3a44-1d44-4079-8aa9-764f1effee15)

#### LINE PLOT PAGEVIEW and REVENUE by Day
![image](https://github.com/manh21082002/Customers-Transactions-Website-Traffic-data-analysis/assets/100988312/cc256e63-b64e-4540-a8d7-08e6c0b00a43)

- Website traffic does not immediately impact revenue but has a delayed effect over time. This can be explained by the fact that customers may not make purchases immediately after visiting the website but do so after multiple visits.

#### LINE PLOT PAGEVIEW and REVENUE by WEEK
![image](https://github.com/manh21082002/Customers-Transactions-Website-Traffic-data-analysis/assets/100988312/3b232c04-41b6-4632-babc-650be118d50e)

- Seven out of the top ten highest-revenue products also have the highest website traffic.

#### TOP 10 iterm highest-PAGEVIEW and TOP 10 iterm highest-REVENUE
![image](https://github.com/manh21082002/Customers-Transactions-Website-Traffic-data-analysis/assets/100988312/9fbc61bb-2e2b-4a5e-963b-404d26a7c4aa)

- Using the RFM model (Recency, Frequency, Monetary), customers can be segmented into four main groups: New Customers, Old Customers, Loyal Customers, and Formerly Loyal Customers.
![image](https://github.com/manh21082002/Customers-Transactions-Website-Traffic-data-analysis/assets/100988312/d2b858ed-f645-4187-9e14-a45966f7b66b)
![image](https://github.com/manh21082002/Customers-Transactions-Website-Traffic-data-analysis/assets/100988312/999a4fa9-f9a7-4aa8-a38f-99ecdf5598bb)
![image](https://github.com/manh21082002/Customers-Transactions-Website-Traffic-data-analysis/assets/100988312/1c584336-64ac-410e-8ffc-da28ef2e455b)

- It's challenging to reach the Old Customer segment, so the focus should be on engaging with the other three segments, especially Loyal Customers. However, it's essential not to neglect New Customers and Formerly Loyal Customers.
