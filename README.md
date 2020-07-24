# project-property

team name : The ethical developers
team member: 1. Dan Elvey 2. Kenjiro Hirota 3. Parker Wai
project proposal: analysing census datasets in relation to affordable housing

# Project Question: What factors attribute to the Affordability Index in suburbs of Greater Perth?

# Research objectives:
To utilise available datasets from ABS census
To calculate the Purchasing and Rental Affordability Index across suburbs of Greater Perth
To investigate the factors that influence the Affordability Index

# Data source
http://stat.data.abs.gov.au/

# Data gathering
Create API query using http://stat.data.abs.gov.au/sdmx-json/ Query generator

income.ipynb: To calcualte median income of each SA2 area. 
mortgage.ipynb: to To calcualte median mortgage repayment of each SA2 area. 
rent.ipynb: to To calcualte median rent of each SA2 area. 
other_data.ipynb: to gather the other data (demographic factors) of each SA2 area. 

# Data cleansing and plotting
ProjectCombined.ipynb: to merge all data gathered avobe and save it as one df. Usign this, generate scatter plot to see between which data we can see correlation.

# Data visualization (mapping)
gmaps.ipynb gives heat map of rent, but it's not exactly aligned with SA2 area, so usign GIS, generated mapping with certain layor. 
