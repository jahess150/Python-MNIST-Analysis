# Python_MNIST_Analysis
## Joshua Hess

Hello! This repository is a project I did to learn more about computer vision and machine learning in general. To do this, I created four basic machine learning models for the MNIST handwritten digit dataset. The purpose of these models is to look at a given $28 \times 28$ pixel image of a handwritten digit and recognize which number it is from 0-9. For this notebook, I created models for the following ML algorithms:

1. Logistic Regression
2. Support Vector Machines (SVM)
3. Random Forest Classifier
4. Multilayer Perceptron Classifier

All models were implemented using Python and its `scikit-learn` library. All four models used `GridSearchCV` for hyperparameter tuning, and I included high-level explanations and mathematical deep-dives when explaining each model. My goal with this project was to finish with a stronger understanding of each model and how its used within the context of the MNIST data. 

In this repository, the file `classifying-handwritten-digits-with-python.ipynb` is the Jupyter Notebook containing the analysis and modeling of the MNIST data. For each model, I generated a submission CSV file for the Kaggle competition ![Digit Recognizer](https://www.kaggle.com/competitions/digit-recognizer/submissions), which is where I also got the MNIST data from. These submission files can be found in the `SubmissionFiles` folder. 

This project is licensed under the MIT license, so you are more than welcome to create your own copy and change the notebook as you see fit. If you have any questions or suggestions, feel free to reach out to me at jahess150@gmail.com.
