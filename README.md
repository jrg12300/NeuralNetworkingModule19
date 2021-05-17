# NeuralNetworkingModule19

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions.

What variable(s) are considered the target(s) for your model?
  IS_SUCCESSFUL
What variable(s) are considered to be the features for your model?
  APPLICATION_TYPE, ASK_AMT, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS (maybe, I tried with and wihtout this variable), INCOME_AMT, SPECIAL_CONSIDERATIONS
What variable(s) are neither targets nor features, and should be removed from the input data?
  EIN & NAME
How many neurons, layers, and activation functions did you select for your neural network model?
  2 layers,m 8 for first layer, 5 for 2nd layer
Were you able to achieve the target model performance?
  I was not. Next week I am going to attend office hours to discuss why with a TA. I think some of the reasoning I did not understand.
What steps did you take to try and increase model performance?
  I manipulated the number of layers, neurons, the amount of aspects in the "other" category for APPLICATION_TYPE & CLASSIFICATION, and adjusted the number of epochs

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
  My model only got to 57% accuracy. I need to find a model that would increase this. The next step is to try PCA and use the different supervised machine learning models covered in module 17.
