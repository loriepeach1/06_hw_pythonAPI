# Python and Data Retrieval via APIs

## Overview

This project proved what we already know - in general, the wether is warmer near the equator.    500 random lat and long coordinates were generated from the citipy library.    For each lat and long, the city weather details were obtained via an API call to openWeatherMap.    Finally, via a python script the weather of 500+ cities across the world of varying distance from the equator could be visualized.


![Temperature](ReadMeImages/fig1_latitudeTemp.png)

<br>
![Humidity](ReadMeImages/fig2_latitudeHumidity.png)

<br>    
![Cloudiness](ReadMeImages/fig3_latitudeCloudiness.png)

<br>    
![Wind_speed](ReadMeImages/fig4_latitudeWindSpeed.png)

## Tools & Technologies Used: 

* OpenWeatherMap API (using API key)
* citipy python library
* Jupyter notebook

* import matplotlib.pyplot as plt
* import pandas as pd
* import datetime as dt
* import numpy as np
* import requests
* import time
* import json

## Assignment Details

Your objective is to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Your final notebook must:

* Randomly select **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed with the city number and city name.
* Save both a CSV of all data retrieved and png images for each scatter plot.

As final considerations:

* You must complete your analysis using a Jupyter notebook.
* You must use the Matplotlib or Pandas plotting libraries.


## Copyright

Data Boot Camp © 2018. All Rights Reserved.
