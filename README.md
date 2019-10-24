# MongoDB-with-pyMongo
This repository consist of the python code about MongoDB.

In this case, I want to make a new collection in mongoDB cluster by taking the data from one of their collection then I need to make it same as like the other collection.

First, this is the link that you can use to the connect to the data

Link to get the data : "mongodb+srv://admin1234:12345@cluster0-miqju.gcp.mongodb.net/test?retryWrites=true&w=majority"

Link to match the data : "mongodb+srv://userstudent:admin1234@cluster0-nnbxe.gcp.mongodb.net/test?retryWrites=true& w=majority"

I used two cluster because in the cluster that we need to match the data is full of memory for making new collection.


Well, this is the instruction :
1. Make new collection with 'clean_movies' name that same as movies collection in sample_mfilx database using collection movies_initial
2. Validation Data with
   1) All document in clean_movies and movie is same.
   2) Amount of document in clean_movies_putrisqiana collection and movie_collection are same.
   3) All document in clean_movies_putrisqiana collection and movies collection are same.
   4) All value in clean_movies_putrisqiana collection has the same value and same order with movies collection and the same order.
   
Hope it can be useful, and CMIIW.



