# PyBer_Analysis

## Project Overview
The objective of this project was to analyze and visualize the performance of the ridesharing service Pyber. I used my phyton skills and knowledge of Pandas to do a deeper dive into the data to display how different city types (urban, suburban, and rural) performed. The results of the analysis can be used by the company and drivers to increase output and dedicate resources specifically to higher output areas accordingly. 

The analysis is based on the following:

*  The percentage of total number of rides for each city type
*  The percentage of total drivers for each city type
*  The percentage of sum of the fares for each city type
*  The average fare per driver for each city type
*  The total weekly of the fares for each city type

## Resources
- Data Source: [city_data.csv](https://github.com/meliscelikay/PyBer_Analysis/blob/050055e72bf8bdc8c3c4c5d619bdf80d489cad28/Resources/city_data.csv), [ride_data.csv](https://github.com/meliscelikay/PyBer_Analysis/blob/050055e72bf8bdc8c3c4c5d619bdf80d489cad28/Resources/ride_data.csv)
- Software: Python 3.9.7, Conda 4.12.0, Jupyter Notebook 6.4.5
- Dependencies: Pandas Library and Matplotlib Library


## Results
### Overview of City Types  - PyBer Ride-Sharing Data (2019)
The initial summary bubble chart below highlights the average fare of rides between city type (urban, suburban, rural) against the total number of rides in that city, the total number of drivers per city and the average fare per city.  The size of the circles correlates with number of drivers per city and the color of the circles correlates to the city type .

![Fig1](https://github.com/meliscelikay/PyBer_Analysis/blob/050055e72bf8bdc8c3c4c5d619bdf80d489cad28/analysis/Fig1.png)

### Ride Count Data & Percentage of Total Rides by City Type
The box-and-whisker chart displays the range of ride count data in each city type. The urban ride count data includes an outlier with 39 rides in one city. The average number of rides in rural cities is lower both urban and suburban cities.

![Fig2](https://github.com/meliscelikay/PyBer_Analysis/blob/050055e72bf8bdc8c3c4c5d619bdf80d489cad28/analysis/Fig2.png)

The percentage of total fares pie chart displays similar information. Urban cities have more than 2/3 of the total rides in 2019 which accounted for 68.4%, whereas suburban cities accounted for 26.3% and rural cities accounted for 5.3%

![Fig6](https://github.com/meliscelikay/PyBer_Analysis/blob/050055e72bf8bdc8c3c4c5d619bdf80d489cad28/analysis/Fig6.png)

###  Driver Count Data & Percentage of Total Drivers by City Type
The box-and-whisker chart displays the range of drivers count data in each city type. It shows the number of urban drivers is higher than both the number of rural drivers and the number of suburban drivers.

![Fig4](https://github.com/meliscelikay/PyBer_Analysis/blob/050055e72bf8bdc8c3c4c5d619bdf80d489cad28/analysis/Fig4.png)

The percentage of total drivers pie chart displays that the highest percentage of total drivers with 80.9% for urban cities, whereas 30.5% total fares for suburban cities and 6.8% total fares for rural cities.

![Fig7](https://github.com/meliscelikay/PyBer_Analysis/blob/050055e72bf8bdc8c3c4c5d619bdf80d489cad28/analysis/Fig7.png)

###  Ride Fare Data & Percentage of Total Fare by City Type
The box-and-whisker chart displays the range of ride fare data in each city type. It displays that urban and suburban cities tend to be lower and rural cities is higher.

![Fig3](https://github.com/meliscelikay/PyBer_Analysis/blob/050055e72bf8bdc8c3c4c5d619bdf80d489cad28/analysis/Fig3.png)

The percentage of total fare pie chart displays that urban cities have higher percentage of total fares with 62.7% whereas 16.5% total drivers for suburban cities and 2.6% total drivers for rural cities.

![Fig5](https://github.com/meliscelikay/PyBer_Analysis/blob/050055e72bf8bdc8c3c4c5d619bdf80d489cad28/analysis/Fig5.png)

In the final summary analysis, a multiple-line chart that displays the total fare by city type from January to April 2019. Overall, the highest revenue in comparison to suburban and rural cities is urban cities. 

![PyBer_Fare_Summary](https://github.com/meliscelikay/PyBer_Analysis/blob/234297d7cc2fdfef166ea268e8c68f3e02654420/analysis/Pyber_fare_summary.png)


## Summary
The results of the analysis were very clear, Urban areas clearly performed the best across all matrices. I wish the dataset was more expansive (12 months), limiting to only 4 months may not show all relevant trends and performance. Perhaps Suburban and Rural areas would do better in warmer months which may be related to tourism, when people tend to leave big cities and head to vacation locations. Regardless, I still think Urban areas would perform the best in general due to population density. Also, dataset is from 2019 only, if we had more data across several years different conclusions could be reached ie 2020-2022 during Covid 19 pandemic time frame. I am sure economic downturns would impact ridesharing industry. 
Urban areas lead in categories such as driver count, fares, and total ride count. I thought it would have been interesting to analyze age, gender, ride distance, and median income of riders as well, but there was no data available in this project.   
