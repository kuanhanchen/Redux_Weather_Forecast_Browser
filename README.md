# Redux_Weather_Forecast_Browser

It's a weather forecase browser. At the top, a user is able to serach for a city in US. When a user submits the city by clicking search button or pressing Enter, we're going to submit a query to a third party API, that's going to serve us back forecasted weather data for the next five days. Once we get that weather back, we're going to add a row on a table with information about that particular cities forecast for the next five days. The user can search for many different cities over time and for each search is just added an additional row. In each row, we'll display city, temperature, pressure, and humidity. Also, We're going to do a simple line chart to represent each of those values.

Weather Forecase API: openweathermap.org/forecast5

Using redux-promise and axios package to helps us handle AJAX requests inside of our app.

### Getting Started

There are two methods for getting started with this repo.

#### Familiar with Git?
Checkout this repo, install dependencies, then start the gulp process with the following:

```
> git clone https://github.com/kuanhanchen/Redux_Book_List.git
> cd Redux_Book_List
> npm install
> npm start
```

#### Not Familiar with Git?
Download the .zip file. Extract the contents of the zip file, then open your terminal, change to the project directory, and:

```
> npm install
> npm start
```
