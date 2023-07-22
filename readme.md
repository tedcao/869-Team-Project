# Steps to do the ICR Competition
## Requirements: 
predict if the person has one or more of any of the three medical conditions (Class 1), or none of the three medical conditions (Class 0). You will create a model trained on measurements of health characteristics.

## Data Evaluation & Visualization

## Data Cleaning


## Feature Engineering


## Algorithms


# Data
### train.csv - The training set.
* Id Unique identifier for each observation.
* AB-GL Fifty-six anonymized health characteristics. All are numeric except for EJ, which is categorical.
* Class A binary target: 1 indicates the subject has been diagnosed with one of the three conditions, 0 indicates they have not.
### test.csv - The test set. Your goal is to predict the probability that a subject in this set belongs to each of the two classes.
### greeks.csv - Supplemental metadata, only available for the training set.
* Alpha Identifies the type of age-related condition, if present.
* * A No age-related condition. Corresponds to class 0.
* * B, D, G The three age-related conditions. Correspond to class 1.
* Beta, Gamma, Delta Three experimental characteristics.
* Epsilon The date the data for this subject was collected. Note that all of the data in the test set was collected after the training set was collected.
### sample_submission.csv - A sample submission file in the correct format. See the Evaluation page for more details.