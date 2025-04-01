# Netlfix-Dashboard
The project is to design an overview dashboard for the content releases in the decade from 2010 to 2020 using Power BI. It’s about visualizing and examining the distribution between movies and TV shows for release patterns, genres, ratings, geographical distributions, etc. It’s basically a look back at how Netflix has evolved over the decade and the content strategy of the company. The visualization provides strategic insights into Netflix's content expansion strategy during its critical transformation into a global streaming powerhouse.

## Dataset 
Used data from Kaggle. It has about 8,500+ entries on the platform with fields such as release year, added year, ratings, director, cast, and countries.

## Tools and Conepts 
- Tools – Python (Numpy, Pandas), Power BI (plots, slicers), DAX, Power Query Editor
- Concepts – Data Cleaning, Visualizations and Storytelling, Comparative Analysis, Trend Analysis

## Methodology
1)	The entire dataset had content as old as from the 1980s, which was added to the platform starting in 2008. As this is a focused study of a decade, the data was filtered to that period, and extensive data cleaning was performed in Python to ensure reliability.
2)	Necessary measures, tables, and columns were created using Power Query Editor and DAX queries to get the requirements for the plots.
3)	Plots were created, and slicers were implemented to ensure wide usage and dynamic exploration of Netflix’s content trends, distribution, and genre patterns across dimensions/categories.
4)	The dashboard was formatted to the level of presentation and easy interpretation.

## Results 
- KPI Cards – Showing the total number of entries added to the platform, number of movies, TV shows, average runtime, and genres.
- Area Chart – Distribution of the releases by different days to identify the day on which most content was released.
- Radar Chart – Provides a direct insight into which month had the most number of releases.
- Stacked Bar Chart – Distribution of Movies & TV Shows for the Top 20 Countries.
- Funnel Chart – Shows the top 10 most popular genres on the platform.
- Clustered Column Chart – A pattern to show the count of movies and shows across ratings on the platform, which reveals the target audience focus.
- World Map – Visualizing the additions by country for the selected year and month dynamically.

## Findings
1.	Movies make up 70.3% (5,135 titles) of the total content, compared to 29.7% (2,167 titles) for TV shows.
2.	The content spans 42 different genres, with an average runtime of 69.58 minutes.
3.	Friday has the highest number of releases (1,288 titles), followed by Tuesday (802) and Sunday (759), indicating a strategic release timing aimed at maximizing viewer engagement.
4.	The United States leads in content volume, followed by India and the UK, accounting for about 36% of the entire world’s content. Country-specific strategies vary significantly.
5.	International Movies (2,343 titles), Dramas (2,013 titles), and Comedies (1,375 titles) are the top three genres, highlighting Netflix's global content acquisition strategy.

## Learnings 
1)	Knowing when to calculate and use a specific measure or column in Power BI is crucial to ensure accurate data representation.
2)	Creating relationships in the model view of the software allows for accurate plotting of fields across tables.
3)	It is important to note that tables created in the report view or normal view of the platform do not appear in the Power Query Editor for analysis or evaluation. These tables are only created to facilitate the visualization process and do not reflect in the data model.


