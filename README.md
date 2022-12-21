# Examining the push for year-round daylight saving time

[Click here to view the visualizations on the web](http://juliaingram.github.io/daylight-saving)

This repo contains the code, graphics, and Illustrator files to visualize state legislatures' efforts to end biannual clock-switching and a map of when sunrise and sunset would take place across the U.S. if the country were to switch to year-round daylight time. 

To build these graphics, I scraped data from the National Conference of State Legislatures on state legislation to on daylight saving time in 2020, 2021 and 2022, and then created graphics in plotnine to visualize that legislation. I modified the SVG files in Adobe Illustrator and used ai2html to make them responsive on the web.

I also scraped the latitude and longitude of about 975 U.S. cities from [LatLong.net](https://www.latlong.net/category/cities-236-15-1.html) and used that geographic information to pull sunrise and sunset times from the [sunrise-sunset.org API](https://sunrise-sunset.org/api). These times are modified to show the time of sunrise and sunset on Jan. 1, 2022 if the U.S. observed daylight saving time year-round. 

Jupyter notebook [daylight-savings.ipynb](daylight-savings.ipynb) contains the code for the data collection and preliminary graphics.
