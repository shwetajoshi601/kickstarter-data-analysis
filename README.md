# kickstarter-data-analysis
A project for analyzing the Kickstarter data available on Kaggle.
In this project, we have created three distinct visualisations for analysing the Kickstarter data in vega lite. (Links available below).

## Introduction
* The [Kickstarter Data](https://www.kaggle.com/kemical/kickstarter-projects#ks-projects-201801.csv) available on Kaggle consists of data for crowdfunding projects that are posted on the Kickstarter platform. 
* The dataset has been first analysed in Python and relevant pre-processing has been done to derive certain features useful for analysis. The [Jupyter notebook-Kickstarter analysis.ipynb](https://github.com/shwetajoshi601/kickstarter-data-analysis/blob/master/Kickstarter%20analysis.ipynb) consists of the pre-processing steps and generates CSV files for each analysis. These CSV files have been stored in another repository.
* Vega-Lite has been used to create visualisations and the JSON spec has been embedded into HTML files.
* The HTML files for the 3 analyses consist of the details of the dataset description, the visualisations and insights obtained from the analysis.

## Steps to view the Analysis

Assuming you have GIT Bash already installed, or any other tool to interact with GitHub,

1. Clone the project folder

   ```
      git clone https://github.com/shwetajoshi601/kickstarter-data-analysis.git
   ```   
2. Change directory
   ``` 
      cd kickstarter-data-analysis
   ```
3. Run the HTML

      ```
      Double click on any HTML file. It will open in the browser.
      ```
      
   Example:
   
      ![sample](https://user-images.githubusercontent.com/16982762/78817480-1a03cc80-79cb-11ea-9859-acebba0ef25d.PNG)
    

## Analysing how Project goal amount affects the success

* In this visualisation, we try to find a relation between the success/failure of a project to the goal amount the projects have.
* We find the total number of projects successful and failed in each category of Projects and compare it with the median Goal and Pledged amount for that category.

Links: [HTML-Vis1.html](https://github.com/shwetajoshi601/kickstarter-data-analysis/blob/master/Vis1.html) | [Processed dataset](https://github.com/shwetajoshi601/infovis-data/blob/master/vis1-data-new.csv)

## No. of Failed and Successful Projects by Hour of Day

* The success of a project depends on multiple factors - the Goal amount of the project, project category, the title of the project or even the time at which the project was posted.
* We try to analyse if the hour of day at which the project was launched has any effect on the success.
* For this, hour has been extracted from from the launch date. For each hour, the graph displays the total number of failed and successful projects.

Links: [HTML-Vis2.html](https://github.com/shwetajoshi601/kickstarter-data-analysis/blob/master/Vis2.html) | [Processed dataset](https://github.com/shwetajoshi601/infovis-data/blob/master/vis2-data-new.csv)

## Relationship between Success Rate and No. of Backers

* In this analysis, we observe the trend in the success rate of projects over the years.
* We also try to find the relationship of the success rate with the number of backers that invest in the projects.

Links: [HTML-Vis3.html](https://github.com/shwetajoshi601/kickstarter-data-analysis/blob/master/Vis3.html) | [Processed dataset](https://github.com/shwetajoshi601/infovis-data/blob/master/vis3-data-new.csv)
