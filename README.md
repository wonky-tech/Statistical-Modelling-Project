# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The project aims to demonstrate ability to use python, and related libraries, to analyze and visualize data retrieved from external sources. I chose to look at bike stations in Glasgow, UK, from the city_bikes API. I paired this data with place or POI data from the FourSquare and Yelp APIs.

## Process
1. access data from APIs (city_bikes, FourSquare, and Yelp)
2. where necessary, parse JSON data given by APIs so that it can be stored in pandas dataframes for further processing.
3.  join data from the city_bikes API with the FourSquare and Yelp APIs. This resulted in three dataframes, the latter two combining bike station data with Point of Interest (POI) data.
4. analyze data.
5. create a regression model from the data and explain some insights from it.

## Results
The related place information from FourSquare covered a large number of POIs (around 6000) but seemed to focus on FourSquare's internal categorizations. I could not find useful information like user ratings. In contrast, Yelp data covered fewer POIs for the give city (around 4000) but included useful information like user ratings. 

## Challenges 
I found it especially difficult to parse deeply nested JSON data provided by the APIs. This lead to possibly less data/insights extracted from the available data. From the given data, it was hard to find strong relationships between features (eg distance from bike to POI and ratings, number of free bikes and ratings). 

## Future Goals
With more time, I'd like to explore the API data more, and do a better job parsing it into dataframes. I'm sure this would lead to a better analysis and understanding of the data. I'd also like to explore the categories used to see how to be more specific, while still retrieving meaningful place information.