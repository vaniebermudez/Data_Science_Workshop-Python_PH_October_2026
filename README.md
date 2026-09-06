# Weather-Weather Lang: What Can Data Tell Us?

A hands-on Data and AI workshop by Python Philippines. We use real-world Australian weather data to walk through a complete machine learning classification workflow, from raw data to trained, evaluated models.

## About This Workshop

You never really know what the weather will be, but what if the data can give us a clue? In this workshop, we use real-world weather data to explore how machine learning can uncover patterns and help us make predictions. Using Python, we go through the essential steps of an ML workflow: preparing data, choosing useful features, training a model, and evaluating its predictions. Along the way, we demystify concepts like features, labels, classification, training and test data, accuracy, and overfitting through a practical, end-to-end example.

**Target audience:** Intermediate Python users who are comfortable with Python but curious about taking the next step into Data Science and Machine Learning. No prior ML experience required.

**Duration:** 2 hours

## What You Will Learn

* The difference between classification and regression
* Handling missing data (drop vs. impute) and encoding categorical variables
* Why feature scaling matters for some models and not others
* Training and comparing three classification models: Logistic Regression, Decision Tree, and Random Forest
* Evaluating models beyond accuracy: confusion matrix, precision, recall, and F1-score
* What overfitting looks like in practice, and how to manage it

## Repository Contents

| File | Description |
|---|---|
| `ds_workshop_participants.ipynb` | The full hands-on Jupyter notebook. Data loading, cleaning, feature selection, model training, evaluation, and an overfitting demonstration. |
| `Weather_Weather_Lang_Workshop.pdf` | Full slide deck used to teach the concepts alongside the notebook. |
| `weatherAUS.csv` | The dataset on Australia Weather. |
| `requirements.txt` | The set of packages needed for this workshop. |

## Dataset Source

This workshop uses the **Australia Weather Data** dataset from Kaggle:

[https://www.kaggle.com/datasets/arunavakrchakraborty/australia-weather-data](https://www.kaggle.com/datasets/arunavakrchakraborty/australia-weather-data)

Download `weatherAUS.csv` from this repository instead so it works well with the notebook.

## Getting Started

### 1. Clone this repository

```bash
git clone <your-repo-url>
cd <your-repo-folder>
```

### 2. Install dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

OR create a virtual environment first then,

```bash
pip install -r requirements.txt
```


### 3. Run the notebook

```bash
jupyter notebook ds_workshop_participants.ipynb.ipynb
```

Run the cells from top to bottom. Each section builds on the previous one.

## Workshop Outline

1. **Kickoff and Framing** (10 min): Introducing the big question, can data predict tomorrow's rain?
2. **Understanding the Problem and the Data** (15 min): Classification vs. regression, exploring the dataset
3. **Data Preparation and Feature Selection** (25 min): Handling missing values, encoding categorical variables, feature scaling, selecting our final feature set
4. **Train/Test Split and Model Training** (25 min): Splitting the data, training Logistic Regression, Decision Tree, and Random Forest
5. **Evaluation** (20 min): Accuracy, confusion matrix, precision, recall, F1-score
6. **Overfitting and Model Improvement** (15 min): Comparing train vs. test accuracy, what causes overfitting, and how to manage it
7. **Wrap-up and Q&A** (10 min): Recap and next steps


## What's Next

Ideas for extending this workshop or your own exploration:

* Feature engineering, for example a temperature range feature (MaxTemp minus MinTemp)
* Hyperparameter tuning with `GridSearchCV`
* Trying other models such as XGBoost, KNN, or Support Vector Machines
* Deploying a trained model with a simple Streamlit app

## Credits

* Dataset: [Australia Weather Data on Kaggle](https://www.kaggle.com/datasets/arunavakrchakraborty/australia-weather-data), originally sourced from the Australian Bureau of Meteorology
* Workshop created for Python Philippines