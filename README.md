# Gigly_Monkeys_Studios



## 1. Introduction
In the world of film production, there are different niches-commercials, documentaries, feature films, music videos etc. The analysis is important as it will enable Microsoft, under the name of Gigly Monkey Studios to determine the specific niche and how it will meet the market needs.
## 1.1. Business Understanding
### 1.1.1 Problem Statement
Inorder to be successful, one needs to find what's right for them and laying the proper foundation is essential to ones growth and success. This analysis therefore seeks to determine what is the best niche for Gigly Monkey Studios to consider, budget implications inorder for them to be successful.
### 1.1.2 Aim
The pupose is to attract viewership and generate revenue.
## 1.2 Objectives
### 1.2.1 Broad Objective
It is to conduct an analysis of the production industry inorder to choose the best option that will enable best success

### 1.2.2 Specific Objective
1. What is the general trend in the production industry?
2. Who are their competitors? 
3. What are the top 5 rated productions based on ratings? 
4. What are the top 5 rated productions based on incomes earned? 
5. What is the relationship between production cost and other variables in production industry?

## 2. Data Understanding
The data used during the analysis was from four files. bom_movie_gross file that had 3387 rows and 5 columns. The second data was movie_ratings file that had 73856 rows and 3 columns. The third is movie_basics file that had 146144 rows and 6 columns. The last data came from movie_budgets that had 5782 rows and 5 columns

## 3. Data Modelling
After importing and loading the data using required librabries, they underwent cleaning. This process involved removing unwanted characters from figures, changing data types, locating and deleting null rows and columns, deleting unwanted columns(based on the objectives), removing duplicates and later on merged where possible. 

## 4. EDA
Exploratory data analysis was then conducted and and conclusions stated. This process involved checking the correlation between various elements and trends over the years 


## 5. Conclusion
Film production is a lucrative field. Since 2012, the production industry has been growing. There instances when production decreased(2013-2014) but an inceaese was seen later on (2014-2015) and reaching a peak in terms of number of films produced. 
image_1.png

The average budget for a production is USD 3.473329e+07. The returns from this is an average domestic and worldwide gross incomes of USD 4.358103e+07 and USD 1.043842e+08. For a production, The minimum runtime minutes is 3 min and the maximum runtimes minutes is 280min. 
image_2.png

Production budget is weakly positively correlated with runtime minutes and average rating. ***Higher production cost does not imply more runtime minutes and increased rating.***. Production budget is highly correlated with domestic gross and world wide gross. ***This implies that, the more cost incured during the production, the higher the domestic and worldwide gross hence more profit***. It can also be noted that domestic gross is highly positively correlated with worldwide gross. An increase in domestic gross leads to an increase in worldwide gross. 

image_3.png

image_4.png

The top 5 productions are classified under drama, documentary, commedy, commedy/drama and commedy/drama/romance. Since 2012, drama has the highest number of productions at total of roughly 290 productions and  commedy/drama/romance being the least in terms of number of productions in the top-5 category with a total of around 75 productions since 2010.  
image_5.png


Although the drama genre is highly produces, it is not amongs the top 10 in terms of ratings. Production with the best ratings are those under Action-Documentary-Drama genre at 8.70 
image_6.png


The top 5 most profitable films are Family/Fantasy/Musical, Adventure/Drama/Sport, Fantasy/Romance,Action/Adventure/Sci-Fi and Adventure/Fantasy. 
image_7.png



## 6. Recommendations
1. Film production is a profitable business (as seen by the growth and domestic gross depicted) hence Microsoft (Gigly Monkeys Studios) should invest in the same.
2. To increase on its gross incomes both locally and internationally, Gigly Monkeys Studios should invest in the production budget.
3. Most of the productions made fall in either of the following categores: drama, documentary, commedy, commedy/drama and commedy/drama/romance
4. To be able to make profitable films, Gigly Monkeys Studios should produce films in the following categories: Family/Fantasy/Musical, Adventure/Drama/Sport, Fantasy/Romance,Action/Adventure/Sci-Fi and Adventure/Fantasy.

