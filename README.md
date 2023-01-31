# Pymaceuticals-Challenge5

Note: Please use Jupyter Notebook

This repository contains data analysis performed using Pandas and Matplotlib for Challenge 5 of Data Analytics Bootcamp at University of Toronto. The focus of this challenge was to prepare the data and create visualizations to perform analysis.

The analysis is based on the data provided in two CSV files for Pymaceuticals Inc. about 249 mice which were tested in this study to compare the performance of Capomulin (the drug of interest) againts other treatment regimens.

First, the two datasets are merged to create a single dataset containing all data. The dataset is then cleaned by identifying the duplicated data for Mouse ID and Timepoint and removing this duplicated data from the merged dataset.

A summary statistics table is then created by calculating the mean, median, variance, standard deviation, and standard error for tumor volume under each drug regimen.

For analysis, two identical bar charts are created using Pandas and Matplotlib to show the total number of timepoints for all mice tested under each drug regimen.

Similarly, two identical pie charts are created using Pandas and Matplotlib showing the male vs. female distrubution of mice used in the study.

Four treatments/ drug regimens are compared to identify any outliers for the data on tumor volume at the last timepoint. Quartiles, upper and lower boundaries and boxplot is created for the analysis which shows only one outlier for the drug Infubinol.

A line chart is then created to track the volume of one mice treated with Capomulin over the treatment period. 

A scatter chart is prepared to plot average tumor volume vs. average mouse weight. A correlation analysis is performed on the same variables which shows a strong positive correlation. A regression line is then charted on the scatter plto showing a linear relationship between average tumor volume and mouse weight.

An overall summary and key observations from the analysis are included in the beginning of the notebook.