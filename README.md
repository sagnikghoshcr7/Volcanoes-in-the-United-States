# Volcanoes-in-the-United-States
With help of Python and Folium, visualize active Volcanoes in the United States. Also, create a choropleth map to demonstrate unemployment rate in the same country.

## 1. Installing dependencies

Installing dependencies is the first thing you want to do.

```
#Library
pip install folium

```

## 2. Understanding files in the directory

### Data

1. Volcanoes_USA.txt
2. us-states.json
3. us-unemployment.csv


### Step by Step Solution
I have created different files for each step in creating the interactive dictionary, here's the description of what each file does. 

* geo1.py
  * Create a base map using folium.Map

* geo2.py
  * Add a single marker using folium.Marker

* geo3.py
  * Add multiple markers with help of 'for' loop

* geo4.py
  * Load Data and use that data to plot markers

* geo5.py
  * Add colors according to elevation of the Volcanoes

* geo6.py
  * Change icons of markers to circular

* geo7.py
  * Use MarkerCluster() to cluster all markers according to zoom levels

* geo8_choropleth.py
  * The code for the choropleth map (US unemployment rate in %)

*Note: All files are integrated with comments to help you understand each and every line/command of the code.*
