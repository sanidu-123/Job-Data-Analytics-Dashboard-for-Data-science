# Job Data Analysis Dashboard for Data science domain
Use the Power BI data visualization tool to identify hidden insides and patterns in the data set by using ds salaries.csv

## Power Bi link:https://app.powerbi.com/groups/me/reports/06989445-c477-4f38-9b8d-e8f5340e995f/ReportSection7f9992c3b4ecd5b4e1c7?experience=power-bi
## Overview 
This assignment aimed to select a dataset and analyze and visualize the data for deriving and interpreting insights. We have selected the data science domain and their job salaries for our visualization assignment. The underlying reason for selecting this domain was that the job market is dynamic with changes in the industry and the evolving market. Job salaries are important for job seekers, employers, and policymakers who want to understand what's happening in the job market.

## Objective
Our data visualization project is all about crafting a helpful dashboard using Power BI and Python, but not building complex models just to get the dataset ready for visualization. We're exploring the above job dataset from Kaggle, aiming to make sense of the job market data and present insights in a visually straightforward manner. 

### dataset link:https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries 

## Preprocessing
### Data Blending & Integration and data cleaning
The dataset that is chosen for this project is a secondary one. Therefore, the data blending and integration are already done.  Plus, all the data was in a singular tabular format. Dataset is already cleaned and no many work to do.
### Data Transformation & Reduction 
Replacing values  in the Experience column 
* EN -Entry-level 
* MI -Mid-level 
* SE -Senior-level 
* EX -Executive-level
  
Replacing values in the employment type column 
* PT -Part-time 
* FT -Full-time 
* CT- Contract 
* FL –Freelance
  
Replacing values in the Company size column 
* S- small 
* M- medium 
* L- Large 

## Annalysis
### Descriptive Analysis 
we decided to use Python to interpretation. Use info () and describe () functions for both numerical and categorical data.

### Visualization
* The slicers on top with years allow filtering all data visuals by the year. The card visuals on top display the most important details about data.

* Pie chart and donut chart visuals were used to show the total percentage distribution of company sizes and job distribution by emploment type.

* Line plot visual maps the overall trend of the number of jobs and average salary variation by the year. Table visual shows the top countires with their count of jobs. 

* The correlation heatmap depicts the relationship between the employement type and numerical columns average salary and remote ratio.

## Snapshot of dashboard
![Screenshot 2024-06-22 203142](https://github.com/sanidu-123/Job-Data-Analytics-Dashboard-for-Data-science/assets/172403569/a03fb0e8-1551-49ed-b800-dfb433a4bfee)
