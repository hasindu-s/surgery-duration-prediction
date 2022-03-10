# surgery-duration-prediction
Arthroplasty knee surgery duration predicting model using RandomForestClassifier and statistical calculation approach

## Dataset
I used [Surgery Timing](https://www.kaggle.com/toluoverscore/surgery-timing) dataset for this model. I hava decided to use only a one type of surgeries for this model and after analyzing selected Arthroplasty Knee surgery data

## Preprocessing
Preprocessing and selecting necessary data is done in **Preprocessing** notebook

## Model
Model is in **Complication Classification + Statistical Duration** notebook. **RandomForestClassifier** model uses patient's baseline information to predict whether there is going to be a complication during the surgery. According to this prediction, model calculates the duration using a statistical approach (consider age groups to calculate mean duration)
