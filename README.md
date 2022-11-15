# Movie-Recomendation-System

In this recommender system the content of the movie (overview, cast, crew, keyword, tagline etc) is used to find its similarity with other movies. Then the movies that are most likely to be similar are recommended.

![image](https://user-images.githubusercontent.com/72307168/201926134-01e27f38-f5f9-4345-9c1c-9e0a5a297d1e.png)


--> DATASET :

This dataset is taken from https://www.kaggle.com/code/ibtesama/getting-started-with-a-movie-recommendation-system/data

--> METHODOLOGY :

The selected features used in this project are :

● Genre

● Keywords

● Tagline

● Cast

● Director

The rest of the features used are : budget, original_language, original_title, overview, popularity, production_companies, production_countries,release_date, revenue, runtime, status, title, vote_average, vote_count.

The textual data was then converted into feature vectors(numerical values) with the help of TfidfVectorizer so that we can use cosine similarity on the numerical data which is imported from sklearn module.

--> OUTPUT :

The user enters the movie name and therefore he gets the resultant output :

![image](https://user-images.githubusercontent.com/72307168/201927421-0dcf190a-06b9-48dd-bbb2-989bfc30da49.png)
