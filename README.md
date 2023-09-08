# Flight-price-prediction

## Introduction

The objective of this study is to analyze the flight booking dataset obtained from the "Ease My Trip" website. We aim to conduct various statistical hypothesis tests and utilize the 'Linear Regression' statistical algorithm to gain meaningful insights from the data. "Ease My Trip" is an online platform for booking flight tickets, making it a valuable source for understanding passenger behavior and pricing dynamics.

### Research Questions

Our study aims to answer the following research questions:

a) Does the price vary with Airlines?

b) How is the price affected when tickets are bought just 1 or 2 days before departure?

c) Does the ticket price change based on the departure time and arrival time?

d) How does the price change with variations in the source and destination?

e) How does the ticket price vary between Economy and Business class?

## Data Collection and Methodology

We used the Octoparse scraping tool to extract data from the "Ease My Trip" website. The data was collected in two parts: one for economy class tickets and another for business class tickets. In total, we extracted 300,261 distinct flight booking options from the site. Data collection spanned 50 days, from February 11th to March 31st, 2022. The data source was secondary data obtained from the Ease My Trip website.

## Dataset

The dataset contains information about flight booking options for travel between India's top 6 metro cities. It consists of 300,261 data points and 11 features in the cleaned dataset.

### Features

The various features of the cleaned dataset are explained below:

1) **Airline:** This categorical feature stores the name of the airline company and includes 6 different airlines.

2) **Flight:** Flight stores information regarding the plane's flight code and is also a categorical feature.

3) **Source City:** This categorical feature represents the city from which the flight takes off and includes 6 unique cities.

4) **Departure Time:** This derived categorical feature categorizes time periods into bins and stores information about the departure time, featuring 6 unique time labels.

5) **Stops:** A categorical feature with 3 distinct values indicating the number of stops between the source and destination cities.

6) **Arrival Time:** Similar to departure time, this derived categorical feature groups time intervals into bins and stores information about the arrival time with 6 distinct time labels.

7) **Destination City:** This categorical feature represents the city where the flight will land and includes 6 unique cities.

8) **Class:** A categorical feature containing information on seat class, with two distinct values: Business and Economy.

9) **Duration:** A continuous feature displaying the overall amount of time it takes to travel between cities in hours.

10) **Days Left:** This derived feature is calculated by subtracting the trip date from the booking date.

11) **Price:** The target variable, stores information about the ticket price.
