# The Simpsons #Data_Analytic
Today we are going to take a look at the beloved series but from a data point of view, We analyzed the rate of each episode since the start of the series trying to understand our love story for the show.

## The Simpsons
Who don't know the beloved American animated sitcom created by Matt Groening as satirical depiction of American life, epitomized by the Simpson family, which consists of Homer, Marge, Bart, Lisa, and Maggie. The show is set in the fictional town of Springfield and parodies American culture and society, television, and the human condition.
With 34 seasons and around 730 episodes The program is something different in terms of success and continuity.

## The Data
We analyzed the ratings for each episode of the series based on IMDB's database, which you can get through [AWS](https://developer.imdb.com/)  for 1 month free trail and a lots of money after that. 

## Let's start
We have the Data of 728 episodes, contain the name and description and of course the rate for each of them.

### First chart
We will do the simplest form of analysis and draw ratings for each of the episodes, From the diagram, we will notice two points
- There are a number of episodes in each season that are clearly above or below average rating.
- There is a slight decline in episode ratings compared to the initial episodes.

![Episodes [1–728] Rate from 10](https://cdn-images-1.medium.com/max/800/1*S0YWpnSd1qm6OLVFyXzXYw.png)

### Season AVG rate
Let's do something more useful and calculate the average ratings for each season individually.

The show **started with a rating of 7.7** and gradually increased until **Season 7, where it achieved its highest rating of 8.4**, After that, the gradual decline began to reach **season 16 (17 previous season), where the last time the show achieved a 7 rating!!**

![ِAVG Rating for each seasons](https://cdn-images-1.medium.com/max/800/1*6vIKYxX4Rlimq5zHSOpNmg.png)

### Low/High Points
The worst moments of the series during his long life were in 2012, season 23 episode 22, **Lisa Goes Gaga** The episode revolves around Lisa’s attempt to get popular and Lady Gaga as a guest, although the episode failed to get more than 4 points reviews.

Other low rated episodes S33E1 The Star of the Backstage 4.3 rating and S30E18 Bart vs. Itchy & Scratchy 4.9 rating, with more than 700 episodes, getting only three weak ratings is a real achievement.

And now for the high points​, **12 episodes** managed to get a **rating of 9 and above**, Highest Rated Episodes from Season 8 Episode 23 **Homer’s Enemy** With a rating of 9.3 and one angry Frank Grimes.

Other episode with the 9+ rating are S6E6 **Tree house of Horror V**, S8E2 **You Only Move Twice** S4E12 **Marge vs. the Monorail**, S5E2 **Cape Feare**, S6E25 **Who Shot Mr. Burns? Part One**.

There is clearly a recurring pattern here and that's what we'll explore in the next diagram​.

### Low and High through the seasons
We decided to explore more about the distribution of high and low ratings across seasons, We counted the episodes within each season with ratings in the high range and ratings in the low range, and that the chart we get.

![Count of episodes with low/high rating](https://miro.medium.com/max/720/1*BheAHWAtvEGS7p7mJC5_SA.png)

And YES all the high rating episodes come in first seasons and the low one all in the last seasons.

### Rate by Character
Finally, the question I was trying to get an answer for the most, who is the most high rated characters?

Depending on the description of each episode, we will see the average rating of the episodes for each character, Where we will first determine for each character the episodes in which they appeared and then calculate the average rating for all episodes.

It's not fair to compare the characters together because the number of each of them participating in the episodes is significantly different, Therefore, we will divide the classification into three groups.

#### The Family

We do love them all, but little more for the little one **Maggie​**​.

#### Important characters in the story

On both sides of the evil spectrum **MR. Burns**​​ and **Flanders​​**​.​

#### Minor characters

your drinking best friends **Barney**​, goofy **Ralph**​ and **MS. Krabappel**​.

### NEXT
What your favorite episode of the show and what you want to see next?

## Contact me
 