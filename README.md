# West-Nile-Causal-Analysis
A detailed analysis on mosquitoes population and how they are affected by various parameters.

I have downloaded the dataset from kaggle. You can access it from here https://www.kaggle.com/krishnasrujan/west-nile-mosquitoes
If the notebook is unable to to viewed , you can view it here
1)  https://nbviewer.jupyter.org/github/krishnasrujan/West-Nile-Causal-Analysis/blob/master/West%20Nile%20Mosquito.ipynb
2)  https://www.kaggle.com/krishnasrujan/west-nile-virus-causal-analysis
# Dataset description:
Main dataset

These test results are organized in such a way that when the number of mosquitoes exceed 50, they are split into another record (another row in the dataset), such that the number of mosquitoes are capped at 50.

The location of the traps are described by the block number and street name. For your convenience, we have mapped these attributes into Longitude and Latitude in the dataset. Please note that these are derived locations. For example, Block=79, and Street= "W FOSTER AVE" gives us an approximate address of "7900 W FOSTER AVE, Chicago, IL", which translates to (41.974089,-87.824812) on the map.

Some traps are "satellite traps". These are traps that are set up near (usually within 6 blocks) an established trap to enhance surveillance efforts. Satellite traps are post fixed with letters. For example, T220A is a satellite trap to T220.

Please note that not all the locations are tested at all times. Also, records exist only when a particular species of mosquitoes is found at a certain trap at a certain time. In the test set, we ask you for all combinations/permutations of possible predictions and are only scoring the observed ones.

Spray Data

The City of Chicago also does spraying to kill mosquitoes. You are given the GIS data for their spray efforts in 2011 and 2013. Spraying can reduce the number of mosquitoes in the area, and therefore might eliminate the appearance of West Nile virus.

Weather Data

It is believed that hot and dry conditions are more favorable for West Nile virus than cold and wet. We provide you with the dataset from NOAA of the weather conditions of 2007 to 2014, during the months of the tests.

Station 1: CHICAGO O'HARE INTERNATIONAL AIRPORT Lat: 41.995 Lon: -87.933 Elev: 662 ft. above sea level
Station 2: CHICAGO MIDWAY INTL ARPT Lat: 41.786 Lon: -87.752 Elev: 612 ft. above sea level


# My Work:

I have done a detailed analysis on mosquito population. 
Mosquitoes population is more in July and August. 
Goverment took a good step to spray mosquito repelent gas which ultimately decreased the population of mosquitoes. 
Analysis is also on how the population of mosquitoes is affected by various environmental parameters.
