**Visualizing Data with Leaflet**
---

This project utilizes leaflet, Javascript and D3 to visualize the earthquake data from the United States Geological Survey (USGS).The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.


**Challenge Instructions**
---

This project utilizes leaflet, Javascript, HTML and D3 to visualize the earthquake data from the United States Geological Survey (USGS). 

**Part-1:** Basic Visualization
Get the Data Set
<ul>
  <li>The USGS provides earthquake data in a number of different formats, updated every 5 minutes</li>
  <li>The "All Earthquakes from the Past 7 Days" data set was selected from the USGS GeoJSON Feed page</li>
  <li>The data was given in JSON format which was used to pull in the data for the visualization</li>
</ul>

**Import and Visualize the Data**
Create a map using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude.
<ul>
  <li>The data markers reflect the magnitude of the earthquake by their size and and depth of the earth quake by color</li>
  <li>Earthquakes with higher magnitudes appear larger and earthquakes with greater depth should appear darker in color</li>
  <li>Popups that provide additional information about the earthquake were included when a marker is clicked</li>
  <li>A legend was created to provide context for the map data</li>
</ul>

**Part-2**: More Data
Plot a second data set on the map above to illustrate the relationship between tectonic plates and seismic activity.
<ul>
  <li>Pull in Tectonic Plates data set</li>
  <li>Visualize it along side the original set of data</li>
  <li>Add a number of base maps (Satellite Map, Grayscale Map, Outdoors Map and Dark Map) to choose from/li>
  <liSeparate out the two different data sets (earthquakes and tectonic plates) into overlays that can be turned on and off independently</li>
  <li>Add layer controls to the map</li>
</ul>
