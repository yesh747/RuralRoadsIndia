# RuralRoadsIndia

## Data Cleaning
Data_Cleaning.Rmd was used to clean and organize data from the Indian Human Development Survey I and II (ihds.info). The cleaned data was ouput into **ruralHealthAndRoadsOfIndianVillages.csv** for 2005 and 2012 panel data. ruralHealthAndRoadsOfIndianVillages2005.csv and ruralHealthAndRoadsOfIndianVillages2012.csv contain cleaned data from only those years. 

In Data_Cleaning.Rmd, you must point the load raw data commands for Individual, Household, and Village data to the raw IHDS data before running the file. Instructions for obtaining raw IHDS data are found at ihds.info. **The cleaned data has already been outputted to .csv files, so it is NOT necessary to run this file before running Data_Analysis.Rmd.**


## Data Analysis
The Data_Analysis.Rmd conducts graphical and regression analysis on the cleaned IHDS data. Regressions are sometimes output into .html files via the stargazer library.
