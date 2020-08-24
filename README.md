# airpollution

A GitHub repository aimed at distinguishing the primary causes of air pollution across the 15 largest metropolitan statistical areas in the United States.

## Requirements

* Python 3 
Libraries:
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Glob

## About The Study

This research project is conducted under Renaissance Learning. Made possible by Data Scientist Jon Stelman and the company, the study connects metropolitan statistical areas (MSAs) across the country and compares air quality based on the two major pollutants: O3 and PM2.5. We compare input variables such as temperature, production/GDP, energy consumption, as well as commuting with air quality and overlay their trends to gain a better understanding of what truly causes bad air and how it differentiates based on the area.

## Notebooks

The notebooks are separated into four notebooks: an overview air pollution notebook, a processing notebook, a visualization notebook, as well as an analysis notebook.

The overview air pollution notebook olds some very simple graphs of raw data and short exploration.

The processing notebook holds all of the functions we use to graph and visualize. We also read all of the data within this notebook, and simply run it within the other notebooks so the functions and data transfer.

The visualization notebook holds all of the visualizations across every metropolitan statistical area organized by region. It displays air quality in comparison to the numerous input variables, being a location for all of the graphs we need to research.

The data analysis notebook follows a similar structure to the presentation and paper, outlining the project, the findings, as well as the general story and line of reasoning.

## Data

We conduct basic data handling using our Python libraries to clean up data and visualize it properly. We incorporate time series line plots and bar charts as well as correlation matrices to display our data and develop findings based on the trends we see. Our data has limitations, where comparisons between data may not be the most consistent. 

## Acknowledgement

A special thank you to Jon Stelman, the LSI Team, as well as the whole of Renaissance Learning for creating the opportunity for this study and supporting it every step of the way.
