# Dynamic-Bounding-Boxes
Face Recognition using Pinterest data and Drawing dynamic bounding boxes
PART ONE
• DOMAIN: Face recognition
• CONTEXT: Company X intends to build a face identification model to recognise human faces.
• DATA DESCRIPTION: The dataset comprises of images and its mask where there is a human face.
• PROJECT OBJECTIVE: Face Aligned Face Dataset from Pinterest. This dataset contains 10,770 images for 100 people. All images are taken
from 'Pinterest' and aligned using dlib library.


PART TWO
• DOMAIN: State traffic department
• CONTEXT: City X’s traffic department wants to understand the traffic density on road during busy hours in order to efficiently program
their traffic lights.
• TASK: Create an automation using computer vision to impute dynamic bounding boxes to locate cars or vehicles on the road. It would
require for you to do some research on how to impute bounding boxes on video file. You can use video provided with this assignment or
any video of your choice which has moving cars to impute bounding boxes.
Refer to the screenshot from sample video below:
• TASK: In this problem, we use a pre-trained model trained on Face recognition to recognise similar faces. Here, we are particularly
interested in recognising whether two given faces are of the same person or not. Below are the steps involved in the project.
• Load the dataset and create the metadata.
• Check some samples of metadata.
• Load the pre-trained model and weights.
• Generate Embedding vectors for each face in the dataset.
• Build distance metrics for identifying the distance between two given images.
• Use PCA for dimensionality reduction.
• Build an SVM classifier to map each image to its right person.
• Predict using the SVM model.
