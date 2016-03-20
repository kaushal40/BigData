# BigData
Hadoop Map reduce, Pig, Hive, Spark and Scala base assignments for BigData course at UTD

Hadoop - Map Reduce : 

(1) Haddop mapreduce program to find userId's belongs to zipcode

(2) Find top 10 average rated movies with descending order of rating.

(3) Find all the user ids who has rated at least n movies.

(4) Given some movie titles in csv format - find all the genres of the movies.

(5) Find the top 10 zipcodes based on the average age of users belong to that zipcode, in the ascending order of the average age.

Map Reduce Joins

(1) Map Side Join

(2) Reduce Side Join


Pig - Hive

(1) Pig - Hive Scripts and User Defined functions to do some analytics


Spark

(1) Given a input zipcode, find all the user-ids that belongs to that zipcode. You must take the input zipcode in command line.
Find top 10 average rated movies with descending order of rating.
Part II Mahout and Recommendation

(2) Apply item-based collaborative filtering using mahout’s spark-itemsimilarity. spark-itemsimilarity can be used to create "other people also liked these things" type recommendations.
Construct the item-similarity matrix of each movie having rating 4 (use ratings.dat)
Using Apache spark interactive shell. Take the user id as input. Now finds all the movies that he rates as 4.
Find the movies that match with the user’s rated movies with the key of the item-similarity file.
Reference https://mahout.apache.org/users/recommender/intro-cooccurrence-spark.html
