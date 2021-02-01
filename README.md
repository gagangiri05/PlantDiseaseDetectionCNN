# Plant_disease_detection_CNN
Plant Disease Detection Using Convolutional Neural Network
# Problem Statement
A deep CNN based machine learning model that can be implemented as a smart phone
application for the recognition of plant diseases using plant leaf images.
Input: The leaf image of the disease infected plant captured from the camera of the phone
through app.
Output: The name of the disease the plant has been affected by and the necessary
information related to it.

# Objectives
• To design a CNN model to detect plant disease from leaf image.
• To implement an app to capture and process the leaf image and to obtain the desired
output.
• To minimize the usage of computational power and reduce the training time for the
model.
• To enhance the accessibility to the farmers by reducing expensive and complicated
hardware.

# Motivation
Agriculture is the backbone of India. The loss of crop due to plant disease may lead to
hunger and starvation and may result in fall of economy of the country. Thus agriculture has a
major influence on the economic, cultural and political development of a country. Continuous
and efficient plant disease prediction can prevent the loss of crop and thus increase the output
of the produce. The agricultural production cost can be significantly increased if plant
diseases are not detected and cured in early stages. The plants have to be monitored all the
time in order to detect the first symptoms of a disease before it spreads to the whole crop.
Remote monitoring through machine vision can provide an alternative option. Nondestructive
techniques like image processing can be used for plant disease diagnosis based on its
symptoms. There are many applications existing in the same domain which need high 
computational power to get accurate results. We believe that effectiveness of an application is
when it reaches the respective end users which in this case is the farmers. These applications
are not accessible to our farmers due to expense. Thus, our application bridges the gap
between state-of-the-art technologies and farmers.

# Features
• build_optimal_network algorithm,this algorithm uses back tracking to select the
most optimal model for prediction.
• train_network_to_convergence algorithm.
• Transfer of CNN model to TensorFlow lite to easily deploy pre-tranied model on
Android apps.
• Stand-alone application to overcome the disadvantages of the client server
architecture so that the mobile application works without internet
