# Kentucky Toxic Release Inventory Facilities
Authored by: Jessica Freeman, September 2021
<br>GitHub Page URL: https://jmfr236.github.io/ky-tri-facilities/

## About: 
As a part of the Toxic Release Inventory (TRI) Program, the EPA collects annual reports from large facility sites around the United States. These reports contain information about the amount of toxic chemicals a facility has released into the environment. Industries that submit reports involve manufacturing, mining, electrical power, chemical manufacturing, and hazardous waste. Each yellow glowing circle represents a potentially hazardous facility in Kentucky. Use this interactive map to view the number of reported TRI sites within each county.

## Sources:
<li> Toxic Release Inventory 2014: https://query.data.world/s/3b3oi57gti4qhoexmg74sdc3ftz2te
<li> Kentucky Counties: http://www2.census.gov/geo/tiger/GENZ2020/shp/cb_2020_us_county_500k.zip
<li> Kentucky Rivers: https://d2ad6b4ur7yvpq.cloudfront.net/naturalearth-3.3.0/ne_10m_rivers_north_america.geojson
<br>

## Jupyter Notebook Details
If the Jupyter notebook will not open for viewing within this repository, please see the html version here.

To run this notebook the following libraries need to be installed.

jupyter
jupyterlab
pandas
geopandas
matplotlib
gdal
fiona
geoplot
mapclassify
Maintaining the order of the above list during install will be helpful.

For Anaconda environments use:

conda create --name 'your_env_name' jupyter jupyterlab pandas geopandas matplotlib gdal fiona -y && conda activate 'your_env_name'