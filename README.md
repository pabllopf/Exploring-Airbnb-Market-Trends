# Exploring-Airbnb-Market-Trends
Apply your importing and cleaning data and data manipulation skills to explore New York City Airbnb data.

# Description:
New York City has a variety of Airbnb listings to meet the high demand for temporary lodging for travelers, with several different price levels, room types, and locations.

Practice your skills in importing and cleaning data and data manipulation and report insights to a real estate start-up!

# Project Instructions
As a consultant working for a real estate start-up, you have collected Airbnb listing data from various sources to investigate the short-term rental market in New York. You'll analyze this data to provide insights on private rooms to the real estate company.

There are three files in the data folder: airbnb_price.csv, airbnb_room_type.xlsx, airbnb_last_review.tsv.

What are the dates of the earliest and most recent reviews? Store these values as two separate variables with your preferred names.
How many of the listings are private rooms? Save this into any variable.
What is the average listing price? Round to the nearest two decimal places and save into a variable.
Combine the new variables into one DataFrame called review_dates with four columns in the following order: first_reviewed, last_reviewed, nb_private_rooms, and avg_price. The DataFrame should only contain one row of values.

Last edit was 4 months ago
1
![image](https://github.com/user-attachments/assets/57b147c3-45c1-4870-917d-554c7a8e7cce)

2
​
3
Welcome to New York City, one of the most-visited cities in the world. There are many Airbnb listings in New York City to meet the high demand for temporary lodging for travelers, which can be anywhere between a few nights to many months. In this project, we will take a closer look at the New York Airbnb market by combining data from multiple file types like `.csv`, `.tsv`, and `.xlsx`.
4
​
5
Recall that **CSV**, **TSV**, and **Excel** files are three common formats for storing data. 
6
Three files containing data on 2019 Airbnb listings are available to you:
7
​
8
**data/airbnb_price.csv**
9
This is a CSV file containing data on Airbnb listing prices and locations.
10
- **`listing_id`**: unique identifier of listing
11
- **`price`**: nightly listing price in USD
12
- **`nbhood_full`**: name of borough and neighborhood where listing is located
13
​
14
**data/airbnb_room_type.xlsx**
15
This is an Excel file containing data on Airbnb listing descriptions and room types.
16
- **`listing_id`**: unique identifier of listing
17
- **`description`**: listing description
18
- **`room_type`**: Airbnb has three types of rooms: shared rooms, private rooms, and entire homes/apartments
19
​
20
**data/airbnb_last_review.tsv**
21
This is a TSV file containing data on Airbnb host names and review dates.
22
- **`listing_id`**: unique identifier of listing
23
- **`host_name`**: name of listing host
24
- **`last_review`**: date when the listing was last reviewed
1
# Import necessary packages
2
import pandas as pd
3
import numpy as np
4
​
5
# Begin coding here ...
6
# Use as many cells as you like
