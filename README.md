# Matplotlib - The Power of Plots

## Background

What good is data without a good plot to tell the story?

We are given access to the complete data from the most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

## Analyzation:

* Before beginning the analysis, we checked the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

* Using the cleaned data for the remaining steps.

* Generating a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generating a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows  the number of total mice for each treatment regimen throughout the course of the study.

* Generating a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Calculating the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculating the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generating a box and whisker plot of the final tumor volume for all four treatment regimens and highlighting any potential outliers in the plot by changing their color and style.

* All four box plots is created within the same figure.

* Selecting a mouse that was treated with Capomulin and generating a line plot of time point versus tumor volume for that mouse.

* Generating a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculating the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Ploting the linear regression model on top of the previous scatter plot.

* Looking across all previously generated figures and tables and writing three or more observations or inferences that can be made from the data.

## Conclusions:
* From the line graph between Tumor Volume and timepoint we can see that as days are passing, tumor size is decreasing for Capomulin drug. The same trend can be seen by the boxplots also.
* As seen in the boxplot, the drug "Infubinol" has an outlier in its dataset, Therefore the stats like mean of tumor volume is gets effected by it.
* For drug regime "Capomulin", As the tumor volume increases, weight of the mouse also increases with it. This could be confirmed by the correlation co-efficient of between the two which is 0.84.
* Number of Male and Female mice were approximately equal in the experiment.


