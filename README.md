# Recommendation system

> party recommendation system based on movie
<br>

- Presentation video

[![Video](http://img.youtube.com/vi/B2-ZLfRzzho/0.jpg)](https://www.youtube.com/watch?v=B2-ZLfRzzho) 

## Built With

* [김영서](https://github.com/youngseo0526) - Main coder
* [백서희](https://github.com/soycong) - Leader & Main coder
* [서현수](https://github.com/hyunsoo41) - Main coder
* [최다경](https://github.com/DaGyeongChoi) - Main coder

## Getting Started

### Prerequisites

- Dataset

  Download `ml-latest-small.zip` from [here](https://grouplens.org/datasets/movielens/latest/)
  
  Alternatively, you can clone this repository and use `data\ml-latest-small` directly without downloading the dataset.
  

### Installing

- Window:

```
cd [root_path]
pip install matplot
pip install seaborn
pip install pandas
pip install numpy
```

## Running the tests

run `movie_recommendation_soy.ipynb`

## Comprehensive Reference

In `Ratings.csv`, using calumn `timestamp` that time the user started watching a movie, classify datatime into 6 groups with 4-hour intervals.

|matrix_number|hour|
|:---:|:---:|
|h1|00 ~ 03|
|h2|04 ~ 07|
|h3|08 ~ 11|
|h4|12 ~ 15|
|h5|16 ~ 19|
|h6|20 ~ 23|

<br>
<img width="661" alt="스크린샷 2022-01-09 오후 7 19 19" src="https://user-images.githubusercontent.com/60006301/148678194-dd641e3a-e4d3-4e39-ad5a-dc850cf03619.png">


## Acknowledgments

* [source code1](https://www.kaggle.com/ibtesama/getting-started-with-a-movie-recommendation-system)
* [source code2](https://www.kaggle.com/rounakbanik/movie-recommender-systems)
* [netflix prize](https://journals.sagepub.com/doi/full/10.1177/1461444814538646)
