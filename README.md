# Image Classifier
This project aims to develop a model to classify images of cats into different breeds using transfer learning and deep learning techniques. 

## Methodology

- Collected a dataset of 50 images across 5 cat breeds (Abyssinian, Tonkinese, Balinese, Siamese, Persian) from online sources.
- Pre-processed the images by resizing to 224x224x3 to match the input dimensions of the MobileNetV2 model. 
- Split the data into training and test sets with a 90-10 split. 
- Used the pre-trained MobileNetV2 model and retrained the final layer for the task of cat breed classification.
- Trained the model for 10 epochs.

## Results

- Achieved an accuracy of 80% on the test set after 10 epochs of training. 
- The model was able to correctly classify 4 out of 5 test images into the correct breed.
- Visualized the change in accuracy over the 10 training epochs.
