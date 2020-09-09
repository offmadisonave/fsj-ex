# Off Madison Ave

## Full Stack Javascript Exercise

### Requirements

You should have NodeJS 10+ installed on your local development machine with wide area network availability.  You are encouraged to share your entire screen during the exercise and make use of your favorite tools and libraries.

### Instructions

1)  Clone this repository

2)  Inspect the contents of the repository and determine your next steps.

3)  Change the server HTTP port to 3001

4)  Open the default route in your browser

5)  Create a GET route that returns the contents of "static.json"

6)  Create a route that takes a parameter for zip code, obtains the 
    forecast from openweathermap.org and returns the average 
    high and low temperatures for every period returned in Fahrenheit.

    GET https://api.openweathermap.org/data/2.5/forecast?zip={ZIP_CODE}&appid={OPEN_WEATHER_API_KEY}

7)  Create middleware that requires an authentication request header 
    and apply that middleware to your new routes.

8)  Create a React page that POSTs a zip code to a new server route that uses the 
    same weather forecast API and display the forecasted high for tomorrow.  