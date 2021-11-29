# Using Weather Data in Vacation Decision-Making

## Overview
With the goal of enhancing customers' experiences when making decisions about their next vacations, data on world weather was retrieved and used to generate maps that gather destination options based on the customer's input.

## Results

### Retrieving Weather Data
With the goal of creating a database with sample world weather data, 2,000 random latitutes and longitudes values were generated and used to make an API request to the openweathermap.org portal. A database with 423 cities containing information about their locatizations and their current weathers was generated. See in Table 1 the first 10 rows of the database.

Table 1. First 10 rows of the Sample World Weather Database
![Screen Shot 2021-11-28 at 8 04 15 PM](https://user-images.githubusercontent.com/89421440/143807088-cff02777-1147-47ec-9d5d-adfe1c7b26be.png)


### Creating a Customer Travel Destinations Map
By asking for the customer's input about the minimum and maximum temperatures they would like for their trip, the code generates a vacation map with hotel and city suggestions within the selected weather range. The vacation map, shown in Figure 1, is generated both from the Database previously created and an API request to the maps.googleapis.com portal.

Figure 1. Vacation Map based on Customer's Input
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/89421440/143809088-7ed6798f-0561-419c-b709-f25f4e991d7c.png)


### Creating a Travel Itinerary Map
A new code was written to create a travel itinerary map from the customer's vacation selections. The map in Figure 2 includes 4 cities in Northeasthern Brazil and suggests a travel itinerary beginning and ending at Sao Jose Da Coroa Grande, and passing through Touros, Aquiraz and Salgueiro.

Figure 2. Travel Itinerary Map
![WeatherPy_travel_map](https://user-images.githubusercontent.com/89421440/143809950-86e166e0-b2ff-41ce-bf33-f9c7bd12306e.png)


## Summary
In sum, the database and maps generated allows the customers to make data driven decisions about their vacation plans.
