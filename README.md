## Visualizing CPS' annual budget for public schools in 2020

This project visualizes the Chicago Public School board's annual budget for public schools in 2020 as an interactive chloropleth map. The map is broken down by each zipcode in Cook County and color coded according to the amount of money spent. 
![CPS FY 2020 Annual Budget by Zipcode](reports/sample_output/image1.png?raw=true "Optional Title")

It also features markers that indicate the location of each public school, providing details on the number of teaching staff at the school and its individual budget.
![CPS FY 2020 Annual Budget by Zipcode](reports/sample_output/image3.png?raw=true "Optional Title")

### Core Technical Concepts/Inspiration

* Python 3.8.5
* [Folium 0.1.6](https://pypi.org/project/folium/0.1.6/)

### Things to know/Bugs
* Google Maps API limits
* Latitude, longitude data gathering is time consuming

### Data Sources
* [CPS Annual Budget](https://biportal.cps.edu/analytics/saw.dll?Portal)
* [Cook County GeoJSON](https://data.cityofchicago.org/)

### Contact
* Email: narottammedhora@gmail.com

### License
* [MIT License](LICENSE)
