# LR_Delivery_Time_Prediction_Kriti
LR Delivery Time Prediction Model

The objective of this assignment is to build a regression model that predicts the delivery time for orders placed through Porter. The model will use various features such as the items ordered, the restaurant location, the order protocol, and the availability of delivery partners.

The key goals are:

Predict the delivery time for an order based on multiple input features
Improve delivery time predictions to optimiae operational efficiency
Understand the key factors influencing delivery time to enhance the model's accuracy
Data Pipeline
The data pipeline for this assignment will involve the following steps:

Data Loading
Data Preprocessing and Feature Engineering
Exploratory Data Analysis
Model Building
Model Inference
Data Understanding
The dataset contains information on orders placed through Porter, with the following columns:

Field	Description
market_id	Integer ID representing the market where the restaurant is located.
created_at	Timestamp when the order was placed.
actual_delivery_time	Timestamp when the order was delivered.
store_primary_category	Category of the restaurant (e.g., fast food, dine-in).
order_protocol	Integer representing how the order was placed (e.g., via Porter, call to restaurant, etc.).
total_items	Total number of items in the order.
subtotal	Final price of the order.
num_distinct_items	Number of distinct items in the order.
min_item_price	Price of the cheapest item in the order.
max_item_price	Price of the most expensive item in the order.
total_onshift_dashers	Number of delivery partners on duty when the order was placed.
total_busy_dashers	Number of delivery partners already occupied with other orders.
total_outstanding_orders	Number of orders pending fulfillment at the time of the order.
distance	Total distance from the restaurant to the customer.

Git Hub Link is as below:
https://github.com/kkrkashyap/LR_Delivery_Time_Prediction_Kriti.git