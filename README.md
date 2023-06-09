# Microsoft Movie Studios

 
## Goal

In order to provide feedback to the Microsoft CEO, board and shareholders, project managers on team for Microsoft Studio, CFO and other important department heads, we first had to define what a successful movie studio does. It seemed important to measure a Movie Studios success in-terms of Worldwide Gross intake. We asked the question, what makes a movie successful in grossing high Worldwide? While there are many factors this analysis will focus on movie genre, runtime, and budget.

# Data 
In order to analyze important data we have analyzed two important datasets. The first data set "imdb", is a dataset with many valuable data points. Included in this movie database is movie basics, directors, known for, movie aka's, movie ratings, persons, principals, and writers. For the purposes of this project the focus was on movie basics. The subcategory in movie basics that were directly analyzed included runtime, and genre. In order to analyze this data SQL was initially used. The second database used was tn.movie_budgets.csv'. To import this data PANDAS was used. This data included budget, and worldwide gross. In order to completely analyze the data one database was created merging the imdb and tn.movie_budgets.csv.

[im.db.zip](https://github.com/learn-co-curriculum/dsc-phase-1-project-v2-4/blob/master/zippedData/im.db.zip)

[tn.movie_budget](https://github.com/learn-co-curriculum/dsc-phase-1-project-v2-4/blob/master/zippedData/tn.movie_budgets.csv.gz)

### Genre's impact on Worldwide Gross

Important questions regarding these variables included the following: What genre of movies are best for producing high grossing worldwide movies? What movies genres fail to produce high grossing worldwide movies? The graph shows that genres such as Action, Adventure and Sci-Fi are most likely to produce an outlier that may result in extremely high grossing movies. Animation's median worldwide gross is also very high at around .25 Billion. Based on this information I would recommend that Microsoft produce Animation, Action, Adventure, and Sci-Fi movies. Also based on this graph I would recommend that Microsoft avoids making news, war, history, western, documentary and musical movies.

![image](https://github.com/jguzzo522/presentation/assets/75549456/8ac5671c-8f2d-4fc9-9a93-a75b649049f5)

### Movie runtime's impact on Worldwide gross

Important questions regarding runtime: How long should a movie be to produce the highest possible worldwide gross?
Based on the data provided from the combined databases, the optimal runtime should be over 120 minutes. In order to measure optimal runtime we broke the runtime category up into 3 subcategories. Short run time was defined as any movie running less than 60 minutes long. Medium runtime was any movie running between 60-120 minutes, and long runtime was any movie running longer than 120 minutes. There was not much difference between short and medium runtime movies. However, there were more outliers in medium runtime movies that produced movies that grossed upwards of a billion dollars. The short run time movies did not produce any movies grossing over a billion dollars. Long runtime movies median value was around.20 billion dollars. In addition many movies were outliers in this category, including many movies grossing over 1 billion dollars. Based on the data and the graph below, it is recommended that Microsoft invests in longer runtimes.

![image](https://github.com/jguzzo522/presentation/assets/75549456/3d1a77f8-0f31-4e8a-97e7-eac2cbdb8e2c)

### Movie budget's impact on Worldwide Gross

Important questions regarding budget: What type of budget creates the highest grossing films? Is there a big difference to justify larger budgets?
In order to address these questions, it was important to breakdown the data of budgets into small (bellow 50 million dollars), medium (50-100 million dollars) and large (100+ million). As predicted small budgets produced the least grossing films. Small budget films median gross was less than .1 billion dollars. While the median gross for large budgeted films was around .5 billion dollars. Medium movies also did much better than small budget films, with a median gross value around .2 billion dollars. Not a single small budget film produced a billion dollar gross. There were a very small amount of medium sized budgets that produced a billion dollar gross. Large budget films produced several movies grossing over a billion dollars. Higher budget films also produced a few movies grossing over two billion dollars. Based on this analysis , large budget films are worth the investment.

![image](https://github.com/jguzzo522/presentation/assets/75549456/3f759f67-296b-466f-adf0-c70cb80e94d8)

## Recommendations

Based on the data analysis, if Microsoft wants to produce high worldwide gross movies, I highly recommend that Microsoft considers making movies with a genre of Sci-Fi, Adventure, Animation and Action. I highly recommend that Microsoft Studios avoids movies such as news, war, history, western, documentary and musical movies.

Investments should be made in longer-running movies over two hours in length. Microsoft should avoid making short movies if the desired outcome is grossing over a billion dollars. No short length movie has made over a billion dollars and very few medium length movies have grossed over a billion dollars.

Microsoft should produce movies with higher budgets. A healthy budget of over 100 million dollars seems to be key to making a movie grossing over a billion dollars Worldwide. Movies that gross high seem to have a direct coorelation with their budget. 

## Further Investigation 

While this project was limited in scope, a suggestion of further analyzation of movie genre, and runtime combined may be interesting. For instance family animation movies, that produce high gross returns, may not need to be as long as an action film. In addition if Microsoft would like to make more movies with lower budgets, it may not be advisable for the studio to make action, or animation films due to the high cost of CGI. It may be a smarter business plan to make movies such as drama, romance and comedy if the studio is providing a smaller budget. However, more analyzation would need to be done to make this recommendation.

## Contact info
Jessica Guzzo(Student)
Email:JGuzzo522@gmail.com



[Presentation1.pdf](https://github.com/jguzzo522/project1/files/11709375/Presentation1.pdf)

[Project 1.pdf](https://github.com/jguzzo522/project1/files/11729876/Project.1.pdf)

