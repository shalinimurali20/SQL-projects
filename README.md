# SQL-projects

# Analyze International Debt Statistics
## Level: Beginner
### Task: Write SQL queries to answer interesting questions about international debt using data from The World Bank.
- What is the number of distinct countries present in the database? The output should be single row and column aliased as total_distinct_countries.
- What country has the highest amount of debt? Your output should contain two columns: country_name and total_debt and one row.
- What country has the lowest amount of principal repayments (indicated by the "DT.AMT.DLXF.CD" indicator code)?

# Investigating Netflix Movies
## Level: Beginner
### Task: Perform exploratory data analysis on the netflix_data.csv data to understand more about movies from the 1990s decade.
- What was the most frequent movie duration in the 1990s? 
- A movie is considered short if it is less than 90 minutes. Count the number of short action movies released in the 1990s and save this integer as short_movie_count

# Analyze Students' Mental Health
## Level: Beginner
### Task: Explore and analyze the students data to see how the length of stay (stay) impacts the average mental health diagnostic scores of the international students present in the study.
- Return a table with nine rows and five columns.
- The five columns should be aliased as: stay, count_int, average_phq, average_scs, and average_as, in that order.
- The average columns should contain the average of the todep (PHQ-9 test), tosc (SCS test), and toas (ASISS test) columns for each length of stay, rounded to two decimal places.
- The count_int column should be the number of international students for each length of stay.
- Sort the results by the length of stay in descending order.

# Golden Era of Video Games
## Level: Beginner-Intermediate
### Task: Write SQL queries to answer interesting questions about video games since 1977.
- Find the ten best-selling games. The output should contain all the columns in the game_sales table and be sorted by the games_sold column in descending order.
- Find the ten years with the highest average critic score, where at least four games were released (to ensure a good sample size). Return an output with the columns year, num_games released, and avg_critic_score. The avg_critic_score should be rounded to 2 decimal places. The table should be ordered by avg_critic_score in descending order. Save the output as critics_top_ten_years
- Find the years where critics and users broadly agreed that the games released were highly rated. Specifically, return the years where the average critic score was over 9 OR the average user score was over 9. The pre-computed average critic and user scores per year are stored in users_avg_year_rating and critics_avg_year_rating tables respectively. The query should return the following columns: year, num_games, avg_critic_score, avg_user_score, and diff. The diff column should be the difference between the avg_critic_score and avg_user_score. The table should be ordered by the year in ascending order.

  

