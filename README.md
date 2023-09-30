# leaflet-challenge

Part 1: Create the Earthquake Visualization

![2-BasicMap](https://github.com/sladertorres/leaflet-challenge/assets/134868789/9821aef4-7098-40c8-84a7-b73b0d77c265)


Your first task is to visualize an earthquake dataset. Complete the following steps:
Get your dataset. To do so, follow these steps:
The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed Links to an external site. page and choose a dataset to visualize. The following image is an example screenshot of what appears when you visit this link:
![3-Data](https://github.com/sladertorres/leaflet-challenge/assets/134868789/ab4b1325-10fd-4397-8903-7f04639a303c)


When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:
![4-JSON](https://github.com/sladertorres/leaflet-challenge/assets/134868789/f243a707-f639-4f7e-a79d-e8cd36eb5858)


Import and visualize the data by doing the following:
Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.
Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.
Hint: The depth of the earth can be found as the third coordinate for each earthquake.
Include popups that provide additional information about the earthquake when its associated marker is clicked.
Create a legend that will provide context for your map data.
Your visualization should look something like the preceding map.
Part 2: Gather and Plot More Data (Optional with no extra points earning)

Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in this dataset and visualize it alongside your original data. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplates Links to an external site..
This part is completely optional; you can complete this part as a way to challenge yourself and boost your new skills.
The following image is an example screenshot of what you should produce:
![5-Advanced](https://github.com/sladertorres/leaflet-challenge/assets/134868789/fa46c217-b6a4-4368-876b-5682649a8f7e)


Perform the following tasks:
Plot the tectonic plates dataset on the map in addition to the earthquakes.
Add other base maps to choose from.
Put each dataset into separate overlays that can be turned on and off independently.
Add layer controls to your map.
Requirements

These requirements apply only to "Part 1: Create the Earthquake Visualization" as "Part 2" is optional with no extra points earning.
