# Module 9 Assignment - Surfs Up Analysis

## Background
As W. Avy continues to prepare for the potential opening of a surf and ice cream shop in Hawaii, he has hired us to take a closer look into the temperature data for Oahu in June and December. He believes that from this data, he will be able to determine if the demand for a surf and ice cream shop is consistent throughout the year. Our analysis and conclusions can be found below.

## June and December Temperature Analysis
After parsing the temperature data, we were able to create two data frames that contain the June and December data, respectively. Running summary statistics on the two data frames, we were able to pull together the tables below. Based on the statistics generated for June and December temperatures, we have pulled the following conclusions:

- June temperatures, on average, are 4 degrees warmer than December temperatures. 
- The variance in temperatures for December is larger than the variance for June. The standard deviation for December temperatures is 3.75 degrees vs 3.26 degrees, respectively. As for the interquartile range, the range for December is 5 degrees compared to 4 degrees for June. 
- The max temperature for December and June are relatively the same at 83 and 85 degrees, respectively, but the min temperatures vary. The min temperature for December is 56 degrees and 8 degrees lower than the min for June. 


**June Temperature Statistics**
![june_temps](https://github.com/kjminges/surfs_up/blob/main/june_temps.png)


**December Temperature Statistics**
![december_temps](https://github.com/kjminges/surfs_up/blob/main/december_temps.png)

## Conclusion
While the temperature summary statistics differ for December and June, the differences are slight and one could argue that the temperature profiles are both  advantageous for a surf and ice cream shop. In order to do our due diligance for W. Avy, we would like to perform the following queries for the June and December weather data:

1. As W. Avy continues his review of the data, he should make sure that the statistics that we pulled for June and December temperatures is consistent based on the different station points where the data was pulled. If W. Avy is zero-ing in on a location for his shop, we will want to pull the temperature data for June and December for the station that is closest to this location. 
2. While the temperature can correlate to the success of W. Avy's surf and ice cream shop, he will need to consider the weather as well. For example, it may be warm in December, but if there is a lot of rain, it is possible that this could hurt his business. Therefore, we will need to pull the summary statistics for the precipitation data based on the month. This will help us determine if one month is more wet than the other. 
