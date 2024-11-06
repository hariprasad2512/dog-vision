# Dog-Vision

**Dog Vision** is a Deep Learning Multi-Class Classifier that identifies dog breeds from images. 
Using the power of transfer learning, the model is built on the **[MobileNetV3]** architecture, pre-trained on over 15 million images.
This allows the model to leverage existing patterns and features learned during its initial training. 

https://www.kaggle.com/c/dog-breed-identification/data

The **Dog Vision** model has been fine-tuned on a dataset of over 10,000 images spanning 120 dog breeds, enabling it to deliver highly accurate breed predictions.

## Key Features

- **120 Dog Breeds:** The model is capable of classifying dogs into 120 different breeds.
- **Transfer Learning:** Utilizes the [MobileNetV3] model from TensorFlow Hub, pre-trained on a large-scale image dataset.
- **Developed in Google Colab:** The training and fine-tuning process was conducted in Google Colab, making it accessible and scalable.

## Tools & Libraries Used

- **TensorFlow 2.0:** The core framework used for building, training, and evaluating the model.
- **TensorFlow Hub:** Used to integrate the pre-trained [MobileNetV3] model.
- **Matplotlib:** Employed for data visualization and plot generation throughout the model training and evaluation processes.

## Dataset

- The model is trained on a dataset of over **10,000 images** covering **120 dog breeds**.
- Data preprocessing involved resizing images to a uniform size suitable for MobileNetV3, augmenting images to improve model generalization, and splitting data into training, validation, and testing sets.

## Model Overview

- **Base Model:** MobileNetV3 (pre-trained on 15M+ images)
- **Fine-Tuning:** The model is fine-tuned on the dog breed dataset to adapt its knowledge specifically to dog breeds.
- **Input Size:** Images are resized to fit the input requirements of MobileNetV3.
- **Loss Function:** Categorical Crossentropy
- **Optimizer:** Adam

## Setup & Installation

 **Run the model in Google Colab:**

   Upload the project files to Google Colab and execute the provided `notebook.ipynb` file to see the model in action.


## Conclusion

Dog Vision leverages the power of transfer learning and deep learning to provide a reliable, efficient, and user-friendly tool for dog breed identification. Explore the world of dog breeds and enjoy seamless predictions using state-of-the-art AI.
