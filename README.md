# Behaviour Prediction based on Handwriting using Machine Learning

The aim of this project is to develop a predictive model to reveal the personality traits of a person based on their handwriting. 
### The handwriting features taken into consideration are as follows: ###

1. Baseline

2. Word spacing

3. Pen pressure

These features indicate the **social** and **emotional behavioural traits** of a person. 

### Notable Libraries Used: ###

1. Computer Vision - cv2

2. Scientific Computing - scipy

3. Image processing - imutils

4. Plotting - matplotlib

### Steps: ###

1. Dataset: _CVL dataset_ which consist over 11K images of handwriting samples.

2. Manual Labelling: Based on research on Graphology, I manually labelled each handwriting sample with the features and later mapped it to the traits.

3. Feature vectors: Once the labelled dataset was ready, using imutils package's image processing functions, the feature vectors were calculated from the image.

4. Trait mapping: The feature vectors were then mapped to the human traits based on the manual labelling.

5. Model building: The obtained dataset was then fed to various machine learning models to test for performance and prediction accuracy.


