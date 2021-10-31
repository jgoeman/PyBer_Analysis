# PyBer Analysis Challenge

## Overview of the Analysis
Management has requested data comparing ride sharing data and city type for all of the data, and Data showing the fares for the first four months of 2019 by date. This has been completed through the creation of data frames and a mulitiple-line chart of total fares for each city type.    

Two data sets were provided in this analysis:
- The Ride Data CSV containing the following information for areas serverd by PyBer:
  1. City 
  2. date
  3. fare
  4. ride ID    

- The City DAta CSV containing the following information for areas serverd by PyBer:
  1. City
  2. Driver Count for the City
  3. Type of City (Urban, Suburban, Rural)    
    
The information in the two data sets were merged together into one Dataframe and the information was then grouped by the the type of city to provide the requested information.The information was then rearanged as necessary using pivots and resampling.  The followin six metrics were gathered in relation to the city type:
- Total Rides
- Total Drivers
- Total Fares
- Average Fare per Ride
- Average Fare per Driver
- Total fares by the city types 

## Results
The ride-sharing data compared among city types contains a few differences that can be looked at to provide insight into PyBer's overall business.    
When comparing rural city types to suburban  and urban areas there are much less overall rides in the given time period. Approximately 5.3% (125 rides) of total rides are given in rural areas, 26.3% (625 rides) of rides are given in suburban areas and 68.4% (1625 rides) are given in urban areas. In rural and suburban areas total drivers are less than total rides given while in urban areas there are more total drivers than overall rides. Total fares, average fare per ride, and average fare per driver are at their highest in rural areas, decrease in urban areas, and further decrease in urban areas. This information can be seen organized in the following dataframe:    

![SummaryDataFram](https://user-images.githubusercontent.com/36859475/139602163-30d0faeb-f798-4c52-bd2c-8c777f0948b3.png)
    
The total fare by city type has been analyzed on a weekly basis for the first four months of 2019. Each city type (Rural, Suburban, and Urban seem to follow simliar overall trends over this time with slight variances and different magnitudes of change. The total fares are at their highest towards the last week of February decrease into March and have slight variability throughout the rest of the weeks analyzed. Urban cities at the highest point increase to almost $2,500 fares but tend to vary and stay above $2,000 in total fares. Suburban cities at the highest point are around 1,400 in total fares, but on average stay closer 1,000 in fares on a weekly basis. Rural cities at their highest point are around $500 in the fourth week of February and  first week of April, but hover close to the $250 range most other times. These numbers are generalization, but a clear visualiztion can be seen in the chart below.    

![Pyber_fare_summary](https://user-images.githubusercontent.com/36859475/139602489-99e34042-76e6-42db-910e-2e55706a31e9.png)

## Summary
Given the data provided above a few recommendations can be given addressing the disparities among city types:
- Greater promotion to people living in urban areas should be used. The amount of drivers available in urban areas greatly exceeds the total rides given. This underutilization of drivers shows that there is a greater capicity of rides that could be tapped into in these areas.
- Promote for more drivers in rural and suburban areas. There are less drivers than rides given in these areas which could lead to greater times people wait for rides. Trying to add more drivers in these areas may increase customers satisfaction with lower wait times.
- Between the three city types demand changes slightly over certain periods of time such as the 4th week of February. Pyber should look into these increases in demand,see what is driving the increases, and look into if a greater number of fares could be gathered through more drivers, advertising, and a greater understanding of the events that take place at these times. PyBer should then leverage this information for other times during the year to raise the overall average of fares.

