# Sparkify - Udacity data scientist nanodegree capstone project

### Table of Contents

1. [ Installation ](#installation)
2. [ Project Motivation ](#motivation)
3. [ File Descriptions ](#filedesc)
4. [ Results ](#results)
5. [ Licensing, Authors ](#licensing)

## 1. Installation <a name="installation"></a>
Notebook for this article was developed using Python v3.6.3, Pyspark v2.4.3, Pandas v0.23.3, Matplotlib v2.1.0 and Seaborn v0.8.1.

## 2. Project Motivation <a name="motivation"></a>
Purpose of this notebook/article is, using Spark framework, to predict whether users of a fictitious audio streaming platform, Sparkify, are likely to unsubscribe. This is a capstone project for the Udacity data scientist nanodegree program.

## 3. File Descriptions <a name="filedesc"></a>
* _Sparkify.ipynb_ contains all the code allowing data load, manipulation, and graph generation.
* _Sparkify.html_ is the same, in HTML format.
* _mini_sparkify_event_data.zip_ is a copy of the dataset used for our notebook (JSON format).

Article is available on [Medium](https://medium.com/@olivier.klein/sparkify-udacity-data-scientist-nanodegree-capstone-project-65e3181ea2b0?sk=8d8f3c4b066695ee12c27d0411584609).

## 4. Results <a name="results"></a>
Using different machine learning classifiers, we achieved a F1-score of 0.7 with default parameters; we could improve this to 0.73 after fine-tuning parameters with a grid search.

From an analysis perspective, we could notice that the most important features used by the classifier are the number of "thumbs up" / "thumbs down" given by user per song, number of friends added per session, percentage of songs added to playlists, number of adverts and number of songs per session; we can indeed assume that these parameters are representative of the customer's satisfaction with the service, either negatively or positively.

## 5. Licensing <a name="licensing"></a>
Dataset and image used for this notebook/article are owned by [Udacity](https://www.udacity.com).
