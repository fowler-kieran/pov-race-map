## Mapping the Relationship between Race and Poverty in North Carolina with Bivariate Symbology

### Description

This project was created with the intention of examining the relationship between race and poverty in North Carolina.

The map uses point symbology representing each county's majority race, and choropleth symbology broken down into 5 equal interval classes for rates of poverty. I used equal interval classes so that the outliers could be better displayed, in the hopes that I could see a correlation between areas with large minority populations and higher rates of poverty.

I sourced all my demographic data from the US Census Bureau--both the racial estimates and poverty rates. I used geoJSON.io to convert my CSV file of county racial majorities and I joined a table of county poverty rates to a shapefile of North Carolina in QGIS.

An interactive tooltip can provide users who click on an icon with the county name that icon corresponds to, as well as the majority race present in that county.

For styling, I sourced my "Users" icon from Font Awesome. As it was qualitative data, I chose a qualitative color scheme from ColorBrewer. The "Accent" color scheme paired well with the "Purples" color scheme I chose for my choropleth symbology, which was also sourced from ColorBrewer.

#### Libraries

- The Javascript library, Leaflet, can be accessed [here](https://leafletjs.com/download.html).
- Chroma.js, which can be downloaded [here](https://cdnjs.com/libraries/chroma-js).
- Leaflet Ajax, found [here](https://cdnjs.com/libraries/leaflet-ajax).
- JQuery, downloadable from [here](https://cdnjs.com/libraries/jquery).

#### Data

- Basemap acquired from [Leaflet Providers](https://leaflet-extras.github.io/leaflet-providers/preview/).
- North Carolina Demographic and Economic Data from the [U.S. Census Bureau](https://www.census.gov/library/stories/state-by-state/north-carolina-population-change-between-census-decade.html)
- geoJSON conversion from [geojson.io](https://geojson.io/#map=2/20.0/0.0).
- Color palettes from [ColorBrewer](https://colorbrewer2.org/#type=sequential&scheme=Purples&n=3).
- "Users" icon from [Font Awesome](https://fontawesome.com/v5.15/icons/users?style=solid).
