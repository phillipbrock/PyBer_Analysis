# Pyber Report
## Overview of Analysis
Using extensive ride share data, the client requested insight into city types (urban, suburban, and rural) and how they might relate to other ride-share data categories. This information is then presented graphically, and can be used to make more informed business recommendations and decisions.
### Data Available
For this analysis, CSV data was used which provided specific ride information including fare, date, and city, plus more broad city data which included the type of city (rural, urban, or suburban) as well as the total number of drivers in each city.  

## Results

### Summary Statistics
From the available CSV files, I was able to generate summary statistics such as totals for rides, drivers, fares, average fare per ride, and average fare per driver, grouped by the three city types: 


![This is an image](https://github.com/phillipbrock/PyBer_Analysis/blob/main/Resources/summary1.PNG)

The summary data show that, while urban markets are predictably more prolific for the numbers of rides and the number of drivers, the fares are less expensive for the customer and less profitable per ride for the driver.

### Weekly Analysis

After completing summary statistics, I was able to use a time series to display weekly fare totals by city type over a span of almost five months. Using a multi-line graph, it becomes more clear which markets show the highest gross for fares, as well as changes in demand at different points in the time period across the three market types.


![This is an image](https://github.com/phillipbrock/PyBer_Analysis/blob/main/PyBer_fare_summary.png)


One can see graphically how the three markets roughly relate to one another. At times, such as the last week in February, there is a spike in fares across all three city market types. At other times, they have slight divergences (such as a spike in suburban fares in mid to late April while fares in rural and urban markets decline).

## Summary
This analysis shows stark differences for Pyber to consider as it competes across the three market types present in the data. Moving forward, Pyber might consider the following:

1) While the overall ride volume is higher in urban markets, the average fare and fare per driver show that suburban and rural markets still have demand that can be met with more drivers. I recommend researching ways to incentivize drivers away from urban markets and toward rural / suburban markets to help balance the discrepency. This could mean more Pyber availability for rural and suburban customers, as well as less saturation in the market for drivers in urban markets.

2) Look to optimize price during key surges across all markets. The graphic representation of the time series data show at least one very clear surge in late February. Optimizing price will allow more profit for Pyber and its drivers.

3) Focus marketing on suburban and rural markets. Pricing data show that rural and suburban riders value the service, but it seems to not be utilized. Such market outreach will can only help the Pyber brand.
