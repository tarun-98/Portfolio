
Portfolio projects

1. <u>Portfolio 1</u>: Analysis of Cycling Data
 - Data set 1- The first dataset is an export of my ride data from [Strava](https://strava.com/), an online social 
network site for cycling and other sports.  This data is a log of every ride since the start of 2018
and contains summary data like the distance and average speed.  It was exported using 
the script `stravaget.py` which uses the stravalib module to read data. Some details of
the fields exported by that script can be seen in [the documentation for stravalib](https://pythonhosted.org/stravalib/api.html#stravalib.model.Activity).
- Data set 2-The second dataset comes from an application called GoldenCheetah which provides some analytics services over ride data. This has some of the same fields but adds a lot of analysis of the power, speed and heart rate data in each ride. This data overlaps with the Strava data but doesn't include all of the same rides.
- Tasks- Performed Data analysis and explored distribution of data using Histograms, density plots, box plots, Time Series analysis and scatter plots. The relationship between variables is measured using scatter matrix.

2. <u>Portfolio 2</u>: Predicting the energy usage of a house based on IoT measurements of temperature and humidity and weather observations
- Data set- [energydata_complete.csv](https://github.com/LuisM78/Appliances-energy-prediction-data)
-  Tasks-
     - Task1 - Data analysis: Explored distribution of data using Histograms, box plots, Time Series analysis, pairwise plot and heatmaps.  Histograms are used to identify the distribution and boxplots divulges the outliers present in the data. Time series graphs are constructed to identify Energy consumption profile for a particular period. Heatmaps is the good way to reperesent data for a particular period. In this portfolio i have used heatmaps to represent hourly energy consumption for four consecutive weeks.
     - Task2- Constructed a linear model. Plotted the residual vs Actual value graph 
     - Task3- Used Recursive Feature Estimation to identify and compare the accuaracies of model built on different number of features
   
