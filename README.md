# Weather App

This weeks project was to build a weather site fetching data from Open Weather Maps.
The focus was to get familiar with using APIs. 
## The problem
I started with the fetch functions, making sure all the data was retrieved and printed it in the console. When I had my data in place i put it to display in the html.

When I had everything in place for a specified city, I changed the code into using geo-location. 

The big problem for me was to display the local time for each location without any GMT converstions done by string methods or Date objects. I made it work after several hours of trial and error by creating a UTC-date and applied some string methods, but I'm not sure whether it is a good solution.  

I also don't know what to do with potential errors thrown by the fetch. For now I log the error message but I maybe need to remove this. 

For this weeks project I have tried to focus on structure and readable code and I aimed for black level.

## View it live
https://karro-weather.netlify.app/
