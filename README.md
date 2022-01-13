# World Map 

## In this project, we are using the Google geocoding API to clean up some user-entered geographic locations of the best universities in the world and then placing the data on a Google Map.

### Implementation:

#### We ask for a set of data in the where.data file from the user, here you may enter locations of any type.

#### I have used this file to highlight all of the world's best Universities which where on any checklist for my
#### Undergraduate degree.

#### Use the API to fetch the exact locations of these Universities. We then save it in a sql database.

## Please check the poster file in the Repository for more information

#### And then creates a visualization using a json file (which has all the data dumped into it from the database), The result is a World Map.

## Visualization:

<img width="1024" alt="Visualization for World Map" src="https://user-images.githubusercontent.com/69566994/149311531-8eda5774-d601-48f0-b0dd-1cc2e0b3fb17.png">

### Notes:

- Due to the rate limiter in the API, we have to be very efficiant in using the API
- First, we take our input data in the file(where.data) and read it one line at a time
- Second, retrieve the geocoded response and store it in a database 
- As of December 2016, the Google Geocoding APIs changed dramatically. All the Google Geo-related APIs require an API key.
- Simply open where.html in a browser to see the locations.  You can hover over each map pin to find the location that the geocoding API returned for the user-entered input. 
- If you cannot see any data when you open the where.html file, you might want to check the JavaScript or developer console for your browser.
- No future mass commits to main are allowed
