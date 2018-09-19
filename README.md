# driveToWork
### Steps
* delete weekends data 
* apply smoothing function with cyclic, smooth and plot the data
* apply CUSUM to find the change point

### challenges
* it is hard to find good data source



### data source
* only contain traffic counts for each day 
  http://data-tempegov.opendata.arcgis.com/datasets/7ecc9c4054ba4f42a16976e59fc9e17b_0
* https://developer.tomtom.com/store/maps-api 
  might be paid service
* only contain traffic counts for each hour 
  https://www.kaggle.com/hanriver0618/2011-2013-nyc-traffic-volume-counts 

### Plotting
* search for starting point and ending point of each street (Google API with streetA&streetB)
* draw line on google map with two points
* color the line based on the counts of traffic
* how to display time series data on map 
