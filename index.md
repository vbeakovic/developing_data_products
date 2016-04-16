---
title       : Developing Data Products Course Project
subtitle    : A Shiny app to explore and model the Iris dataset
author      : Valter Beaković
job         : Coursera student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## About the Shiny app


&nbsp;
&nbsp;


The app provides and interactive interface to explore and model the Iris dataset.

It has three main parts:

* Exploring the dataset
* Modeling the dataset
* Comapring the results

Each part is a separate menu item in the navbar.

--- .class #id 

## Exploring the dataset


&nbsp;
&nbsp;

Graphs available:

* Scatter plot
* Box plot
* Histogram

Controls available:

* Drop lists to select variables to plot
* Sliders to select point size and binwidth
* Checkboxes to add jittered point on boxplot, facet the scatter plot and color the points



--- .class #id 
## Models

To model the data set three algorithms are available:

* Regression three (rpart package)
* Random forest (random forest package)
* Gradient boosting machine (gbm package)

Controls:

* Checkboxes to select the variables to model with
* Drop list to select the variables to plot

Analysis:

* Variables used / Accuracy / Confusion matrix / Measures of statistical performance

--- .class #id 
## Compare

A tabular and graphical side by side comparison of the generated models.

Controls:
* Drop list to select the variables to plot

The app is available on shinyapps.io at the following link:
<a href="https://altervalter.shinyapps.io/iris/">Iris explorer in Shinyapps</a>


Thank you!


