# linear_regression_ml

This repo contains 2 instance of linear regressions models: 1. Univariate 2. Multivariate

For the multivariate model, it aims to predict the insurance cost. The variables:
Age: insurance contractor age, years. Restricted this to 18+ years based on an assumption that that's the age one can be have track of their health insurance.

Sex: insurance contractor gender, _[female, male]_

BMI: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight. Set this to pick only BMI above 23.5

Children: number of children covered by health insurance / Number of dependents

Smoker: smoking, _[yes, no]_

Region: the beneficiary’s residential area in the US, _[northeast, southeast, southwest, northwest]_

Charges: Individual medical costs billed by health insurance, $ #predicted value

# API Endpoint link:

https://price-prediction-model-4ns5.onrender.com

## NOTE

For the POST, please ensure to include the "/predict" part so the link will be like this:
"https://price-prediction-model-4ns5.onrender.com/predict"

On postman, on the dropdown, choose raw and JSON. Then use the body section to put in your values and press send to get your output.

Your interface should look like this:
![image](https://github.com/user-attachments/assets/8c5bfb1b-c99f-45ce-bf2d-2490e54be444)

HAVE FUN PLAYING WITH THE DATA!
