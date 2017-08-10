-# DDP-Week3-Presentation
 -
 -Instructions
 -
 -Create a web page presentation using R Markdown that features a plot created with Plotly. Host your webpage on either GitHub Pages, RPubs, or NeoCities. Your webpage must contain the date that you created the document, and it must contain a plot created with Plotly. We would love to see you show off your creativity!
 -Review criterialess 
 -The rubric contains the following two questions:
 -
 -Does the web page feature a date and is this date less than two months before the date that you're grading this assignment?
 -Is the web page a presentation and does it feature an interactive plot that appears to have been created with Plotly?
 -Example Submissionsless 
 -Here's an extremely minimal passing example, but we hope your submission is much cooler!
 -
 -# What I did!
 -
 -I used the nasa data set in R, adjusted the temperature from Kelvin to Farienheight. I then created a 3D scatter plot of the various levels of cloud cover (High, Mid and Low) and stratified the plot color accross temperature.


-# NASA spatio-temporal data

-## Description

This data comes from the ASA 2007 data expo, http://stat-computing.org/dataexpo/2006/. The data are geographic and atmospheric measures on a very coarse 24 by 24 grid covering Central America. The variables are: temperature (surface and air), ozone, air pressure, and cloud cover (low, mid, and high). All variables are monthly averages, with observations for Jan 1995 to Dec 2000. These data were obtained from the NASA Langley Research Center Atmospheric Sciences Data Center (with permission; see important copyright terms below).

-## Usage

nasa
-## Format

A tbl_cube with 41,472 observations.

-## Dimensions

lat, long: latitude and longitude

year, month: month and year

-## Measures

cloudlow, cloudmed, cloudhigh: cloud cover at three heights

ozone

surftemp and temperature

pressure

-## Examples

nasa
