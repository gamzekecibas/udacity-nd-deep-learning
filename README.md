# udacity-nd-deep-learning
Project &amp; practices from [Udacity Deep Learning Nanodegree](https://www.udacity.com/course/deep-learning-nanodegree--nd101)  

- **PRE NOTEBOOKS:**  
Practices during the course are here.  
    - [001- Gradient Descent](https://github.com/gamzekecibas/udacity-nd-deep-learning/blob/main/pre-notebooks/001-GradientDescent.ipynb)   
    - [002- StudentAdmissions.ipynb](https://github.com/gamzekecibas/udacity-nd-deep-learning/blob/main/pre-notebooks/002-StudentAdmissions.ipynb): It includes one hot encoding and data scaling processes.    
- **PROJECTS**:  
Main projects in the course are here.  
  - [01-neural-network](https://github.com/gamzekecibas/udacity-nd-deep-learning/tree/main/PROJECTS/01-neural-network)  
    Deep neural network (DNN) is studied using [bike sharing demand](https://www.kaggle.com/c/bike-sharing-demand) in the project. The dataset is presented below:
<p align="center">
  <img width="400" height="300" src="https://user-images.githubusercontent.com/60810553/160198599-e4632451-7e84-4853-8ba8-6db120d4853f.png">
</p>

   A *NeuralNetwork* function is created to build the model. The function is in ***my_answers.py***. In the method, there are fundamental layers of feedword and            backward passes. End of hidden layers, weights are updated using derivatives of error that is equal to difference between actual value and prediction. Activation        function of each layer is *sigmoid*. Hyperparameters of the trained model are:  
            * **epochs** = 4800  
            * **learning rate** = 0.35  
            * **hidden nodes** = 20  
            * **# output** = 1  
    Trained model can make predictions as below:  
<p align="center">
  <img width="500" height="300" src="https://user-images.githubusercontent.com/60810553/160200715-f1aef09e-cc4a-4023-ac19-fb49dbc17bf2.png">
</p>

  - [02-cnn-landmark](https://github.com/gamzekecibas/udacity-nd-deep-learning/tree/main/PROJECTS/02-cnn-landmark)  
> *The model is run on GPU.*  
   
   Convolutional Neural Network (CNN) is studied using [landmarks-dataset](https://www.kaggle.com/datasets/google/google-landmarks-dataset). It may be specialized for the project because it includes data augmentation process. Samples from after data loader:
<p align="center">
  <img width="600" height="250" src="https://user-images.githubusercontent.com/60810553/160202546-792f6140-5da4-4691-a345-83f3e7c25867.png">
</p>

   The CNN is built by **three Conv2d layers**, **MaxPool2d**, **two fully connected layers**, **view (flatten layer)** & **batch_norm2d and batch_norm1d**. Activation function is selected as **leaky ReLU** with -0.2 slope. **Dropout** is preferred as regularizer with 0.3 probability. Stochastic Gradient Descent (SGD) is used as optimizer where learning rate is 1e-2. Loss is calculated by cross entropy. Initially, **epochs** is equal to 20, however it is too low to predict successfully. Therefore, **epochs** is adjusted as 100. 
<p align="center">
    <b>You can check porject report for detais...</b>
</p>

  - [03-rnn-script](https://github.com/gamzekecibas/udacity-nd-deep-learning/tree/main/PROJECTS/03-rnn-script)  
  - [04-gan-generate-face](https://github.com/gamzekecibas/udacity-nd-deep-learning/tree/main/PROJECTS/04-gan-generate-face)  
  - [05-aws-model-deployment](https://github.com/gamzekecibas/udacity-nd-deep-learning/tree/main/PROJECTS/05-aws-model-deployment)
