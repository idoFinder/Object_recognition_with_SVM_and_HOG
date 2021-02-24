# Object recognition using SVM and HOG

This was a project of the course: **"Learning, representation, and Computer Vision"** by Dr Aharon bar Hillel

The data used for this project is the [Caltech 101 dataset](http://www.vision.caltech.edu/Image_Datasets/Caltech101/)

General flow:
- Resize the raw images
- Applying HOG (Histogram of Oriented Gradients) on the raw_data using pre-defined Params, resulted in features vector
- Creating a "one-vs-rest" implementation for multi-class SVM classifier 
- Hyperparameters tunning
- Evaluation + plotting the "worst" predictions (meaning - the hardest-to-classify images)

