# Mapping Earthquakes
Traversing and retrieving GeoJSON data on earthquakes and tectonic plates from the US Geological Survey website using JavaScript and D3 and Leaflet libraries, and plotting the data on a Mapbox map through an API request.  

## Project Overview: 
The purpose of this project was to create an interactive map displaying global data on tectonic plates and earthquake activity from within a seven day timeframe. The map allows the user to explore the relationship between fault line locations and earthquake activity. 

The tectonic plate fault lines are displayed as a removable tile layer on the map. Two additional tile layers include "Earthquakes" and "Major Earthquakes", which both display circle markers on the map marking the location of earthquake activity within the retrieved seven day timeframe. The markers' radius and color correspond to the magnitude of the earthquake, with the "Earthquakes" tile layer displaying all earthquake activity and the "Major Earthquakes" tile layer displaying only earthquake activity of a 4.5 magnitude or greater. Clicking on any of the circle markers displays data related to the size and exact location of the earthquake. 

The maps also contain switchable base layers for a daytime, nighttime, or navigation-based view of the map. 

## Tools:  
- Software: Visual Studio Code
- Languages/Dependencies: HTML/CSS, JavaScript, D3.js and Leaflet 
- API Sources: Mapbox.com and usgs.gov
- Retrieved GeoJSON data: 
  - [all earthquakes over a seven day timeframe](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
  - [major earthquakes over a seven day timeframe](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson)
  - [tectonic plate data](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)

## Link to interactive map:
The interactive map is accessable through [this webpage.](https://npvandyke.github.io/Mapping_Earthquakes/) 

[![satellite map view](EarthquakeNight.png)](https://npvandyke.github.io/Mapping_Earthquakes/)


Questions? Comments? [Let's Connect!](https://www.linkedin.com/in/natalie-vandyke-npv/) ![](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)
