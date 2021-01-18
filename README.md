# Deep_Learning

Overview of the analysis:
This project is aim at to help to predict if applicants that will be found by a charitable organization. For this machine learning analysis, we compromised three steps:
•	Preprocessing the data for the natural network
•	Compile, train and evaluate the model
•	Optimizing the model 
Results: 
•	Data Preprocessing
1.	“IS_SUCCESSFUL” was considered as target variable
2.	Variables considered as feature except target variable and noisy variable such as EIN and Name
•	Compiling, Training, and Evaluating the Model
1.	For the neutral network, I had two hidden layers. First layer had 80 neurons, the second had 30 neurons. I had “relu” activation for both layers and output
2.	Based on the nn.summary, the accuracy is 66%, which means the model was not able to achieve target model performance 75%
3.	I have attempted three ways to increase the performance 
	Remove additional noisy feature Speical_consideration, however, the accuracy went down to 53%
	Adding additional neurons to hidden layers and add one more hidden layer, but the accuracy did not go up still at 53%
	Changing activation function of hidden layers, however, the accuracy did go down to 45

Summary: throughout the project, the model accuracy was around 50% after optimization which is much lower than initial accuracy which had 66%. The loss of accuracy could be explained that the model is overfitted and we alternately could apply random forest classifier. 
