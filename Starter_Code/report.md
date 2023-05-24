# Report on Neural Network Model

# Overview

The purpose of this analysis is to use a deep learning model to predict if the Alphabet Soup's fund applicants will be successful. Based on the Alphabet Soup's original data we aim to see how accurately we may be able to infer success.

# Results

Data Preprocessing:

	- The target variable for this model was the "IS_SUCCESSFUL" column, which indicates success or failure
	- The feature variables for this model included "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", and "ASK_AMT"
	- The variables that were removed from the input data because they were neither targets, nor features, were "EIN" and "NAME"

Complaining, Training, and Evaluating the Model:

	- The original model contains two hidden layers with 80 and 30 neurons, respectively. The "relu" (Rectified Linear Unit) activation function was used in order to incorporate non-linearity to the model.
	- I was not able to achieve the target model performance.
	- The steps I took in an attempt to increase the model's accuracy were the following
		- Increase the number of neurons in the first hidden layer from 80 to 120.
		- Add a third hidden layer (with 15 neurons).
		- Increase the number of epochs during training from 100 to 150.
Summary:

	- In summary, the original model (and very closely performing optimized model) was able to predict the success of Alphabet Soup's fund applicants with 73% accuracy. In the future, more feature variables may potentially lead to a higher accuracy as the model may have more relevant information to learn from. Though 73% accuracy is not ground breaking, it certainly shows proof of concepts and further exploration would be warranted

