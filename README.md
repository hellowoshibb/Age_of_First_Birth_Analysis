<h1 align="center"> How Socioeconomic Factors Affect Average Age of First Birth in Canada</h1>
<h2 align="center"> Authors </h2>
<center>

Sevnur Kulak
Dongqi Bi
Ivan Li
</center>


<h2 align="center"> Abstract </h2>
<p align="justify">

The average age for having a first child has been shifting from early 20s to older ages recently. This paper investigates potential factors to research on likelihood of having children at an early age depending on gender, education level, occupation, income, and mental health. Whereas women are more likely to have their first children at earlier stages of their lives compared to men, education, occupation, and income are other factors which have an impact for individuals to have their first child in later stages of their lives. It is crucial to assess the underlying factors of this changing trend for further application in the labor market and potential upcoming health outcomes for women. 


</p>

To run the code which performs our analysis, make sure you execute the following two steps first:
### 1. Installing the packages

Install the following packages in your R environment:
- hash
- dplyr
- forcats
- knitr
- janitor
- tidyverse
- tidyr
- wrapr
- haven
- ggplot2
- gridExtra


### 2. Downloading the data

To access to the General Social Survey C31 MAIN SURVEY- FAMILY, visit:
https://www23.statcan.gc.ca/imdb/p3Instr.pl?Function=assembleInstr&lang=en&Item_Id=335815#qb345582

The raw data set is gathered by the General Social Survey C31 MAIN SURVEY- FAMILY, it is only available for students in University of Toronto and is not allowed to share with public. The data set we used in our paper is the clean-up data set with selected variables. If you need to download the raw data:

1. Visit: http://dc.chass.utoronto.ca/myaccess.html
2. Go to "SDA @ CHASS" and sign in with your utoronto id.
3. Search for and click "Canadian general social surveys (GSS)"
4. Download the data for "General social survey on Family (cycle 31), 2017"
5. Choose CSV file, data definitions for STATA and select all the variables.



### Running the Code

The data cleaning file for tidying up the raw data into the dataset we used is impremented in the script/data_cleaning.R

The algorithms and data analysis study is impemented in outputs/paper/Age_of_First_Birth_Analysis.Rmd. You can run this file using RStudio.

### More Details 
View our paper at outputs/paper/Age_of_First_Birth_Analysis.pdf for more information. 
