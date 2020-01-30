# Airflow-Demo-Automation


Airflow is an open-source platform to programmatically author, schedule and monitor workflows. Airflow was started in 2014 at Airbnb 
The project joined the Apache Software Foundation’s Incubator program in 2016. It is one fo the most intuitive way to automate and track repeatable tasks in the Analytics ecosystem.

## Use Case

Here you have a data provider, who has flat files which when uploaded into database will be used for analysis. After the files has been uploaded, Data Engineer, will process those files and make sure it’s available with data scientist to either run some models or perform basic aggregations. The summarize data will then be used by a business analyst to create a report or dashboard in excel or tableau for manager.
As of today, there are number of pain points associated with each stakeholder in this scenario.
Waiting time due to dependency on data provider and manual effort to start the process of report generation.
There is cumbersome monitoring for Data scientist or Business Analyst, in case there is an error in code and lot of time is spent in debugging and identifying errors in code. 
There is lack of transparency throughout process for manager and lot of back and forth to communicate the status of report.

![1574100207862](https://github.com/guptapiyush340/Airflow-Demo-Automation/blob/master/2.png)

## Airflow Implementation

![1574100207862](https://github.com/guptapiyush340/Airflow-Demo-Automation/blob/master/1.png)

## DAGs Overview

We have 3 datasets namely, Train (the training set), Test (the testing set), and Resources (items requested along with each application or proposal).

![1574100207862](https://github.com/guptapiyush340/Airflow-Demo-Automation/blob/master/4.png)

## How to get Started

Using all the features as it is rarely useful in data mining. To make this features more informative, we performed a range of feature engineering steps and performed text analysis on the essays and title of essays.

![1574100207862](https://github.com/guptapiyush340/Airflow-Demo-Automation/blob/master/3.png)
