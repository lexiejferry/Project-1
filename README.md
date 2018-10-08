# Project-1
A map relating NDVI values to State Tax rates in Baltimore County, Maryland

@Author: Lexie Ferry
@Date:   2018-09-24T09:45:11-04:00
@Email:  lexiejferry@gmail.com
@Project: Project 1
@Last modified by:   Lexie Ferry
@Last modified time: 2018-09-24T09:55:12-04:00



**A Comarision of NDVI to State Tax rates in Baltimore City**

- **Project goal:** My project goal was to see if there is a correlation between vegetation intensity and average state tax rates in Baltimore City.

- **About:** For this project, I made a hexagonal grid of 350m by 350m (approximately 3 city blocks) and extracted the average NDVI and State Tax information using a combination of SQL query and Zonal Statistics. I then reclassified the data and displayed it on a 2.5D Map. All data was converted to a North American Albers Equal Area Conic projection. Landsat Data used was taken in June to maximize vegetation intensity

![alt text](https://github.com/lexiejferry/Project-1/blob/master/Project1map.png "Project1map")

![alt text](https://github.com/lexiejferry/Project-1/blob/master/Chart_P1.PNG "Chart_P1")

- **Results:** There was determined to be a slightly negative correlation between NDVI and State Tax values with a correlation of -0.1434. This is most likely due to the distribution of residential property being located near forests in suburbs, versus commercial property being located more in the city center where there is less vegetation. For a better result, a differentiation between residential and commercial property would be needed.

**Software Used:** QGIS 3.2

- **Tools, Plugins, and Packages:** Spatialite Databases, SQL Query, Zonal Statistics, Clip, Extract/clip by extent, Raster Calculator, Join attributes by location, 2.5D Visualization

**Data Sources:** USGS Landsat 8 satellites, Baltimore City Services (https://cityservices.baltimorecity.gov/realproperty)
