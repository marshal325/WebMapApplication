# Lab 3 Web Map Application
# COVID-19 Interactive Maps of the United States
## Shuai Yuan

## Introduction
This project is titled "Interactive COVID-19 Thematic Maps of the United States". It's an interactive web map application designed to visualize COVID-19 data across the United States, such as the distribution and ratio of infected populations. It includes two main maps: one showing the incidence rate of COVID-19 (a choropleth map), and another displaying the total number of cases (a proportional symbol map). The aim of this interactive map is to provide a clearer and comprehensive understanding of the COVID-19 situation in the United States and to help prevent the spread of the pandemic through the effective use of this interactive tool.

## Maps
- [COVID-19 Rates Map](https://github.com/marshal325/WebMapApplication/blob/main/map1.html)
- [COVID-19 Cases Map](https://github.com/marshal325/WebMapApplication/blob/main/map2.html)

## Screenshots
![COVID-19 Rates Map](https://github.com/marshal325/WebMapApplication/blob/main/img/map1.png)
![COVID-19 Cases Map](https://github.com/marshal325/WebMapApplication/blob/main/img/map2.png)

## Primary Functions
- **Choropleth Map**: Visualizes COVID-19 rates per 100,000 people. The map uses varying shades to represent different data ranges.
- **Proportional Symbols Map**: Displays total COVID-19 cases with circle markers. The size of each circle correlates with the case count.
- **Interactive Popups**: Clicking on a region or marker displays detailed information, such as specific case numbers or rates. Different areas with different information.
- **Custom Legend**: Each map includes a legend explaining the color or size scales to show different level and distribution of the pandemic.

## Unique Features
- **Dynamic and Updating Data**: GeoJSON data is dynamically loaded from external sources, allowing for real-time updates. It also enables maps to connect to other datasets and big data for updating and changing data.
- **Responsive Design**: Maps are fully responsive, providing an optimal viewing experience across various devices and screen sizes. Interactive design enables it to update and keep being interactive all the time so that enhancing interaction between user and map.

## Libraries Used
- [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/guides/): A JavaScript library that uses WebGL to render interactive maps.
- [D3.js](https://d3js.org/): Used for complex data visualizations and interactive maps.

## Data Sources
- COVID-19 data: [The New York Times](https://www.nytimes.com/interactive/2021/us/covid-cases.html)
- U.S. Census Bureau for Census and population data

## Credits and Acknowledgments
This project was developed by Shuai Yuan as part of GEOG 458 at University of Washington. Special thanks to the course instructors and TAs for their guidance and support.
