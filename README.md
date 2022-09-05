
# Fall2022_OPIOD_Team

We are a Team of four students and below are the details. 

<li>Priyanka  Budavi - Graduate</li>
<li> Aditi Darandale - Graduate</li>
<li> Manish Shah - Graduate</li>
<li> Raveena Rakesh Arasikere  - Graduate</li>



## Table of Contents
* [Overview](#Overview)
* [The project status](#The-project-status)
  + [Stage 1 Data Understanding and Linking](#Stage-1-Data Understanding and Linking)
  + [Stage 2 Data Modeling](#stage-2-data-modeling)
  + [Stage 3 Distributions and Hypothesis Testing](#stage-3-Distributions and Hypothesis Testing)
  + [Stage 4 Dashboard](#stage-4-Dasboard)
  
* [Technologies](#Technologies)
* [Setup](#Setup)


## Overview

Coronavirus is a continuing worldwide pandemic, which has affected a lot of people including you. In this project we are trying to understand and analyse the various datasets regarding the spread of COVID-19 in various regions of the United States. Also one can read the data set, plot graphs to learn about trends of Covid spread and merge multiple data sets into single one. 
 
## The project status 

In Stage-1 we are trying to understand the different Enrichment stage and relate with the COVID-19 dataset. Using Python libraries we perform data wrangling with the COVID and enrichment dataset so that these files could be merged to analyze the spread of COVID19 pandemic.

In Stage -2  we develop the data for modeling and comparative analysis. We compare the cases and deaths of the US with other countries and also analyze the data at state level and county level. We perform statistical analysis and compare how COVID has affected at country , State and county level and visualize the graphs using plotly. 


### Stage 1: Information about the assigned enrichment datasets 

<li>ACS Social, Economic, and Housing Dataset - Kyle Killworth</li>
<li>Presidential Election Results (Political leanings) - Reetika Sarkar </li>
<li>Hospital Beds Dataset -  Priyanka Budavi</li>
<li>Census Demographic ACS - Manish Shah </li>
<li>Employment Dataset  - Aditi Darandale </li>

### Stage 2: Data Modeling

The data used in stage 2 is the merged COVID dataset for the US and the world COVID dataset. We compare the weekly statistics pertaining to the weekly average counts of new cases and deaths across the US. We also compare these with other countries that have population density comparable to that of the US and draw preliminary inferences. We plot the counts for the chosen countries to observe increasing or decreasing trends and peaks in COVID-19 cases and deaths in the US and the chosen countries. We try to find out the underlying causes for the observed trends in the data by doing some background research (due to reasons such as holidays, vacations, vaccinations, etc).  

### Stage 3 : Hypothesis and Distribution

The goal of Stage III is to develop distributions and formal hypothesis tests for the intuitions you had in Stage I and II and utilize statistical modeling to prove/disprove them.

### Stage 4 : Basic Machine Learning

The goal of Stage IV is to utlize machine learning and statistical models to predict the trend of COVID-19 cases / deaths.


### Stage 5 : Dasboard

The final stage aims a developing a simple interactive dashboard based on the analysis you have done so far. In this we will be utilizing Plotly (https://plotly.com/) along with Dash (https://plotly.com/dash/) as our framework.

## Technologies
   Project is created with : 
    <li> 1. Python </li>
    <li> 2. Jupyter Notebook </li>
     
     
## Setup
Download the github repository either using https or SSH, and open the required file in jupyter notebook from the src folder.
The Link for the dataset can be downloaded/viewed from the below links : 
  1. https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_confirmed_usafacts.csv  - No. of cases 
  2. https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_deaths_usafacts.csv - No. of deaths
  3. https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_county_population_usafacts.csv  - Population by county

