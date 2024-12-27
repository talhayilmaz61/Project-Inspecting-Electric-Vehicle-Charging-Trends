# Project-Inspecting-Electric-Vehicle-Charging-Trends
Dive into a decade of data from the US Government's Alternative Fuels Data Center to uncover trends in electric vehicle charging infrastructure. From the rise of public and private charging ports to yearly shifts in EV sales, this project visualizes the future of sustainable mobility.


Does increased electric vehicle sales lead to more public or private charging ports?

How many vehicles were sold in 2018 in total? Save the answer as a numeric variable called ev_sales_2018.
Plot trends for private ports, public ports, and sales, saving this as fig, ax objects.
Did vehicle sales and number of private and public ports show the same trend (either increasing or decreasing) between the years 2015 and 2018? Save your answer as same or different to a variable called trend.


### The Data
&nbsp;

`private_ev_charging.csv`

| Variable   | Description                                          |
|------------|------------------------------------------------------|
| `year` |  Year of data collection |
| `private_ports`| The number of available charging ports owned by private companies in a given year  |
| `private_station_locations`   | The number of privately owned station locations for EV charging

___

`public_ev_charging.csv`
 
| Variable   | Description                                          |
|------------|------------------------------------------------------|
| `year` |  Year of data collection  |
| `public_ports`| The number of available charging ports under public ownership in a given year  |
| `public_station_locations`   | The number of publicly owned station locations for EV charging

___

The sales information is available for each model and year in the `ev_sales.csv` file:

| Variable   | Description                                          |
|------------|------------------------------------------------------|
| `Vehicle` |  Electric vehicle model |
| `year`| Year of data collection |
| `sales`   | The number of vehicles sold in the US
