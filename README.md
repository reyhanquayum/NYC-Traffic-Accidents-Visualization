# NYC Traffic Accidents Analysis (2020)

[View the Full PDF Report Here](./NYC%20Traffic%20Accidents%20Analysis%20(2020).pdf)

## Overview

This project analyzes traffic accident data in New York City for the year 2020. The objective is to identify key patterns, including accident frequency by time, location (borough and specific streets), and potential contributing factors.

- **Author**: Reyhan Quayum
- **Date Completed**: February 27, 2023
- **Focus**: Transportation Safety, Data Analysis, Urban Planning
- **Location**: New York City
- **Time Frame**: January 2020 – December 2020

---

## Dataset

**Source**: [NYC Motor Vehicle Collisions Dataset on NYC Open Data](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
- **Author / Creator**: New York Police Department (NYPD)
- **Publication Date**: Originally published January 2020; latest update December 2020
- **Publisher**: NYC Open Data
- **Data Accessed**: May 26, 2023
- **Format**: csv
- **Size**: 1,420 KB
- **Number of Records**: 74,881
- **License**: [To be confirmed]
- **Fields of Interest**:
    - CRASH DATE and CRASH TIME
    - BOROUGH / LOCATION (LATITUDE, LONGITUDE)
    - CONTRIBUTING FACTOR VEHICLE (1-5)
    - NUMBER OF PERSONS INJURED
    - NUMBER OF PERSONS KILLED
    - VEHICLE TYPE CODE (1-5)
    - ON STREET NAME
    - CROSS STREET NAME
    - OFF STREET NAME

---

## Key Analysis

- **Top Three Streets with Most Accidents**:
    1. BELT PARKWAY (1241 accidents)
    2. LONG ISLAND EXPRESSWAY (745 accidents)
    3. BROOKLYN QUEENS EXPRESSWAY (738 accidents)
- **Number of Accidents by Borough**: Visualized in the report.
- **Summary Statistics for Injuries**: Provided for all of NYC, Manhattan, and Brooklyn.
- **Geographic Distribution of Accidents**: Visualized as a scatter plot by borough.
- **Covariance Analysis**: Calculated between pairs of injury and fatality columns for different groups (persons, pedestrians, motorists, cyclists).
- **Month with Most Accidents**: January (14287 accidents)
- **Month with Least Accidents**: April (4116 accidents)

---

## Report

You can view the final report as a PDF here:

[View the PDF Report](./NYC%20Traffic%20Accidents%20Analysis%20(2020).pdf)

This PDF contains the detailed analysis, visualizations, and conclusions drawn from the 2020 NYC traffic accident data.

---

## Visualizations

- Bar chart showing the number of accidents per borough.
- Scatter plot showing the geographic distribution of accidents by borough (latitude vs. longitude).

![Number of Accidents by Borough](/img/borough_accidents.png)
![Accidents by Borough](/img/geographic_distribution.png)

---

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries:
    - `pandas`
    - `matplotlib`
    - `calendar`