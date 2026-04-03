                Absenteeism at Work Dataset Description

1- Dataset source:
The dataset is provided by the Kaggle repository, from the UCI Machine Learning Repository

2- Dataset Size:
Original shape: 740 rows × 21 columns 
After cleaning: 628 rows × 21 columns 

3- Columns:
The dataset contains 21 features, including:
- Numeric:
Transportation expense, Distance from Residence to Work, Service time, Age, Workload 
Average/day, Hit target, Weight, Height, Body mass index, Absenteeism time in hours.
- Categorical
Reason for absence, Month of absence, Day of the week, Seasons, Disciplinary failure, 
Education, Social drinker, social smoker, Pet.

4- Data Cleaning:
4.1 - Duplicates: 34 duplicate rows are removed.
4.2 - Outliers: IQRused to remove outliers from these columns: distance_from_residence_to_work, age, work_load_average/day          and absenteeism_time_in_hours.
4.3 - Column Formatting: convert all column names to lowercase and replace spaces with underscores. 
4.4 - Missing Values: No missing values.

5- Purpose of Using This Dataset:
- It contains duplicates and outliers: suitable for practicing data cleaning and 
  preprocessing.
- explore patterns and relationships in the data: it includes important features 
  related to employee absenteeism.
