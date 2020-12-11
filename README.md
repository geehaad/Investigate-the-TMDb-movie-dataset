# Investigate-the-TMDb-movie-dataset
The main purpose of this investigation is to find what makes the movie success, in other words, what can effect on the Revenue and the Rating of the movie, are the most popular movies make more money than others? does the actor effects on the movie popularity, and so on.

The dataset can be found at Kagle (https://www.kaggle.com/tmdb/tmdb-movie-metadata)

The TMDb Movie dataset, has been selected for investigation using NumPy and Pandas. 
The dataset is a collection of information on around 4800 movies, consists of two parts:
the first one contains information about the cast and crew of the movie, and the second part information on aspects such as popularity, budget, revenue, cast, directors, production house, date of release, runtime, and its rating.

The main purpose of this investigation is to find what makes the movie success, in other words, what can effect on the Revenue and the Rating of the movie, are the most popular movies make more money than others? does the actor effects on the movie popularity, and so on.

## Research  Questions
Q1: Which year has the highest release of movies?
Q2: Who is the actor with the largest number of movies?
Q3: What is the highest budget movies?
Q4: Which movie has the maximum popularity?
Q5: What is the relation between the actor appearence and the movie popularity?
Q6: Which Directors are most successful (Revenue\ Rating)?
Q7: Which movies have the highest vote_average? 
Q8: Movies with Longest and Shortest Runtime? Is there a Relation between Runtime and Rating?
Q9: What are the Top production Companies with higher number of Release?
Q10: Which countries that makes most Popular Movies?
Q11: The correlation between Movie properties

Conclusions:
<li> The investigation shows that Movies industry has evolved over years, and the year with highest release of movies is 2009. </li>
<li>It seems that Robert De Niro has the largest number of movies, Followed by Bruce Willis and both have 30 movies and Nicolas Cage with 29</li>
<li>The movie with the Largest budget is 'Pirates of the Caribbean: On Stranger Tides' with 380000000.0	$</li>
<li>And for popularity, 'Minions' is most popular movie.</li>
<li>Also we tried to figure out if the actor who appears in alot of movies is the factor that makes the movies popular or not, but it seems that the movie popularity doesnot strongly depends on the actor name</li>
<li>The directors are a strong factor in movies success, we tried to see who the top directors are, who appears to be Steven Spielberg acording  to the movies revenue, folloed by Peter Jackson</li>
<li>The top three movies according to voting are: Little Big Top, Me You and Five Bucks, Dancer, Texas Pop. 81 with 10.0 vote_average, this result is not a strong evidence, because there is difference in number of people who vote 
</li>
<li>It's interesting, the longest run time is 338 mins, which is about 5.6 hrs and the shortest is 14 mins.
The movie that has the largest runtime "carlos" doesnot have a little average, but it is also not large,
Same with popularity. 
and It doesnot seem that Poplution, Rate_average and Runtime strongly depends on each other.</li>
<li>Then we moved to see who maade this moves, we were interested to see the companies with higher number of released movies, and the top is "Paramount Pictures" followed by "Universal Pictures"<li>
<li>United States of America is the country made 'Minions', which is most popular. 
USA made about 3102 movie!<li>
<li>Then we use the coloration matrix to see The correlation between Movie properties</li>
<li>seems to be increasing with popularity, with Correlation near to 0.64</li>
<li>also there is a quiet strong relation between it and budget, with Correlation = 0.73</li>
<li>The correlation between revenue and vote average is 0.2. So vote average is not highly related to the revenue.</li>
<li>The correlation between revenue and runtime is 0.26. So runtime is not highly related to the revenue.</li>
