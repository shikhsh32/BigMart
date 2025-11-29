# BigMart
Project Overview:
BigMart has collected 2013 sales data for 1559 products across 10 stores.
The objective of this project is to build a predictive model that estimates the sales of products for different outlets based on historical data and product/store attributes.

This model will help BigMart understand key factors influencing sales and optimize business decision-making.

DataSet Information:
The dataset consists of two files:
Train.csv : 8523 records with input features + target coloumn ( Item_Outlet_Sales )
Test.csv: 5681 records with input featues ( predict Outlet Sales)

Key Features: 

Item_Identifier (Unique product ID)
Item_Weight (Weight of product)
Item_Fat_Content(Low Fat / Regular)
Item_Visibility ( Product visibility in store )
Item_Type (Product category)
Outlet_Identifier	(Unique store ID)
Outlet_Size (Size of outlet (Small/Medium/High) )
Outlet_Location_Type(Tier of the city)
Outlet_Type (Grocery / Supermarket)
Item_Outlet_Sales(Target variable)

Data Preprocessing & Feature Engineering: 
- Handled null values using mean, median, and mode
- Replaced zero values in Item_Visibility with mean
- Normalized Item_Fat_Content values

Tech Stack: 
                    
Python (Core programming)
Pandas, NumPy ( Data processing )
Google Colab ( Development environment )
GitHub ( Version control )
