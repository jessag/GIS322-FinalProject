# Analysis of Single-Motherhood and Poverty

## Python 3.6

## Introduction
The purpose of this project is to explore if and to  what degree a state’s single motherhood rate impacts the state’s poverty rate. The analysis was conducted exclusively within the Python environment. Given that the analysis was a single linear regression analysis, the statistical significance of the findings were scrutinzed and limitations discussed. To provide an understanding of any geographic patterns embedded within the poverty and single motherhood data, two interactive choropleth maps were produced. As such, the reader can develop a more robust understanding of not only if there is a statistically significant relationship between the discussed variables, but where the relationship appears most pronounced.
 

## General Tasks Accomplished
Importing geodatabases, cleaning data, performing attribute merges, calculating and graphing simple linear regression, and generating interactive choropleth map visualizations.

## Implemented Libraries
A variety of libraries and packages were applied, including GeoPandas, Pandas, matplotlib, statsmodels, Numpy, and Bokeh.


## Data
All data involved was derived exclusively from the United States Census Bureau, 2019 5-year ACS estimates.




## Results

The regression analysis gave enough statistically significant evidence to warrant the rejection of 
the null hypothesis – that single motherhood does not affect poverty rates. The resulting choropleth maps 
highlight that the southeast region of the United States suffers from a high poverty and single motherhood 
rates. The northeast and northwest United States have low poverty and single motherhood rates.
While this project discovered an interesting positive relationship between poverty and single 
motherhood rates, a study involving the analysis of multiple variables and how they impact the poverty 
rate is  likely to generate an actionable model.
Meeting socio-cultural discourse with findings from statistical analyses can generate effective 
responses to crises within the United States. It is the purpose of this project to provide policy makers with 
the adequate and sound evidence that is needed for the institution of viable public policies.






### Interactive Choropleth Maps (static images below, only)
![SM_Choropleth](https://user-images.githubusercontent.com/54545486/115966107-19a87780-a4e1-11eb-9c51-64387e41bdb1.JPG)


![Poverty_Choro](https://user-images.githubusercontent.com/54545486/115966118-24fba300-a4e1-11eb-826d-937f4d16ea8b.JPG)


### Statistical Analysis

![OLS_snap](https://user-images.githubusercontent.com/54545486/115966159-49577f80-a4e1-11eb-8a4a-0b49cbc7092d.JPG)


![Regression_Snap](https://user-images.githubusercontent.com/54545486/115966163-507e8d80-a4e1-11eb-9055-be11f49e3bde.JPG)


### Sources that helped me develop this project

Beers, Brian. (2021, April 15). P-Value. Retrieved from https://www.investopedia.com/terms/p/pvalue.asp

Geeks for Geeks. (2020, July 17). Ordinary Least Square (OLS) using statsmodels. Retrieved from 
https://www.geeksforgeeks.org/ordinary-least-squares-ols-using-statsmodels/?ref=rp.

Geeks for Geeks. (2020, April 21). Plot Mathematical Expressions in Python using Matplotlib. Retrieved 
from https://www.geeksforgeeks.org/plot-mathematical-expressions-in-python-using-matplotlib/.

Geospatial Technology. (2019, August 21). What is a TIGER file? Retrieved from 
https://mapasyst.extension.org/what-is-a-tiger-file/

GeoPandas. (n.d.). GeoPandas 0.9.0. Retrieved from https://geopandas.org/.

Stojiljkovic, Mirko. (n.d.). Linear Regression in Python. Retrieved from https://realpython.com/linearregression-in-python/#implementing-linear-regression-in-python

United States Census Bureau. (n.d.). When to Use 1-year, 3-year, or 5-year Estimates. Retrieved from 
https://www.census.gov/programs-surveys/acs/guidance/estimates.html.

### Data Sources

United States Census Bureau, American Community Survey. (2019). Poverty Status in the Past 12 
months. Retrieved from 
https://data.census.gov/cedsci/table?t=Poverty&g=0100000US.04000.001&tid=ACSST5Y2019.S
1701&hidePreview=true

United States Census Bureau, American Community Survey. (2019). Selected Social Characteristics in 
the United States. Retrieved from
https://data.census.gov/cedsci/table?t=Families%20and%20Living%20Arrangements&g=010000
0US.04000.001&tid=ACSDP5Y2019.DP02&hidePreview=tru


## Status of Project
Completed as planned. However, this was a simple statistical analysis. I would like to aggregate more data sources to create a more reliable model by using
mulitple linear regression as opposed to simple linear regression.



