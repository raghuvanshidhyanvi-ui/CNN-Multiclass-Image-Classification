\# CNN Multiclass Image Classification



\## Overview



This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images from the CIFAR-10 dataset into 10 categories.



The project covers dataset loading, CNN architecture design, model training, and evaluation on test data.



\## Dataset



The CIFAR-10 dataset contains 60,000 color images of size 32 × 32 pixels across 10 classes.



The classes are:



\- Airplane

\- Automobile

\- Bird

\- Cat

\- Deer

\- Dog

\- Frog

\- Horse

\- Ship

\- Truck



The dataset contains 50,000 training images and 10,000 test images.



\## Technologies Used



\- Python

\- PyTorch

\- Torchvision

\- Jupyter Notebook



\## Model Architecture



The CNN consists of:



\- Three convolutional layers

\- ReLU activation functions

\- Max pooling layers

\- Fully connected layers

\- An output layer with 10 class scores



\## Workflow



1\. Load the CIFAR-10 dataset.

2\. Prepare training and testing data loaders.

3\. Build the CNN architecture.

4\. Train the model using backpropagation and an optimizer.

5\. Evaluate predictions on the test dataset.

6\. Calculate classification accuracy.



\## Project Structure



```text

CNN-Multiclass-Image-Classification/

├── CNN\_for\_CIFAR10.ipynb

├── README.md

└── .gitignore

```



\## How to Run



1\. Clone this repository:



&#x20;  ```bash

&#x20;  git clone https://github.com/raghuvanshidhyanvi-ui/CNN-Multiclass-Image-Classification.git

&#x20;  ```



2\. Install the dependencies:



&#x20;  ```bash

&#x20;  pip install torch torchvision jupyter

&#x20;  ```



3\. Open the project notebook:



&#x20;  ```bash

&#x20;  jupyter notebook CNN\_for\_CIFAR10.ipynb

&#x20;  ```



4\. Run the notebook cells in order.



\## Results



\- Number of classes: 10

\- Number of training epochs: 10

\- Test accuracy: 74.%



\## Learning Reference



This project was developed as part of my deep learning learning journey, with guidance from Apna College educational material.



\## Future Improvements



\- Visualize training and validation loss.

\- Generate a confusion matrix.

\- Experiment with data augmentation.

\- Improve model accuracy and generalization.





