# Customer-Segmentation
### Segment the Customers according to their purchase behavior.

### Dataset Link: Download Link

This is a transnational data set that contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers. The following is the description of every column in the dataset.

- InvoiceNo:	Invoice number.	Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation. 
- StockCode	 Product (item): code	Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- Description	Product (item): name	Nominal.
- Quantity:		The quantities of each product (item) per transaction. Numeric.	
- InvoiceDate:	Invoice Date and time:	 Numeric, the day and time when each transaction was generated.
- UnitPrice:		Unit price. Numeric, Product price per unit in sterling. 
- CustomerID:	 Customer number	 Nominal, a 5-digit integral number uniquely assigned to each customer.
- Country:	Country name	Nominal, the name of the country where each customer resides.

I have performed RFM (Recency, Frequency, Monetary) analysis for each customer. Also I have used these RFM columns to perform K-means clustering.
For each customer, I have three columns (Recency, Frequency, Monetary) after the RFM analysis. 

After the analysis I have prepared a Power BI report to provide insights like:
1.	Top customers on basis of RFM score.
2.	Best Customers, Big Spenders, Lost Customers, Loyal Customers, etc.
