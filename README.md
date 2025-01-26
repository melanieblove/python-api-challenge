# python-api-challenge

The main purpose of this challenge is to analyze the correlation between latitude and other variables like humidity, wind speed, cloudiness, and temperature, and how these factors change as their latitude approaches the Equator.



## Results of correlations of the charts:

1. The correlation found in the chart temperature vs. latitude (Northern_hemi 0.7298831639910319 & Southern_hemi  0.33872242309720185) 
are positive this means that as latitude increases, temperature also tends to increase which could be the case near the poles,
in some specific regions.
Also the strength of the correlation can vary depending on geographic location, season, and other environmental factors


2. The correlation found in the chart between humidity and latitude (Northern Hemisphere:  0.1371217320872958, Southern Hemisphere: 0.03874190741854498) is positive. This suggests that, generally, humidity is higher near the Equator and lower towards the poles, particularly in polar climates. We can conclude that as latitude increases, humidity tends to decrease, especially near the poles where the air is cold, dry, and holds less moisture.
However, the strength of this correlation can vary depending on geographic location, season, and other environmental factors. For example, coastal regions may have higher humidity regardless of their latitude due to the nearby ocean. Similarly, forested regions like the Amazon, which are close to the Equator, may also have higher humidity despite their proximity to the Equator.

3. Also, the strength of the correlation between latitude and cloudiness can vary depending on geographic location, season, and other environmental factors. However, considering the general trends: near the Equator (0° latitude), cloud cover tends to be higher because high temperatures cause more evaporation. In contrast, polar regions (above 60° latitude) tend to have lower cloud cover, as cold air holds less moisture, making cloud formation less frequent.

Given this background, in this analysis, the correlation values for the Northern Hemisphere (0.057172886349690887) and the Southern Hemisphere (0.0021819017018207647) are both closest to 0. This suggests that as latitude increases, cloudiness also increases, though the correlation is quite weak.


4. In regions closest to the Equator (0° Latitude), the air is generally calm because warm air rises due to the high temperatures, resulting in lower wind speeds.
As the latitude increases, wind speeds tend to become more frequent and stronger. 
In this correlation, the Northern Hemisphere has a value of 0.0035, and the Southern Hemisphere has a value of 0.0794. 
Both hemispheres show a positive correlation, meaning that as latitude increases, wind speeds also increase, can vary depending on geographic location, season, and other environmental factors. As we can observed the correlation on the North hemisphere is closest to 0 means there is not a clear correlation on the chart.

## Code WeatherPy LINK
[WeatherPy](WeatherPy\WeatherPy.ipynb)
## Code VacationPy LINK
[VacationPy](WeatherPy\VacationPy.ipynb)

## link of resourse 
https://geo.libretexts.org
