# weather
--

It were developed basically 2 components.
1. Component for showing the initial 6 cities
2. Component for showing the details of the weather of a city

The first component it is also reused for showing the cities in the search result.
Those components basically just show information. The search it is done in the root/parent component that pass the information to child components through properties.
It is used the routerview component to handle the routes and visualize components accordingly.
The image are loaded directly from the weather site taking the information provided by each city in the search results. They can be stored locally if it is expected a high traffic due to weather site restrictions.

## It was used bootstrap 4 for the basic design.
