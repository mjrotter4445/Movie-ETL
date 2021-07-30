# Movie-ETL
# ETL - Extract, Transform, and Load 
*A ETL Movies Analysis*
## Project Overview 
### Purpose & Background
The Amazing Prime, a video streaming company, decided to sponsor a hackathon, 
where participants try to predict which low budget movies being released 
will become popular.  Participants of a hackathon need clean data. Below, 
we will provide an organized and clean dataset using ETL or **Extract, 
Transform, and Load** process and includes the following:
    -  Extracting data from two different sources.  
       - web scrape of **wikipedia** website for all movies released since 1990
       - data from **Kaggle** website for rating data.
    -  Transforming data using **Jypter Notebook, Python, Pandas, and Python Regex.**
    -  Loading data using **PostgreSQL** and **pgAdmin** to host final cleaned data set. 

### Overview of the Code and process used
1. ETL_function_test_ipnyb
    -  Data extracted from website in JSON and class csv files/format.  
    -  Data is transformed into Pandas data frames.   
    -  JSON file loaded first and transformed into data frame.  
2. ETL_clean_wiki_movies.ipnyb
    -  Function clean_movie combines scattered data of alternative languages
       into one column alt_titles.   
       - a subfunction change_column_name organizes column names into a 
         a standard pattern. 
    -  We built and use function extract_transform_load to transform the wiki
       movies data.
3.  ETL_clean_kaggle_data.ipynb
    -  Function extract_transfom_load gets used to clean Kaggle data too. 
       - datatypes are standardized, missing values are filtered, 
         a dataframes merged.  
4.  ETL_create_database.ipynb
   -  At completion, we connect the database by **sqlalchemy library** and 
       **to_sql** method.  
   -  Complete ETL_process is executed with **extract_tranform_load** function. 

</p>  
<p align="center">
<img width="300" height="200" src="https://github.com/mjrotter4445/Movie-ETL/blob/main/Resources/use%20this%20one.png">
</p>   


    
### Resources
 Data Sources:
   -  Wikipedia and Kaggle 
 Environment & Software
   -  Python 3.7
   -  Jupyter Notebook
   -  PostgreSQL and PgAdmin
 Dependencies
   -  

### Results - see examples and make the pngs next
 