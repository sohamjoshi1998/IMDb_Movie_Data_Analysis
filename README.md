# IMDb_Movie_Data_Analysis
Exploratory Data Analysis of IMDb Movies dataset

### Table Of Contents
1. Overview
2. Libraries Used
3. Methodology
4. Inferences
5. References
6. Author


**1. Overview -** 
IMDb Movies ia a dataset consisting of the 100 top-rated movies from the past decade along with various pieces of information about the movie, its actors, and the voters who have rated these movies online. The task is to find some interesting insights into these movies and their voters, using Python and its libraries.

**2. Libraries Used -** 
*NumPy, Pandas, Seaborn, Matplotlib*

**3. Methodology -**
- Reading and inspecting the dataframe.
- Data Manipulation - The numbers in the budget and gross are too big, compromising its readability thus coverting their units from $ to million $, cCreating a new column named profit which contains the difference of the two columns: gross and budget.
- Data Visualization and Analysis - Derive useful insights using different plots which are mentioned below.

**4. Inferences -**
- It can be seen that 'Tangled' , one of the highest grossing movies of all time, it has negative profit as per the result. Cross checking the gross values of this movie  [link](https://www.imdb.com/title/tt0398286/), it can be seen that the gross in the dataset accounts only for the domestic gross and not the worldwide gross. This is true for may other movies also in the list.
- Leonardo DiCaprio, Tom Hardy, Joseph Gordon-Levitt is the popular trio based on the total number of facebook likes with a condition that none of the three actors' Facebook likes is less than half of the other two.
- Most of the movies appear to be sharply 2 hour-long.
- Deadpool is the R-rated movie most watched by kids (Under 18)


**Gender and Genre Demographic Analysis-**
- Age Group (18-29) seem to vote more than any other age group with Sci-Fi being the most popular genre even if it has the lowest no. of counts according to previous inference.
- Under 18 and above 45 people seem to have least number of votes in all the genres.
- Romance genre seems to be least popular amongst males of all ages compared to other genres.

- Under 18 age group seem to rate movies higher than other age groups in all genres.
- Females in all age groups seem to like animation and romance more than males.
- Males under 18 seem to have a liking for crime along with scifi.

**US vs Non-US Cross Analysis-**
- More number of US people seem to vote for US made movies.
- Non-US made movies seem to have less votes overall.

- Median Rating of US made movies seem to be higher in both the cases, but US people tend to give lower rating to non-US movies.
- US movies seem to have a few movies which have very high ratings unlike non-US movies.

Top 1000 Voters-
- Sci-fi seems to be the most popular amongst top 1000 voters. From the previous heatmap, we can conclude that top 1000 voters would majorly consist of age group 18-29 as Sci-fi was the most popular genre in that age group.


**5. References -** 
This case study was a part of Data Science Certification Program by UpGrad Campus.

**6. Author -**
**Soham Joshi** | [LinkedIn profile](https://www.linkedin.com/in/sohamjoshi1998/)
