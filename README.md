# pymaceuticals-challenge
## Pymaceuticals

The Pymaceuticals folder contains the file needed to analyze the mouse metadata and the study results, which are also within the Pymaceuticals folder. Within the Pymaceuticals folder is the data folder, which contains the mouse metadata in mouse_metadata.csv files, which has the data columns _Mouse ID_, _Drug Regimen_, _Sex_, _Age_months_, and _Weight (g)_. The data folder also contains the Study_results.csv, which has the data columns _Mouse ID_, _Timepoint_, _Tumor Volume (mm3)_, and _Metastatic Sites_.

The Pymaceuticals folder also contains the pymaceuticals_starter.ipynb file, which is a Jupyter Notebooks script that analyzes the data within mouse_metadata.csv and Study_results.csv.

The pymaceuticals_starter.ipynb file generates one summary and eight graphs. The summary statistics table contains mean, median, variance, standard deviation, and SEM of the tumor volume for each drug treatment.

The eight graphs generated are:
- two bar graphs showing the total number of timepoints for each drug regimen
- two pie graphs showing the distribution of the mice's sex
- one figure that has 4 boxplot for the distribution of tumors with 4 different treatment group = Capomulin, Ramicane, Infubinol, and Ceftamin
- one line graph showing the progress of a mouse's tumor volume over the timepoints while on Capomulin
- one scatter plot showing the points of all of the mice's weights and average tumor volume while on Capomulin
- one linear regression model between avergae tumor volume and the weight of the mouse

## Citations
The script in pymaceuticals_starter.ipynb contains code from the follwoing websites:
- https://www.geeksforgeeks.org/find-duplicate-rows-in-a-dataframe-based-on-all-or-selected-columns/ The code from the website is used to find duplicate rows in a dataframe and is used in codebox [4]
- https://pandas.pydata.org/docs/reference/api/pandas.Index.values.html The code from the website is used to call the values of the index and is used in codebox[10]
- https://matplotlib.org/stable/gallery/statistics/boxplot_demo.html The code from the website is used to put 4 boxplots into one figure and is used in codebox[15]

