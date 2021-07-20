# Standard Normalverteilt - Readme

## Data dependencies
To run the jupyter notebooks, you must download the following datasets and put them into the data folder

- Chicago 2018 Divvy Bike Dataset [Link](https://uni-koeln.sciebo.de/s/gL1lM6FjSqTYdBT)
- Chicago Weather Dataset [Link](https://uni-koeln.sciebo.de/s/gL1lM6FjSqTYdBT)
- Divvy Bicycle Stations [Link](https://data.cityofchicago.org/Transportation/Divvy-Bicycle-Stations-In-Service/67g3-8ig8)
- Chicago Points of Interest (A to csv converted version is present under data/poi.csv) [Link](https://tools.wmflabs.org/kmlexport?article=List_of_Chicago_Landmarks)
- Chicago Districts Boundaries (https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Community-Areas-current-/cauq-8yn6)

After downloading, put all the files into the data folder, so that it looks like this
- data/
  - Average_Daily_Traffic_Counts.csv
  - Boundaries - Cummunity Areas (current).geojson
  - chicago_2018.csv
  - Divvy_Bicycle_Stations_-_In_Service.csv
  - poi.csv (included with the project)
  - weather_hourly_chicago.csv
  
After that you can freely execute the Jupyter notebooks of this project

Additionally you will need the following dependencies (that were not covered in the workshop) to get some of the visualizations running
- Plotly (https://anaconda.org/plotly/plotly)
- Shapely (https://anaconda.org/conda-forge/shapely)