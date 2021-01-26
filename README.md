# README #

This README would normally document whatever steps are necessary to get your application up and running.

## Important Sample Plotly Charts ##

This folder contains two file for different type of plotly plot as sample 

### Folder contains-- 
* plotly_charts.ipynb - check the workbook plotly_charts.ipynb ,for plots type.
* plotly_sample_module.py - contains all the functions of plots 

A function is created for each type of plot. 

- Input of function :: x , y, y1, y2 , title
- x = a list which is used as xaxis of the plot
- y = feature 1, a list
- y1 = feature 2, a list 
- y2 = feature 3, a list
- title = Plot Title, a string 

- in time of using every plot, need to change the title_text for xaxis and yaxis name in layout section.. ("xaxis" , "yaxis" )
- config = {'displayModeBar': False, "showTips": False, 'responsive': False} , 
  this config (in line 28 of plotly_sample_module.py) dictionary contain some configarations of plots layout. 
  this part needs to take with every plot function 
