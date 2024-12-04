# Thomas Fire Analysis
### Environmental Data Science 220 Fall 2024 - Final Project 
![Firefighter and white truck in front of a burning hillside](https://live.staticflickr.com/4681/25378265228_ce1b5a68d1_b.jpg)

## Description 
This project provides an in-depth analysis of the Thomas Fire, which burned over 280,000 acres in Ventura and Santa Barbara counties in December 2017. The first part of the analysis examines air quality impacts using Air Quality Index (AQI) data from the US Environmental Protection Agency, visualizing how air quality changed over time during and after the fire. The second part focuses on the fire's physical impact, leveraging Landsat 8 satellite imagery and historic fire perimeter data. By applying false-color imaging techniques, this analysis highlights fire scars and assesses vegetation health in the affected areas.

## Repository Structure 
This repository contains four Jupyter Notebooks, three of which were the original notebooks used for the analysis while the other, `thomas-fire-blog`, accumulates the information for a data science blog post. 

```
thomas-fire-analysis
│   README.md
|   .gitignore
│
└───notebooks
    │  aqi-thomas-fire.ipynb
    │  false-color-thomas-fire.ipynb
    │  fire-perimeter-thomas-fire.ipynb
    │  thomas-fire-blog.ipynb   

└───data
    │ landsat8-2018-01-26-sb-simplified.nc 
    │ thomas.cpg
    │ thomas.dbf
    │ thomas.prj
    │ thomas.shp
    │ thomas.shx
```
## Data Access 

This project required three datasets to provide the air quality data, remote sensing data, and fire perimeter data. 

1.   Air Quality Index (AQI) Data The AQI data comes from the US Environmental Protection Agency. It includes daily air quality index score for Santa Barbara county. The links to download this data can be found here: [2017 AQI](https://aqs.epa.gov/aqsweb/airdata/daily_aqi_by_county_2017.zip) and [2018 AQI](https://aqs.epa.gov/aqsweb/airdata/daily_aqi_by_county_2018.zip)
2.  Landsat Collection 2 Level-2 atmospherically corrected surface reflectance data, retrieved from the Microsoft Planetary Computer [data catalogue](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2)
3.  Historical Fire Perimeter dataset from The Fire and Resource Assessment Program presented by [Cal Fire](https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436). 

## References and Data Sources 

Environmental Protection Agency (EPA). Air Quality Index (AQI) Data. https://aqs.epa.gov/aqsweb/airdata/download_files.html (Accessed October, 2024)

Earth Resources Observation and Science (EROS) Center. (2020). Landsat 8-9 Operational Land Imager / Thermal Infrared Sensor Level-2, Collection 2 [dataset]. U.S. Geological Survey. https://doi.org/10.5066/P9OGBGM6 (Access Novemeber, 2024)

California Department of Forestry and Fire Protection (CAL FIRE). (2023). California fire perimeters (all). Data.gov. https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436 (Accessed November, 2024)

## Author 
Jordan Sibley 

Master of Environmental Data Science Student, Bren School of Environmental Science & Management

jcsibley@bren.ucsb.edu

jordan.c.sibley@gmail.com 

## Acknowledgments 
The material for this assignment was presented by Dr. Carmen Galaz García in the course *Working with Environmental Datasets* (EDS 220) at the Bren School of Environmental Science & Management, Fall 2024.

