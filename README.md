#D3 Challenge

The health risks facing particular demographics by sifting through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

The data set included is based on 2014 ACS 1-year estimates: [https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml), but you are free to investigate a different data set. The current data set incldes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."

### First Step: D3 Dabbler

Create a scatter plot between two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`.

* Include state abbreviations in the circles.

* Create and situate your axes and labels to the left and bottom of the chart.

### Second Step: More Data, More Dynamics

Include more demographics and more risk factors. Place additional labels in scatter plot and give them click events. Animate the transitions for the circles' locations as well as the range of the axes.

#### Third Step: Incorporate d3-tip

While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Enter tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. 

