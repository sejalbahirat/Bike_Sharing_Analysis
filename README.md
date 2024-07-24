# Bike_Sharing_Analysis

## Overview
This project analyses a bike-sharing dataset to understand user behaviour and identify factors influencing bike usage. The dataset includes daily records of user counts along with various attributes such as date, season, weather conditions, and more. 

## Dataset 
* The dataset contains the following columns: 
* instant: Unique identifier for each record 
* dteday: Date of the record 
* season: Season (1: Winter, 2: Spring, 3: Summer, 4: Fall) 
* yr: Year (0: 2018, 1: 2019) 
* mnth: Month (1 to 12) 
* holiday: Whether the day is a holiday (0: No, 1: Yes) 
* weekday: Day of the week (0: Sunday to 6: Saturday) 
* workingday: Whether the day is a working day (0: No, 1: Yes) 
* weathersit: Weather situation (1: Clear, 2: Mist, 3: Light snow/rain, 4: Heavy rain) 
* temp: Normalized temperature in Celsius 
* atemp: Normalized feeling temperature in Celsius 
* hum: Normalized humidity (percentage) 
* windspeed: Normalized wind speed 
* casual: Count of casual users 
* registered: Count of registered users 
* cnt: Total count of users (casual + registered) 

## Installation 
To run the analysis, you need to have Python and the following libraries installed: 
- pandas 
- numpy 
- seaborn 
- matplotlib 
### You can install the required libraries using: 
- pip install pandas numpy seaborn matplotlib 

## Analysis and Visualization 
The analysis includes: 
- Time series plots to visualize user count trends over time. 
- Box plots to examine seasonal, monthly, weekday, and holiday trends. 
- Scatter plots to explore the impact of weather conditions on user counts. 
- Correlation analysis to identify relationships between different variables. 
 
## Insights 
Key insights from the analysis include: 
- User activity is higher on weekends and holidays. 
- Favourable weather conditions (clear skies, moderate temperatures) lead to increased bike usage. 
- Seasonal trends indicate higher usage in certain seasons. 

## Contributing 
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes. Ensure your contributions align with the project goals and maintain code quality. 

## Acknowledgements 
Special thanks to the data providers and the open-source community for their valuable resources and tools. 
