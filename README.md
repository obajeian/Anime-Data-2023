# Anime-Data-2023
The project uses the anime-dataset-2023 obtained from MyAnimeList website to derive insights from it through data analysis.

2023 Anime data analysis

This project aims to gain insights on the Anime industry as determined by the consumers of this form of entertainment in 2023.
The following are the datasets that are involved as obtained from Kaggle;

A)	anime-dataset-2023 
  •	anime_id 
  •	name 
  •	english name
  •	score 
  •	genres 
  •	type
  •	episodes 
  •	aired 
  •	premiered 
  •	status
  •	producers 
  •	licensors 
  •	studios
  •	duration 
  •	rating
  •	rank 
  •	popularity 
  •	favourites
  •	scored by 
  •	members
  
The problem statement

The project aims to use the dataset to investigate the user anime preferences in regard to anime type and genre as well as investigate user engagement based on popularity metrics. The information from this project can be used to strategize for optimization for a recommendation system. Studios can also use this information moving forward to the next year.
What we are looking for: 
•	Understand user preferences
•	Identify popular genres and studios
•	Comparative analysis
The processes

Methodology

Ask
Prepare
Process
Analyse
Share
Act
EDA
I explored the data to look for any incompleteness and inconsistencies in the dataset. I checked for missing values, duplicates and statistics on numerical columns. I did this before cleaning the dataset further to have knowledge over what I am working with.
The dataset was complete but there were some inconsistencies that would have to be wrangled in the cleaning phase. For example, the missing values were labelled as UNKNOWN rather than NA and some of the data points were poorly configured in regard to data types; e.g. score was an object instead of a float.

Data Cleaning

Using the information from EDA I cleaned the dataset.
I first replaced the UNKNOWN values with NaN as missing values for a consistent approach.
I then converted the ill configured data types to their correct data types such as floats and integers.
I then dropped irrelevant columns that would not aid in the business problem.
I then handled the missing values through imputation. I used mean for numerical values and mode for categorical values.

Data Analysis

I now use the clean dataset to run analysis to investigate the following:
Genre Analysis and Popular Trends:
Explore the most popular anime genres and trends over time. Identify which genres have the highest average scores, rankings, and popularity among viewers.
Content Analysis and Success Factors:
Analyze the attributes of successful anime content. Determine the relationship between factors such as episode count, duration, rating, and viewer engagement metrics like favorites and scores.
Studios Impact:
Investigate the influence of anime studios on ratings, popularity, and viewer satisfaction. 
Identify top-performing studios/producers and their contributions to successful anime titles.
Airing Status and Impact on Popularity:
Study how the airing status (ongoing vs. completed) of anime series affects their popularity, viewer engagement, and ratings. Compare the performance of ongoing series with completed ones.
User Engagement Metrics:
Explore user engagement metrics such as "scored by" and "members" to understand the level of community involvement and interest in specific anime titles. Identify highly engaging titles and factors contributing to their engagement.
Comparative Analysis:
Conduct comparative analyses between different types of anime (e.g., TV series, movies, OVAs) in terms of ratings, popularity, and viewer engagement. Identify strengths and weaknesses of each type.
Visualization
While I was doing the analysis, I chose to visualise the output so that the output can be used to communicate insights.
The visualizations were achieved using matplotlib and seaborn libraries in python.
