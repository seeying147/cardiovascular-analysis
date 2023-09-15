# <img src="https://github.com/seeying147/cardiovascular-analysis/assets/144315315/bba359d5-c3c5-4f21-bda8-9c3e457ad3b7" width="200" height="150"> Cardiovascular Disease Analysis
## Description
This project aims to look into the data of cardiovascular patients using R Programming. Through the use of patients' data, it can help us to determine significant factors contributing to cardiovascular disease as well as to have an understanding of how BMI might play a part in increasing the risk of contracting this disease. Every aspect of this project is a sample code which shows how to do the following:

* Summary statistics of each variable
* Investigate each variable to look for possible outliers and carry out transformation if required. 
* Statistical analysis of each variable using linear regression model, ANOVA (an analysis of variance), f-test and t-test

For full documentation, view [here](https://seeying147.github.io/cardiovascular-analysis/)
## Dataset
The dataset was obtained from the online data science platform Kaggle titled “[Cardiovascular Disease dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)”. The original dataset contains 70000 observations with 12 variables.

## Technologies Used
The project is created with RStudio v4.1.2 (Install [here](https://posit.co/products/open-source/rstudio/))

## Setup
To run this project:
* Download cardio_data.csv to view the original dataset
* Download index.Rmd and open the document in RStudio
* In RStudio, install 4 packages using the following command:
```{r}
install.packages(dplyr)
install.packages(ggplot2)
install.packages(gridExtra)
install.packages(PerformanceAnalytics)
```
* In index.Rmd, edit the file path in read.table("filepath", sep=";",header=T). 
* Click "Knit" to view the project. 

## License
This project is licensed under MIT License- see LICENSE file for details

