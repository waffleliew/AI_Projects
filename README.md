# Predicting Diseases with Deep Learning (LSTM Model)

Deep Learning has already shown remarkable success in many industries by helping us to automate the processes.
In the field of medicine, Deep Learning can be used to train models to predict diseases and recommend medications based on a patient’s symptoms.
In this project i will try to build a deep learning model that will be trained on Patient’s symptoms (textual data), then our model will give the predicted Disease as an output.

This is clearly an application of Recurrent Neural Network (RNN). This is because we need a model that will store the information from the previous text and use it later to predict the output. Hence, we will use the Long Short-Term Memory (LSTM) algorithm with Tensorflow to train our model.

Of note: The deep learning model is built using TensorFlow, a popular open-source library for machine learning. The model architecture utilizes an LSTM layer to process the sequence of tokens representing the patient’s symptoms. It is recommended to run the notebook on Google Colab.

