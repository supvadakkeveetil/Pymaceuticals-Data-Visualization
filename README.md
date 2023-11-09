# Pymaceuticals-Data-Visualization
Pymaceuticals Data Visualization using Matplotlib
## Goal
Purpose of this study is to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens and Creating a Top level summary of the Study results for the executives.
## Results
* Bar Chart showing the total number of rows for each regimen

![Bar_Chart](https://github.com/supvadakkeveetil/Matplotlib-Challenge/assets/144635564/42ec2426-b9fc-496e-b927-040c6c2b74c4)

* Pie Chart showing the distribution of Female Vs Male Mice

![Pie_Chart](https://github.com/supvadakkeveetil/Matplotlib-Challenge/assets/144635564/d3666ee6-2716-4ca7-b839-3f73cd70c344)

* Calculating IQR and potential outliers

  Capomulin:
  The InterQuartile of tumor volume is :7.781863460000004
  The Median tumor volume is :38.1251644
  Values below 20.70456164999999 and above 51.83201549 could be outliers

  Ramicane:
  The InterQuartile of tumor volume is :9.098536719999998
  The Median tumor volume is :36.56165229
  Values below 17.912664470000003 and above 54.30681135 could be outliers

  Infubinol:
  The InterQuartile of tumor volume is :11.477135160000003
  The Median tumor volume is :60.16518046
  Values below 36.83290494999999 and above 82.74144559000001 could be outliers
  The outliers are [36.3213458].

  Ceftamin:
  The InterQuartile of tumor volume is :15.577752179999997
  The Median tumor volume is :59.85195552
  Values below 25.355449580000002 and above 87.66645829999999 could be outliers

* Box plot showing the distribution of tumor volume across treatment groups

![BOX _PLOT](https://github.com/supvadakkeveetil/Matplotlib-Challenge/assets/144635564/18712cc4-8544-4e02-972b-60fc8095b3f5)

* Line Chart (Tumor Volume Vs Timepoint for Single mouse treated with Capomulin

![line_chart](https://github.com/supvadakkeveetil/Matplotlib-Challenge/assets/144635564/88f3fe9a-62f8-4c0e-a72b-0c135d488111)

* Scatter Plot (Mouse Weight Vs Average observed Tumor Volume for Capomulin Regimen)

![scatter_plot](https://github.com/supvadakkeveetil/Matplotlib-Challenge/assets/144635564/9fd13b11-1029-4c9b-bb4c-43f1859a70a3)

* Correlation Co-efficient and Linear Regression Model for Mouse Weight Vs Average observed Tumor volume for Capomulin Regimen

  The Correlation between the mouse weight and the average tumor volume is 0.84
  
  ![regression](https://github.com/supvadakkeveetil/Matplotlib-Challenge/assets/144635564/037f8769-55ff-4788-8ba8-a1c85f98a0bb)

  
## Analysis
1. Capomulin and Ramicane drugs have been used to treat the highest number of mice.
2. A good ratio of Male and Female mice have been included
3. The Correlation between mouse weight and average tumor volume is 0.84 using Capomulin drug treatment, which indicates a Strong Positive correlation between the variables. This means when mouse weight increases the average tumor volume tends to increase as well and viceversa. But this does not mean causation.It is not meant to say that the mouse weight causes changes in tumor volume or viceversa. It only indicates there is a consistent relationship between Weight and average tumor volume.

## References
Data Source: As provided by Edx
