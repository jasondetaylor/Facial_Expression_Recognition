# Facial Epression Recognition Project
## Introduction and Motivation
This project is a first dive into CNN's and their applications in learning image data. The project was inspired by current facial recognition software and the general growing prevalence of facial detection software in current tech advancements. A kaggle competition from 2013 was found that matched the intentions of this project and was used as a baseline to see how the models created in this notebook performed at this facial epxression recognition task.

## Modeling
### Methodology
As this was an exploratory notebook, 2 methods of modeling were tested:
1. Transfer learning using the VGG19 architecture trained on the ImageNet dataset.
2. Relatively shallow custom CNN's tranined on the facial expression dataset provided.

### Findings
The use of transfer learning model was found to be ill suited to making predictions on this data, however our CNN's perfomed reasonably well with our best model scoring 59% accuracy placing 13th out of the 56 entires in the kaggle competition.

## Data
Note that the data has not been added to this repo, to retireve the data please download the "icml_face_data.csv" file from the following URL: https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge

## Environment
Recreate the required environment for this notebook using the yaml file in anaconda prompt via code:
conda env create -f environment.yml