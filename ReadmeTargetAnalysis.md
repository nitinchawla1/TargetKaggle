Target Case Study: Analyzing Order Data
This repository contains a case study focused on analyzing an Target dataset. The dataset includes information about customers, orders, and various attributes related to the ordering process. The goal of this analysis is to gain insights into the trends, patterns, and characteristics of orders placed through the e-commerce platform, with a specific focus on the Brazil region.

Dataset
The dataset used for this analysis consists of information related to customers, orders, payments, and deliveries. The exploratory analysis covers various aspects of the dataset, including data types, time ranges, geographical distribution, order values, delivery times, and payment methods.

Exploratory Analysis
The exploratory analysis encompasses the following key questions:

Determine the time range between which the orders were placed.
Count the cities and states of customers who ordered during the specified period.
Identify any growing trend in the number of orders placed over the past years.
Analyze monthly seasonality in terms of the number of orders.
Determine the preferred time of day for Brazilian customers to place orders.
Dawn: 0-6 hrs
Morning: 7-12 hrs
Afternoon: 13-18 hrs
Night: 19-23 hrs
Explore the evolution of e-commerce orders in the Brazil region.
Calculate the month-on-month number of orders placed in each state.
Visualize the distribution of customers across all states.
Analyze the economic impact by examining order prices, freight costs, and other factors.
Calculate the percentage increase in order costs from 2017 to 2018 (Jan to Aug).
Calculate the total and average order value for each state.
Calculate the total and average freight value for each state.
Analyze sales, freight, and delivery time:
Calculate the delivery time for each order.
Calculate the difference between estimated and actual delivery dates for each order.
Delivery Time Analysis
The delivery time analysis includes the following calculations:

time_to_deliver: Order delivered customer date - Order purchase timestamp
diff_estimated_delivery: Order estimated delivery date - Order delivered customer date
The analysis identifies the top 5 states with the highest and lowest average freight value, as well as the top 5 states with the fastest and slowest delivery times compared to the estimated delivery date.

Payment Analysis
The payment analysis involves examining the following aspects:

Month-on-month number of orders placed using different payment types.
Number of orders placed based on payment installments paid.






