# matplotlib-challenge
Bootcamp matplotlib homework

Provided with study data of 249 mice identified with SCC tumor growth treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 
The datafiles are provided in the data folder.

Tasks completed in the jupyter notebook (Pymaceuticals/pymaceuticals.ipynb)
* removed data of mouse id w/dubious duplicate data
* merged the data from 2 csv files into 1 dataframe
* provided summary stats (mean, median, var, std) of tumor volume using 2 different methods
* created bar chart of number of measurements taken per drug regimen using 2 methods (pandaplot and matplotlib.pyplot)

* created pie charts showing count male/female study mice using 2 methods (pandaplot and matplotlib.pyplot)

* For 4 promising drugs: Capomulin, Ramicane, Infubinol, and Ceftamin, calculated Quartiles, found possible outliers and plotted boxplot

* used line plot to show Mouse ID m957 tumor volume over time

* created a scatter plot of average tumor volume vs. mouse weight for the Capomulin regimen
* performed correlation and regression calcs for the average tumor volume vs. mouse weight for the Capomulin regimen data.