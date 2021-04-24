# Matplotlib-Challenge
The PyCitySchools directory contains these files:

	* main.ipynb	
	* Resources directory which contains two csv files
	* Conclusion.txt

The main jupyter notebook file contains analysis on a pharmeceutical's mouse study data. This file reads in two cvs files from the Resources folder. The analysis steps are shown below.

	Check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID
 		 		
	Generate a summary statistics table on tumor volume for each drug regimen, including:
		* Mean
		* Median
		* Variance
		* Standard Deviation
		* Standard Error
		
	Create charts that analyze the results of each drug regimen, including:
		* Bar Chart- plots number of mice per each drug
		* Pie Chart- plots the percentage of male and female mice in study
		* Box Plot- plots tumor volume for 4 drug regimens (Capomulin, Ramicane, Infubinol, and Ceftamin). Additionally, we found all outliers for each drug.
		* Line Plot- plots tumor volume at each timepoint for Capomulin
		* Scatter Plot- plots mouse weight against average tumor volume for Capomulin. Additionally, perform regression on mouse weight vs. average tumor volume. These are not correlated variables.