# Project-2
Severe Weather Data

We aim to provide a complete data set composed of 2 different data elements. The first file of data looks at general weather events in the United States.
This data set looks at multiple kinds of weather phenomena from light rain all the way up to heavy hail and storms ranging from 2016-2021.
https://www.kaggle.com/datasets/sobhanmoosavi/us-weather-events


The second data set looks at US storm data.
This data set only looks at storm data across the United States, including states affected and resulting damage from 2013-2020.
(https://www.kaggle.com/datasets/atinakarim/noaa-severe-storm-database?select=Storms_2015.csv)

We will be cleaning this data using Pandas in a Jupyter Notebook. The Weather Event data will be limited down to severe weather events from 2017-2020 and the storm data will be limited to those events occurring between 2017 and 2020 as well. The Data itself is expansive and must be limited to only those years for the sake of file size. The data itself is complete, but is much too broad and extensive for our purposes. The decision to limit the data to these 3 years only was made as a way to keep file sizes down and make the overall data more managable.

From here, the data will be loaded into MongoDB for search queries.

This topic was selected due to the extensive data available on severe weather, and the extent of damage that can be incurred by these storms. In the future with this data, it would be interesting to see if there are any obvious trends as far as months and times of day that these storms can be expected, or if we are truly in the dark when it comes to these forces of nature.
