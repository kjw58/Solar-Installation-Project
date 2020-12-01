This repository contains all information for our AIPI 510: Sourcing Data for Analytics Final Course Project: Holistic Approach to Solar 
Energy in the US.

Our model explored states that solar developers should consider investing in for future solar projects. We created our model based on 
3 different factors - Profit Opportunity, Market Factor, and Weather Factor. Our Profit Opportunity was generated using 3 of our data sets:
Technical Potential, Existing Generation and Electricity Price. Our Market Factor used 2 features that were created from our original
Electricity Price and Existing Generation data sets - electricity price percent change from 2017 to 2019 and electricity uptake (or existing
generation) percent change from 2017-2019. We chose to use the the time frame from 2017-2019 to explore the last 3 years of this data. Finally,
our Weather Factor was created using 4 data sets built by web scraping from the Current Results website - Sunny Hours, Snow Days, Clear Days, 
and Average Temperature.  

The structure of our code is organized into several sections representing each data set:

Importing Packages

Weather Data Exploration
	- Weather Data Set Features
	- Feature Selection
	- Weather Factor Features

Technical Potential Data Exploration
	- Technical Potential Data Set Features
	- Data Processing
	- Data Visualization

Electricity Price Data Exploration
	- Electricity Price Data Set Features
	- Data Processing
	- Data Visualization

Existing Generation Data Visualization
	- Existing Generation Data Set Features
	- Data Processing
	- Data Visualization

Overall Analysis of our Project
	- Data Processing
	- Data Visualization of Development Opportunity and Benefit Opportunity
	- Data Visualization of Market Factor
	- Data Visualization of Weather Factor
	- Data Visualization of All Combined Factors 

The data processing sections include the code used to create each data frame/factor that contributed to our solar installation model: 
Profit Opportunity, Market Factor, and Weather Factor, while Data Visualization includes exploratory visualizations to better understand 
each data set and determine feature selection. Our final section on Overall Analysis includes data visualization/exploration of each data 
frame we built to develop the model factors that contributed to our final model approach.

Instructions for Running Code:

1. Download all data csv files. Each should be included in our zip folder.

2. Import all packages and install Geopandas to visualize U.S. heatmaps generated in Weather Data, Technical Potential, and Existing
	Generation Data Visualization. This should be done automatically once you run the code.

3. Run all code.

Code by Katie Wu, Zheyou Guo, and Tejas Patel