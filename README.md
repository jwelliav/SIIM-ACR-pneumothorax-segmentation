# SIIM-ACR-pneumothorax-segmentation

The code in this repository was for the following Kaggle competition - https://www.kaggle.com/c/siim-acr-pneumothorax-segmentation/overview
which required the participant to build a model capable of highlighting the portion of a lung that is collapsed in a chest X-ray. 
The problem is hence a segmentation task. We tried models based on the unet architecture with a pretrained resnet encoder. 
Our final model also included a classifier which checks whether the input image does indeed have pneumothorax or not before 
asking the segmentation model to outline the portion of the lung suffering from the problem. The code is written completely by me in pytorch. 
