# PowerBi_Sales_2
Back with another learning session on data analytics and visualization with Power BI. Right now in this repository I'm utilizing the superstore sales dataset to analyze some of the main findings from the dataset.

### Method
The data is contained in a Microsoft Excel file (.xlsx) which can be pulled directly and easily into Power BI. The data is clean with no empty / missing values and all of the columns are already in their correct formats. No further editing or cleaning done before importing the data into Power BI.

### Dashboard
Making charts is relatively easy and it can tell us a lot about the data itself that might be missed when looking at the raw data alone.
<img width="720" alt="image" src="https://github.com/luthfiz23/PowerBi_Sales_2/assets/159741452/f43c56ad-0612-4745-b750-272c9a665dea">

### Information and Insight
1. In 2015, the store generated more than 4M USD in sales and more than 500K USD in profit. This means the store gained around 12.5% profit from its sales, which is genrally safe but it certainly can improve.
2. The store gained more sales (and profit) in the 4th quarter. This is a proven seasonality of the store's sales since the same pattern occured since 2012.
<img width="447" alt="Sales and Profit since 2012 - 2015" src="https://github.com/luthfiz23/PowerBi_Sales_2/assets/159741452/8a36a0fc-e52a-47e0-93c4-49a14d9ff27d">
5. There are 3 main categories of products being sold in the store. Technology is the most profitable one, bringing in more than 230K USD of profit in 2015.
6. Specifically, the sub-category copiers is the most profitable one. The store sold 2642 units of copiers in 2015 and profited 104K USD from it. That means for each copiers sold, each of them brought in 39 USD on average.
7. On the other hand, the furniture category is the least profitable one. With roughly the same units of products sold as technology, furniture only generated a little less than 90K USD in 2015.
8. Tables (one of the subcategories in furniture) is the only category in sold in the store bringing in a **loss** of 30K USD.
9. Interestingly, the only market that generated profit for table sales is the Africa market which has the lowest quantity of tables ordered. Tables sold in the Asia Pacific market generated the biggest loss of 10K USD.
<img width="212" alt="image" src="https://github.com/luthfiz23/PowerBi_Sales_2/assets/159741452/4bc81d63-1f0b-4807-b0cd-1ce5526c2904">
11. Still on the topic of tables, the shipping cost for tables seems to be negatively correlated to the profit made from selling them. It's shown in the chart below that, on average, shipping tables to Africa costs 60 USD where each tables generated around 120 USD in profit.
<img width="212" alt="image" src="https://github.com/luthfiz23/PowerBi_Sales_2/assets/159741452/fd915fab-2268-4104-89e5-f796eb802b61">
12. Copiers generated more than 1000 USD of profit on average in the USCA market, which seems a little odd.
<img width="166" alt="image" src="https://github.com/luthfiz23/PowerBi_Sales_2/assets/159741452/65423d4c-e7d8-43e0-ac62-deb98352f750">
Further investigation shows that there are some outliers in the copiers sold in the USCA market, where there are 3 copiers sold at more than 10K USD and each generating around 4K to 7K USD of profit.
<img width="165" alt="image" src="https://github.com/luthfiz23/PowerBi_Sales_2/assets/159741452/d2422fed-9357-4643-9e6a-3552eb676d7e">
13. In the USCA market, the average supplies (in the Office Supplies category) failed to generate profit and bringing in a relatively small loss of 14 USD. But on the grand sceme of sales, the loss accumulated into 808 USD. Unlike the case of tables sold in Africa, this seems to not correlate directly with the shipping cost.
<img width="166 alt="image" src="https://github.com/luthfiz23/PowerBi_Sales_2/assets/159741452/7a797a3d-3648-4d33-9d60-7617371bb547">

