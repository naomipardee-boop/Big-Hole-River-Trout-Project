# Big Hole River Trout and Water Conditions Project

## Topic
Can trout populations in the Big Hole River be used to predict low (or high) water years?

## Broad Plan for the Analysis/Product Stage
My main research question is whether measures of trout populations in the Big Hole River are associated with, and potentially useful for predicting, low-water or high-water years. To answer this question, I plan to combine trout population data with water-related data such as streamflow, drought conditions, snowpack, or seasonal water levels over time.

I will then use descriptive analysis and basic statistical methods to look for patterns and relationships between fish population measures and water-year conditions. My goal is to see whether trout populations respond consistently enough to water conditions that they could serve as an indicator of unusually low or high-water years.

## Challenge
For my challenge, I want to create an interactive visualization of trout population data and water conditions along the Big Hole River. I plan to use a visualization tool in R to map sampling locations and display changes in trout populations or water levels over time rather than relying only on static graphical analysis.

I am also considering a challenge where I build an interactive dashboard using R shiny. The dashboard could allow users to explore trout population data, streamflow levels, and other environmental variables over time. Users could select specific years or river segments and see how trout populations change relative to water conditions.

## Data Sources

### 1. USGS Streamflow Data
Source: https://waterdata.usgs.gov

This dataset contains hydrological measurements from USGS monitoring stations, including variables such as stream discharge (cubic feet per second), water levels, and monitoring dates. The data typically spans several decades and is collected daily at specific gauge locations along rivers. For this project, data from gauges on the Big Hole River will be used to measure water conditions over time.

Spatial coverage: Monitoring stations located along the Big Hole River in Montana.  
Time span: 1980 - 2018

This dataset will provide the primary measure of water availability and variability, which can be compared to trout population data.

### 2. Montana Fish, Wildlife & Parks Trout Population Data
Source: https://fwp.mt.gov

Montana Fish, Wildlife & Parks conducts fisheries monitoring that includes trout population surveys using electrofishing and other sampling methods. These datasets typically contain variables such as species counts, fish density (fish per mile), biomass estimates, survey location, and survey year.

Spatial coverage: Sections of the Big Hole River where fisheries surveys are conducted.  
Time span: 1980 - 2018

This dataset provides information on trout population levels that will be compared with water conditions.

### 3. NOAA Climate Data Online
Source: https://www.ncdc.noaa.gov/cdo-web/

NOAA Climate Data Online provides historical climate data such as precipitation, temperature, and weather observations from monitoring stations. These variables help capture broader environmental conditions that influence river flow and aquatic ecosystems.

Spatial coverage: Weather stations in or near the Big Hole River watershed.  
Time span: 1980 - 2018

Climate variables will help explain environmental conditions that may influence both streamflow and trout populations.

### 4. U.S. Drought Monitor
Source: https://droughtmonitor.unl.edu

The U.S. Drought Monitor provides historical drought classifications for regions across the United States. Data includes drought severity categories over time (e.g., moderate drought, severe drought).

Spatial coverage: Regional drought conditions across Montana and the Big Hole watershed.  
Time span: 2000 - 2010

This dataset will help identify drought periods that may correspond with changes in water availability and trout populations.

## Relationship Between the Datasets
These datasets together provide information on fish populations, hydrological conditions, and environmental factors affecting the Big Hole River ecosystem. Trout population surveys provide biological data, while streamflow, climate, and drought datasets provide environmental context. By combining these datasets over time, the analysis will explore whether trout populations show consistent patterns in relation to water availability or drought conditions.

## Repository Purpose
This repository contains the project planning materials, data sources, and analysis code for investigating whether trout populations in the Big Hole River can be used to predict low or high water years.
