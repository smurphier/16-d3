# Unit 16 | Assignment - Data Journalism and D3
## Background
A data visualization position for an article analyzing trends in health risks facing particular demographics, to aid sifting through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

The data set included here is based on 2014 ACS 1-year estimates: [https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml), and inludes rates of income, obesity, poverty, etc. by state. (MOE stands for "margin of error.")

### Level 1: Scatter Plot
![4-scatter](Images/4-scatter.jpg)
* Create a scatter plot between two data variables (eg. `Healthcare vs. Age` or `Smokers vs. Poverty`).
* Create a scatter plot; represent each state with circle elements — pull data from `data.csv` using `d3.csv` function. 

* Include state abbreviations in the circles.
* Create and situate your axes and labels to the left and bottom of the chart.

* Note: You'll need to use `python -m http.server` to run the visualization. This will host the page at `localhost:8000` in your web browser.

- - -

### Level 2: Optional Challenge 
![7-animated-scatter](Images/7-animated-scatter.gif)

#### 1. More Data, More Dynamics
Include more demographics and more risk factors. Place additional labels in your scatter plot and give them click events so that users can decide which data to display. Animate the transitions for your circles' locations as well as the range of your axes. Do this for two risk factors for each axis. For an extreme challenge, create three for each axis.
* Hint: Try binding ALL of the CSV data to your circles, to easily determine their x or y values when you click the labels.

#### 2. Incorporate d3-tip
While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Enter tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. Add tooltips to your circles and display each tooltip with the data that the user has selected. Use the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged)—we've already included this plugin in your assignment directory.
![8-tooltip](Images/8-tooltip.gif)
* Check out [David Gotz's example](https://bl.ocks.org/davegotz/bd54b56723c154d25eedde6504d30ad7) to see how to implement tooltips with d3-tip.
- - -

## Copyright
Work of a Rice University Data Boot Camp Student © 2018. All Rights Reserved.
