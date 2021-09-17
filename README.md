# Internship-Energy-Efficiency

## Table of Content
- Introduction
- Approach
- User Interface
- Deployment Link
- File Structure
- Installation
- Technology Used
- Document

## Introduction
Buildings energy consumption is put away around 40% of total energy use. Predicting heating and cooling loads of a building in the initial phase of the design to find out optimal solutions amongst different designs is very important, as well as in the operating phase after the building has been finished for efficient energy. In this Notebook, diferent models were applied for predicting heating and cooling loads of a building based on a dataset for building energy performance.

**Input variables are:**
1. relative compactness
2. surface area
3. wall area
4. roof area
5. overall height
6. orientation
7. glazing area
8. glazing area distribution

**Output variables:**
1. heating loads
2. cooling loads

## Approach
~~~
1. Data Exploration     : I started exploring dataset using pandas,numpy,matplotlib and seaborn. 

2. Data visualization   : Ploted graphs to get insights about dependend and independed variables. 

3. Feature Engineering  :  All The Value Are Arrange In One Range.

4. Model Selection I    :  Tested all base models to check the base accuracy.
                       
5. Model Selection II   :  Performed Hyperparameter tuning using gridsearchCV.

6. Pickle File          :  Selected model as per best accuracy and created pickle file using joblib .

7. Webpage & deployment :  1. Created a webform that takes all the necessary inputs from user and shows output.
                           2. After that I have deployed project on AWS Elastic Net
~~~
## User Interface
The Energy Efficiency Final Model Run in Local Enviornment
![Screenshot (84)](https://user-images.githubusercontent.com/62636740/132971890-bb9064cd-dded-4a95-ab77-8027438404a2.png)

## Deployment Link
AWS Link : http://energyefficiency-env.eba-wrypfzra.us-east-2.elasticbeanstalk.com/
AWS Link For Data Report : http://energyefficiency-env.eba-wrypfzra.us-east-2.elasticbeanstalk.com/report

## File Structure
~~~
Project
|
|
Database Coonection--|
|                    |--Database.py
|                            
|                            
Dataset--------------|
|                    |---Analysis_Purpose.csv
|                    |---ENB2012_data.csv
|                    |---ENB2012_data.xlsx
|                    |---Final_data.csv
|                    |---Model_Building.csv
|                    |---Scaling.csv
|
|logFiles-----------|--App.log
|                   |--database.log
|                   |--Export & Import.log
|
Static--------------|
|                   |--css--|
|                   |       |---style.css
|                   |
|                   |--script--|
|                   |          |--script.js
|                   
templates-----------|  
|                   |---index.html
|                   |---Reoprt.html
|
|venv
|
|app.py
|
|Procfile
|
|requirements.txt
|
|runtime.txt
|
|secure-coonect-energyefficiency.zip
~~~

## Installtion
The Code is written in Python 3.7.11. If you don't have Python installed you can find it [your link here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) the repository.

~~~
Create a Virtual Env with conda create "Your Env name"
~~~
~~~
pip install -r requirements.txt
~~~
~~~
Run aap.py file
~~~

## Technology Used
~~~
1. Python
2. Sklearn
3. Pandas
4. Numpy
5. Flask
6. HTML
7. CSS
8. JS
9. Cassendra
10. AWS
~~~

## Document
Below providing the link of all the document that are required for creating the project.

Link: [Document Link](https://drive.google.com/drive/folders/1OvDlqafwiB26UZBLKYiIH5g2qRy4kE2g?usp=sharing)








