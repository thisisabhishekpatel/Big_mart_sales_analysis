<h1>1. Business Problem </h1>

<h2> 1.1 Sales Prediction for Big Mart Outlets </h2>

<p style='font-size:18px'><b> Description </b></p>
<p>
Sales prerdiction is one of the fundamental problems of any business. It is almost impossible to forecast perfectly but even a forecast within 10% of your actual results can positively impact your business. As such, it should be performed consistently for every business, regardless of size. .<br />
<br />
Why we need to do sales forecasting
1. To Predict And Plan For Demand Throughout The Year
2. To Make Wise Business Investments
3. To Improve Your Sales Process
4. To Improve Company Morale.<br />
<br />
</p>

<p style='font-size:18px'><b> Problem Statemtent </b></p>
* The data scientists at BigMart have collected 2013 sales data for 1559    products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and predict the sales of each product at a particular outlet.

* Using this model, BigMart will try to understand the properties of products and outlets which play a key role in increasing sales.

* Please note that the data may have missing values as some stores might not report all the data due to technical glitches. Hence, it will be required to treat them accordingly. 


<h2> 1.4 Real World / Business Objectives and Constraints </h2>

1. Predict the item outlet sales.
2. No strict latency constraints.

<h1>2. Machine Learning problem </h1>

<h2> 2.1 Data </h2>

<h3> 2.1.1 Data Overview </h3>

Refer: https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/

* Item_Identifier	Unique product ID
* Item_Weight	Weight of product
* Item_Fat_Content	Whether the product is low fat or not
* Item_Visibility	The % of total display area of all products in a store allocated to the particular product
* Item_Type	The category to which the product belongs
* Item_MRP	Maximum Retail Price (list price) of the product
* Outlet_Identifier	Unique store ID
* Outlet_Establishment_Year	The year in which store was established
* Outlet_Size	The size of the store in terms of ground area covered
* Outlet_Location_Type	The type of city in which the store is located
* Outlet_Type	Whether the outlet is just a grocery store or some sort of supermarket
* Item_Outlet_Sales	Sales of the product in the particular store. This is the outcome variable to be predicted.

<h2>2.2 Mapping the real-world problem to a Machine Learning Problem </h2>

<h3> 2.2.1 Type of Machine Learning Problem </h3>

<p> It is a regression problem  <br>

<h3>2.2.2 Performance metric </h3>

<b> Root mean squared error (RMSE)</b>: 



