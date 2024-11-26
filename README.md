# Car Insurance Claim Prediction

## Project Overview
This project aims to predict car insurance claims using machine learning techniques. The model uses various features such as car details, driver information, and past claim history to determine the likelihood of a claim being made. The project is built using Python and Deep learning methods like Artificial Neural Network, with key libraries such as **Pandas**, and**Scikit-learn** for data preprocessing, model training, and evaluation.


## Dataset
The dataset used for this project contains the following columns:
- **MSTATUS**: Marital status of the individual
- **GENDER**: Gender of the individual
- **EDUCATION**: Education level
- **OCCUPATION**: Occupation of the individual
- **TRAVTIME**: Time spent traveling
- **CAR_USE**: Use of the car (personal or commercial)
- **BLUEBOOK**: Bluebook value of the car
- **TIF**: Insurance policy type
- **CAR_TYPE**: Type of car
- **RED_CAR**: Indicator if the car is red
- **OLDCLAIM**: Previous claims
- **CLM_FREQ**: Claim frequency
- **REVOKED**: Whether the individual’s insurance was revoked
- **MVR_PTS**: Motor vehicle record points
- **CLM_AMT**: Claim amount
- **CAR_AGE**: Age of the car
- **CLAIM_FLAG**: Whether a claim was made (target variable)
- **URBANICITY**: Urban or rural area

## Model
This project uses a **Random Forest Classifier** to predict the target variable **CLAIM_FLAG**, which indicates whether a claim will be made. 

### Steps:
1. Data Preprocessing:
   - Handling missing values
   - Encoding categorical features
   - Feature scaling and normalization

2. Model Training:
   - Split the dataset into training and testing sets
   - Train the model using the training set

3. Model Evaluation:
   - Evaluate the model on the test set 

## Results
The model achieves an accuracy of **99%** on the test dataset. 

