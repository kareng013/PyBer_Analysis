# PyBer Analysis

## Overview of the analysis

V. Isualize is seeking our help to create a new DataFrame for data pulled from city data and ride data in order to showcase how data differs by each city type and how this can help with decision making at the Company. In this analysis we create a Summary DataFrame and then use it to create a multiple line plot in order to visualize how total weekly fares differ for each city type on a monthly basis.

## Results

The results from Image 1 below display the total rides, total fares, total drivers, average fare per ride and driver for each type of city: Rural, Suburban, and Urban.

The following observations can be made from the data below:

- Total rides in Urban cities were 2.5 times more than rides requested in the suburban area and 13 times more than rural area
- There are more drivers in the Urban area than the other two areas combined
- Urban Area drivers are more than the rides requested
- Total fares are the highest in Urban areas with total fares of $39,854.38
- Average fare per ride is the most expensive in Rural cities with an average fare of $34.62, due to less drivers and more rides requested
- Average fare per driver is highest in Rural area with driver making average weekly fares of $55.49
- Average fare per driver is the lowest in urban cities at $16.57

![summary_df](https://github.com/kareng013/PyBer_Analysis/blob/main/analysis/Summary%20Data%20Frame.png)

**Image 1: Summary DataFrame**

By observing the line chart in Image 2, it can be seen that fares are fairly steady across the 4 month period. For Urban areas, total fares reached the highest end of February and beginning of March. For Suburban areas, fares reached highest end of February and slowly inclining again end of April. For Rural areas, we see the same pattern where fares were highest end of February and beginning of April. 

![PyBer_Summary](https://github.com/kareng013/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

**Image 2: Total Fares by City Type Chart**


## Summary

The following recommendations can be made by assessing this data:

1. Increase the number of drivers in the Rural area, create incentives for drivers
2. Conduct promotional activities in Urban cities to increase rides due to highe number of drivers available
3. Create incentive for drivers to work on days that total fare reachest its peaks in order to fulfill all ride requests

There are a number of outlying factors that are not included within this data, including but not limited to the following:
- Holidays and events in the different areas causing more rides
- Peaks at certain hours of the day, need to evaluate what hours peak the most for ride requests each day of the months to assess where drivers are needed
