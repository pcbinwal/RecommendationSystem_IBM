## Project Information
### Project motivation
In the IBM Watson Studio, there is a large collaborative community ecosystem of articles, datasets, notebooks, and other AI and ML assets. Users of the system interact with all of this. The requirement here is to created a recommendation system to enhance the user experience and connect them with assets. This in aimed at personalization of the experience for each user.

### Project Title

To create a Article Recommendation System based on user's interaction with various articles. 


## Getting Started

#### Dependencies

```
Dependencies are enlisted in requirements.txt file
```

#### Installation

```
1. Prepare the local environment
    - Install python
    - create VENV 
    - activate VENV
2. Prepare git and clone the repo
    - install git
    - initiate git
    - Clone this repo
3. Prepare and run the project
    - go to repo folder and install dependencies from requirements.txt
    - Run the notebook 
```



## Project Instructions

Project tasks covers following aspects: 

**__I. Exploratory Data Analysis__**   
There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Figuring them out and demonstrating the same. 

**__II. Rank Based Recommendations__**   
To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).   

**__III. User-User Based Collaborative Filtering__**   
In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

**__IV. Content Based Recommendations__**   
Since we are provided some content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, we'll come up with a simple method to cluster similar articles together so we can recommend related content that the user may have already interacted with.

**__V. Matrix Factorization__**   
Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with. You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.


## Licensing, Authors, Acknowledgements, etc.
### License
[License](LICENSE.txt)
### Author
Prakash Binwal
### Acknowledgement
- Udacity project motivation
- Other Datascience leaning and trainings
