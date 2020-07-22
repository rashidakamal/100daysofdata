# NYC Civilian Complaints Review Board - Allegations Data

I'm starting off this endeavor in a easy note -- this is a dataset I've worked with before, and in fact, ran an ["Introduction to Data Visualization with Python + Adobe Illustrator"](https://docs.google.com/presentation/d/1X69-d6EAPBBf_ncV0V0-MEO6IY-PXmATZFJpgkoc1Yo/edit#slide=id.g888cfe5bb7_1_39) workshop for ITP Camp 2020 earlier this summer, in which I centered my work in this data. However, as the workshop did not emphasize the final output, I thought this would be a nice opportunity to revisit the dataset. 

Original data source [here](https://data.cityofnewyork.us/Public-Safety/Civilian-Complaint-Review-Board-CCRB-Allegations-C/xyq2-jjkn). 

## Day 1: Python + Illustrator Output

![Histogram chart showing distribution of the number days it took to close allegations before the CCRB.](output/final-chart.png)

* Median is a helpful measure when the data is skewed or has outliers as it is ["robust against outliers"](https://www.clinfo.eu/mean-median/). In this case, I included both mean and median, as they were not wildly different from one another. 

## Day 2: D3 / HTML / CSS

+ [Observable for Jupyter Users](https://observablehq.com/@observablehq/observable-for-jupyter-users)
    + I probably won't use Observable just yet, but I'm interested to see if this can become a helpful part of my workflow for future "Day 2" endeavors. 
    + **Observable’s not JavaScript** – learning this the hard way. 
    + [Observable: Charting with Vega-Lite](https://observablehq.com/@observablehq/vega-lite)
+ [Changes between D3v4 & D3v5](https://github.com/d3/d3/blob/master/CHANGES.md): everything I used to know is obsolete (sort of).

![Radial Stacked bar chart showing the number of allegations by type.](output/radial_stacked_chart.png)

## Day 3: After Effects