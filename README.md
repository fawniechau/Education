# Education-Inequality 
A project exploring ACT performances and socioeconomic factor influences. 

## Description 
This study aims to determine if socioeconomic factors can predict school performance on the SAT or ACT. By using the average scores of schools and various socioeconomic data, including median income, linear regression models were constructed after cleaning the data. The optimal set of socioeconomic predictors for ACT scores was determined, revealing that the average ACT/SAT scores decrease as the number of students on free/reduced lunch and the rate of unemployment increases, and the percentage of adults with a college degree decreases. The study also explored the effect of ACT score requirements across different states, but found it to have minimal impact on the prediction model.

## Requirements
Google Colabratory 

## Sources for the Data
Primary dataset - School information data (https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0): Provides basic information about schools from the National Center for Education.  

Secondary dataset - Edgap data (https://www.edgap.org/#5/37.892/-96.987): Provides information about average ACT and SAT scores for each department off education or other public data release. 

### Additional Step Data Sources
Education Commission of the States (https://reports.ecs.org/comparisons/high-school-graduation-requirements-02): Provides reports that compare educational policies across 50 states. We found 2 different reports about non-course requirements for high school graduation from 2019 and the school year 2017-2018. Even though we are working with 2016-2017 data, the 2017-2018 is a good start to learn about the states that have SAT/ACT requirements as graduation:


EdWeek.org (https://www.edweek.org/teaching-learning/which-states-require-students-to-take-the-sat-or-act): provides a table with the 2016-2017 data of the states that require SAT/ACT  and other exams. 

## Data Preparation 
The steps taken to prepare the data for analysis are: 
- Conversion of data types 
- Create subset selections to our data that can help answer our questions
- Appropriately renaming columns 
- Merging edgap and school info data together into one data frame 
- Converting values out of range to NaN or removing it from the dataset
- Doing train and test splits 
- Imputating the NaN values 
- Exporting the clean data .csv file 

## Analysis 
The steps taken to analyze clean data: 
- Created relevant questions related to the data 
- Created different regression models inputting different combinations of predictors 
- Found the best subset selection with relevant predictors 
- Clean data was merged to dummy variable .csv to label states that do or do not require ACT scores 
- Different visualizations and plots were made to support questions 

## Author 
Tina Chau 

## License 
The contents of this repository are available for use, but proper credit must be given to Tina Chau. 
