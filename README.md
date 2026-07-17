
# Project Title

Data Science NanoDegree Program Pipeline Project: Review Recommendation Prediction

This project builds a machine learning pipeline to predict whether a customer recommends a product (`Recommended IND`) using customer review data. The dataset contains numerical, categorical, and text features that are processed through a Scikit-learn pipeline.

## Getting Started

Instructions for how to get a copy of the project running on your local machine.

### Dependencies
```
- Python 3.x
- pandas
- numpy
- scikit-lear
```

### Installation
```
1. Download or clone the project files.
2. Install the required packages:
# Install requirements
python -m pip install -r requirements.txt
```
## Testing

The machine learning pipeline was trained and evaluated using a train-test split of the dataset. Model performance was measured before and after hyperparameter tuning

### Break Down Tests
The following evaluation metrics were used:

- Accuracy Score: Measures the overall percentage of correct predictions
- Hyperparameter Tuning Comparison: Compares baseline model performance with the optimized model obtained through RandomizedSearchCV.

These tests help determine how effectively the pipeline predicts whether a customer recommends a product.

## Project Instructions

## Built With

* [data/reviews.csv](https://github.com/jwnam1707-star/dsnd-pipelines-project/blob/main/starter/data/reviews.csv) - Dataset used for training and evaluating the recommendation prediction model
* [starter_notebook.ipynb](https://github.com/jwnam1707-star/dsnd-pipelines-project/blob/main/starter/starter.ipynb) - Main notebook containing data exploration, feature engineering, model training, and evaluation

## License

This project was completed for educational purposes as part of the Data Science Nanodegree Program.