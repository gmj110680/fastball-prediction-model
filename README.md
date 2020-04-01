## Springboard Capstone Project 1 - Major League Baseball Fastball Prediction Model

For this project, my goal was to build a classifier that can predict whether a major league baseball pitcher will throw a fastball with his next pitch based upon various circumstances known to the batter before the pitch is thrown.  I used the publicly-available pitch data from the 2015-2018 Major League Baseball seasons, which can be found on Kaggle [here](https://www.kaggle.com/pschale/mlb-pitch-data-20152018).

Ultimately, I was able to build two classifiers that successfully predict whether a pitcher will throw a fastball at a higher rate than the default fastball rate of 52.41%.  I also share some ideas for future work on the project that I think could further improve my models.



### Project Summary

I have aggregated every step of project, incuding my final results/conclusions as well as thoughts on further work that could improve the models, in the [Fastball Prediction Model Final Notebook](https://github.com/gmj110680/fastball-prediction-model/blob/master/Fastball_Prediction_Model_Final_Notebook.ipynb).  This notebook is an aggregation of all other notebooks saved in the repository and provides the reader with all of the code used for this project along with my step-by-step narrative analysis at every stage of the project, including data wrangling/cleaning, exploratory data anaylsis, data visualization/storytelling based on initial findings, initial model building, feature and model hyperparameter tuning, and my final results and conclusions.

If you would prefer to read a summary of my project work and conclusions without the code, please review the narrative-only [Capstone Project 1 Final Report](https://github.com/gmj110680/fastball-prediction-model/blob/master/Capstone_Project_1_Final_Report.pdf).

### Iterative Project Work

The other files in this repository provide my findings and analysis at various stages of this project.  Please note - because the project was ever-evolving, some of the approaches and strategies discussed in these files may have later changed as my work progressed.  A brief description of each file is as follows:

-  [data_wrangling](https://github.com/gmj110680/fastball-prediction-model/blob/master/data_wrangling.pdf): This file provides a narrative summary of the initial data wrangling steps I took, including merging two of the `.csv` files in the dataset, addressing some missing data, and creating dummy variables for some categorial features.

-  [Data Story](https://github.com/gmj110680/fastball-prediction-model/blob/master/Data_Story_Final.ipynb):  This notebook summarizes some of the data visualization techniques that I used when conducting exploratory data analysis on the dataset.  NOTE - the narrative analysis of the various visualizations in this notebook is based on a previous iteration of the project where I was using only one type of fastball (four-seam) as my target label.  I later updated that label to include two other types of fastballs (two-seam and cutter), which changed the resulting graphs.  So, the numbers used in the narrative analysis will not match up to the updated information in the visualizations.

-  [Statistical Data Analysis](https://github.com/gmj110680/fastball-prediction-model/blob/master/Statistical_Data_Analysis.ipynb):  This notebook summarizes some inferential statistical techniques that I applied to some of the continuous variables in the dataset.  NOTE - these calculations were based on a previous iteration of the project where I was only using one type of fastball (four-seam) as my target label.  I later expanded my target variable to include two-seam and cut fastballs.

-  [Milestone Report](https://github.com/gmj110680/fastball-prediction-model/blob/master/Capstone_Project_1_Milestone_Report.pdf):  This file is a narrative report that summarized my findings once I had completed all of my expoloratory data analysis on my dataset.  NOTE - this report was based on a previous iteration of the project where I was only using one type of fastball (four-seam) as my target label.  I later expanded my target variable to include two-seam and cut fastballs.

-  [In-Depth Analysis](https://github.com/gmj110680/fastball-prediction-model/blob/master/In-Depth_Analysis.ipynb):  This notebook contains my initial experimentation with various machine learning models.  I eventually settled on two classifiers that I then tuned to improve performance.  That work can be found as the last section of my final comprehensive project summary notebook.


If you found this project interesting and/or have any feedback, I'd love to hear from you!  You can reach me at <jacobs.greg@gmail.com>.
