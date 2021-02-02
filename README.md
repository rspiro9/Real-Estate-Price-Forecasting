
# Module 4 Final Project - Real Estate Price Forecasting

## Purpose:
For this project, I will be answering the following question in order to consult a fictional real-estate investment firm:

> What are the top 5 best zipcodes for us to invest in?

I will forecast real estate prices of various zipcodes using data from [Zillow](https://www.zillow.com/research/data/) and recommend the top 5 best zipcodes to invest in.

## Data Science Process Used:
I leveraged the OSEMN (Obtain, Scrub, Explore, Model, Interpret) process for this project. My notebook is organized to follow this process.

## The Dataset:
The data I'm working with is a modified version of the data from the [Zillow Research Page](https://www.zillow.com/research/data/). The data file can be found in this repo as `zillow_data.csv`.

## Key Question Answered:
What are the top 5 best zipcodes for us to invest in?

To qualify as one of the 'best' regions, the region must meet the following qualifications: 
1. Have above average annual growth rate since the housing market recovered from the crisis (2012), and also have above average annual growth rate during the crisis (2007-2012)
2. Needs to have a 5yr average annual growth rate in the top 25% of the dataset
3. Needs to also have a 10 yr average annual growth rate in the top 25% of the dataset
4. Needs a narrow predicted interval width to ensure a more accurate forecasted value (interval width must be within 25% of the smallest interval widths
5. The maximum p-value must be less than alpha=.05 to ensure we are statistically significant and therefore a better performing region.
