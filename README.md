# Investigate-a-Dataset---TMDb-movie-data

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
<!-- Table of contents -->
## Table of contents

- [Table of contents](#table-of-contents)

- [About the project](#about-the-project)

- [Pre-requisites](#pre-requisites)
  
- [License](#license)

## About the project


 This project consists of the analysis of a dataset made up of various information about movies. It contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. The columns are:
+ *id*: the id of the movie in the dataset
+ *imdb_id*: the id of the movie in the IMDB dataset
+ *popularity*: a number indicating the popularity of the movie
+ *budget*: the budget allocated for the making of the movie
+ *revenue*: the revenue obtained from the making of the film
+ *original_title:* the title of the movie
+ *cast*: the actors/actresses of the movie, a string separated by pipes
+ *homepage*: the link to the movie
+ *director*: the director
+ *tagline*: the catchphrase of the movie
+ *keywords*: the keywords of the movie, a string separated by pipes     
+ *overview*: a brief description of the film              
+ *runtime*: the duration of the movie                
+ *genres*: the genres of the movie, a string separated by pipes         
+ *production_companies*: the production companies of the movie, a string separated by pipes 
+ *release_date*: the release date of the movie            
+ *vote_count*: the number of public votes           
+ *vote_average*: the average obtained by the film          
+ *release_year*: the year of release of the film           
+ *budget_adj*: the budget in terms of dollars in 2010 taking into account the inflation
+ revenue_adj*: the revenue in terms of dollars in 2010 taking into account the inflation

> It is available [here](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

During my analysis I have tried to provide answers to the some questions like:

+ Is there a relationship between the popularity of a film and its budget?
+ Is there a relationship between the popularity of a film and its genre?
+ Does the presence of an actor affect the popularity of a film?



## Pre-requisites

In order to run this project it is required to install python and some of its libraries:
- Python 3.7 or more
- Pandas 
- Numpy
- Matplotlib
- Seaborn
We recommend that you install Anaconda, which comes with all the necessary packages, as well as the IPython Notebook. 


## License
Distributed under the MIT License. See [LICENSE](./LICENSE) file for more information.



