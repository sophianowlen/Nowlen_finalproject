## Sophia Nowlen Final Project: Quantifying Elevation changes compared to SLR rate in South Slough NERR

### Goals 
#### - To analyze, test the significance of, and report on differing site-level elevation changes in the South Slough and gain in sight into how they may do in comparison to the local rate of sea level rise (SLR)
#### - To better understand time series data, especially for long-interval studies and how to quantify/plot that

### Motivation
#### - This project will build on my summer internship and capstone work. This summer I interned as a field tech with NOAA at the South Slough National Estuarine Research Reserve. My motivation is to interpret the data I helped collect in a meaningful, informative way and add to my 496 project relevance as well. My audience is my fellow MACS peers as well as general scientists interested in estuarine dynamics/elevation data. 

### Data
#### I will be using metadata from the project that is already in my finalproject repository; I included an example of code I will call below the general outline

### Analysis methods 
#### - A time series analysis (yet to learn, but will go over in class soon)
#### - A linear regression per site to show change over time
#### - Significance tests to show if rates of SLR are significantly lower/higher than SLR at the 95% confidence level 
#### - Figures which show the above! regression rates plotted against SLR and significance plots (color coded maybe?) 
##### - I will use pandas, matplotlib, and numpy to start but probably more

### Conclusions
#### - Because I have done some analysis already, I know most sites are doing significantly or insignificantly well compared to SLR, despite 2 sites losing elevation pretty rapidly. This data is really important for climate change contexts as SLR increases and estuaries must migrate/lose ground! 

### References
#### - My mentor Jenni Schmitt, as well as articles I have referenced in my writing. I will also reference any lab or help I got for the data refinement operations. 


## General Outline
#### - load data
#### - subset data into site-specific categories, run regression for change in elevation over time 
#### - find significance with any relevant statistical tests that are significantly below/above SLR rate
#### - plot change in elevation over time against rate of local SLR 
#### - finalize and summarize findings

##### Step 1: load data
##### import pandas as pd 
##### df = pd.read_csv("sosset_metadata.csv")
##### df.head


