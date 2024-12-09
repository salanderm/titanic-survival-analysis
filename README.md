# Titanic Survival Prediction

This project uses machine learning to predict the survival of passengers on the Titanic based on demographic and ticket information. The dataset and notebook explore relationships between variables and train a model to classify whether a passenger survived or not.

## Project Overview

### Dataset
The dataset (`titanic.csv`) includes the following columns:
- **PassengerId**: Unique identifier for each passenger.
- **Survived**: Survival status (0 = No, 1 = Yes).
- **Pclass**: Passenger class (1 = First, 2 = Second, 3 = Third).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard the Titanic.
- **Parch**: Number of parents/children aboard the Titanic.
- **Ticket**: Ticket number.
- **Fare**: Ticket fare.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

The dataset contains **891 rows**.

### Notebook
The notebook (`titanic-survival-prediction.ipynb`) contains:
- **Data Loading**: Loads and inspects the Titanic dataset using `pandas`.
- **Exploratory Data Analysis (EDA)**: Investigates relationships between features and survival rates.
- **Feature Engineering**: Prepares the data for modeling, handling missing values, and encoding categorical variables.
- **Model Training**: Builds a classification model to predict survival using features such as passenger class, gender, and age.
- **Evaluation**: Evaluates the model's performance using metrics like accuracy.

### Features
- Predicts whether a passenger survived based on input features.
- Analyzes key patterns and relationships in the dataset.
- Visualizations to understand the distribution of survival across demographic groups.

## How to Run

1. **Setup**:
   - Install Python and Jupyter Notebook.
   - Install required libraries:
     ```bash
     pip install pandas numpy matplotlib scikit-learn
     ```

2. **Run the Notebook**:
   - Place `titanic.csv` in the same directory as `titanic-survival-prediction.ipynb`.
   - Open and execute the notebook step-by-step in Jupyter Notebook.

3. **Input New Data**:
   - Replace or update the `titanic.csv` file for predictions on new data.

## Requirements

- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`

## Outputs

- Survival predictions for passengers based on their data.
- Visualizations of survival rates by gender, class, and other factors.
