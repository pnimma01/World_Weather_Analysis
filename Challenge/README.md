# World_Weather_Analysis
Module 6

**Note:**
I worked with Aman Gill for this challenge. We followed pair-programming methodology and the code and readme was co-created.

# **World_Weather_Analysis**

## **Project Overview**

## **Overview of the analysis:**
We will be gathering weather data for random cities in the world, provide functionality to gather comfortable temperature range for travellers, and plot a map and provide directions to nearest hotels to the potential vacation spots.
This project can be sub divided into the following activities:
1. Gather random city data, including longitude and latitude, current weather conditions.
2. Determine potential vacation spots.
3. Provide driving directions to and from the hotels in the vacation spots.

City Data is collected using API to openweathermap.org. The returned data is added to a dataframe, and saved as a CSV file. 
Here is a snapshot of the data gathered using API call: ![Weather data](https://github.com/pnimma01/World_Weather_Analysis/blob/e302ac861da6d189b787c693e48261da5ffdc315/Challenge/Weather_Database%20/CityData_C1.png)

Creating potential customer travel map involved gathering customer's weather preferences, based on which the city weather data is filtered, 

![Vacation Cities data](https://github.com/pnimma01/World_Weather_Analysis/blob/e302ac861da6d189b787c693e48261da5ffdc315/Challenge/Vacation_Search/City_Search_Temp_C2.png)

followed by using Google maps API to show the vacation map.

![Vacation map](https://github.com/pnimma01/World_Weather_Analysis/blob/e302ac861da6d189b787c693e48261da5ffdc315/Challenge/Vacation_Search/Cities_Hotels_C2.png)

Finally, using Google maps API, we plot the directions to the vacation spots.

Plotting the directions gave an eeror while selecting the list of cities to map. Confirmed that the syntax and the code is correct with a TA.

### **Challenges encountered:**
1. The API call to openweathermap has a limitation on number of requests, and is time consuming in case of reruns.
2. The google API call to map the directions/ itinerary keeps on giving errors.

