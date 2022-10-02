# Tasks

<div style="text-align:center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/IBM_logo.svg/2560px-IBM_logo.svg.png" style="width:50%;">
</div>

The project will be divided into the following tasks;
## I. Exploratory Data Analysis
I explore the data before diving into the findings. There are some basic, required questions to be answered about the data. I will use this space to explore, before diving into the details of the recommendation system in the later sections.
## II. Rank Based Recommendations
To get started in building recommendations, I will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).
## III. User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. I implement this in section IV.
## IV. Content Based Recommendations (EXTRA - NOT REQUIRED) : TODO
Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using NLP skills, there might come up with some extremely creative ways to develop a content based recommendation system.
## V. Matrix Factorization
Finally, completing a machine learning approach to building recommendations. Using the user-item interactions, I build out a matrix decomposition. Using decomposition, you will get an idea of how well I can predict new articles an individual might interact with (spoiler alert - it isn't great). Finally discussing which methods I might use moving forward.
