# CaseStudy-SMUDDS
Final Casestudy

https://www.youtube.com/watch?v=5bmrSDLw1Nk 

---

title: "ReadMe"

author: "Saloni Bhatia"

date: "August 7, 2019"

output: html_document

---



#Scenario

DDSAnalytics is an analytics company that specializes in talent management solutions for Fortune 100 companies. Talent management is defined as the iterative process of developing and retaining employees. It may include workforce planning, employee training programs, identifying high-potential employees and reducing/preventing voluntary employee turnover (attrition). To gain a competitive edge over its competition, DDSAnalytics is planning to leverage data science for talent management. The executive leadership has identified predicting employee turnover as its first application of data science for talent management. Before the business green lights the project, they have tasked your data science team to conduct an analysis of existing employee data.



We have been given a dataset (CaseStudy2-data.csv) to do a data analysis to identify factors that lead to attrition. We need to identify the top three factors that contribute to turnover. The business is also interested in learning about any job role specific trends that may exist in the data set (e.g., "Data Scientists have the highest job satisfaction").



#Objective

To conduct exploratory data analysis (EDA) to determine factors that lead to attrition.

Identify (at least) the top three factors that contribute to turnover.

Provide any other interesting jobrole specific trends and observations from your analysis.

Build a model to predict attrition.



#Purpose

To support the analysis of DDSAnalytics Human Resources data in order to:

1)Identify the leading causes of employee attrition within the company.

2)Predict Monthly income for  trends specific to job roles within the company.



#Files Contained in This Repository:

The following files can be found in support of this analysis

1) CaseStudy2-data.xlsx -- Contains original data set as provided by the client.

2) CaseStudy2Data.csv -- A csv formatted version of the data.

3) Codebook.rmd -- An Rmarkdown file containing descriptions of the data and any derived variables / models used in analysis

4) Codebook.html -- An HTML representation of the Codebook

5) DDS Analytics Final Presentation.pptx -- The final presentation as provided to the client.

6) DDSAnalytics_casestudy_SaloniBhatia_model.Rmd -- The final analysis as completed by the team.

7) DDSAnalytics_casestudy_SaloniBhatia_model.html -- HTML version of the final analysis.

8) Case2PredictionsBhatia Attrition.csv - Predicted values for Attrition

9) Case2PredictionsBhatia Salary.csv - Predicted Monthly Income values

10) CaseStudy2CompSet No Attrition.csv - File provided for Classification model evaluation

11) CaseStudy2CompSet No Salary.csv - File provided for Prediction model evaluation 





#Deliverables:

A model that will attain at least 60% overall accuracy for the training and the validation set

One prediction file, "Case2PredictionsXXXX.csv", ordered by ID where 'XXXX' with all team members'last name

RMarkdown file with R code that does the following:

a. fits the model on only the training set ... you must call this dataframe dfTrain and it must have the exact format of the csv file given to you.

b. uses that model to predict the labels of the test set. you must call this dataframe dfVal and it must have the exact format of the csv file given to you.

c. make a dataframe with only the ids in one column and the labels in the second column .. you must call this dataframe dfPreds.

d. prints those ids and predictions to a csv file, to my working directory using write.csv

Individual presentation on YouTube with link to be included in RMarkdown file.

Submit Link to GitHub repo to 2DS.
