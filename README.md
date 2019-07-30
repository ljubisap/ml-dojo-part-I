## Machine Learning Dojo - Part I
### Introduction
Welcome Machine Learning Dojo - Part I. We have a lot of work ahead of us to do but we are going to start small. 
For this dojo you do not need to have any previous experience with machine learning nor Python. 
Dojo duration is planned to be around three hours depending on how fast you complete your tasks.

### Prerequisites 
Some programming skills in any language. 

### Environment setup
In order to start please follow these steps: 
 * Navigate to your home folder
 	``` 
 	cd ~
	``` 
 * Download and install Anaconda from here (install version 3.7):
	https://www.anaconda.com/distribution/. You can also do it from command line in a following way:
	``` 
	curl -o Anaconda2-4.4.0-MacOSX-x86_64.sh https://repo.continuum.io/archive/Anaconda2-2019.07-MacOSX-x86_64.sh
	``` 
 * Start installation and follow instructions on the screen. Accept all default options offered during installation:
    ``` 
	bash Anaconda2-2019.07-MacOSX-x86_64.sh
	``` 
 * Update environment variables:
    ``` 
    source ~/.bash_profile
	```  
### Install Tensorflow
 * Install package directly from Google repository:
    ```
    pip install https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.3.0-py2-none-any.whl
    ```
 * In case you do not have pip (you should though) this is how you can install it:
    ```
    sudo easy_install pip
    ```
 * Type right there in the console
   ```
   python
   ```
 * Python console will open. Enter these two lines of code:
    ```  
    import tensorflow as tf
    tf.__version__
    ```
 * The result should be:
    ```
    '1.3.0'
    ```
### Starting Jupyter notebook 	
 * Navigate to folder where you want to checkout Github project for further fork
 * Checkout required Github repository from [here](https://github.com/ljubisap/ml-dojo-part-I).
    ``` 
    git clone https://github.com/ljubisap/ml-dojo-part-I.git
	```  
 * Navigate into newly created folder
 	``` 
 	cd ml-dojo-part-I
	``` 
 * Execute Jupyter with following commands
 	``` 
 	export BROWSER=open
 	jupyter notebook Machine\ Learning\ Dojo\ -\ Part\ I.ipynb
	```   
	Note: Since we are going to use some larger photos, you might need to start Notebook in a following way:
 	``` 
 	jupyter notebook --NotebookApp.iopub_data_rate_limit=10000000000  
    ```
    and then to select Notebook file you want. This tutorial has two of them:
     * Do it yourself.ipynb
     * Machine Learning Dojo - Part I.ipynb
    
    by clicking on a file name, appropriate Notebook will be opened.  
     	  
### Further readings and references
 * [Scikit Learn website](http://scikit-learn.org/)
 * [Pandas website](http://pandas.pydata.org/)
 * [Scipy website](https://www.scipy.org/)
 * [Numpy website](http://www.numpy.org/)
 * [Matplotlib website](http://matplotlib.org/)
 * [Titanic dataset on Kaggle](https://www.kaggle.com/c/titanic)
 * [House prices dataset on Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
 * [Hands-On Machine Learning with Scikit-Learn and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems](http://shop.oreilly.com/product/0636920052289.do)
 * [Introduction to Data Science - Laura Igual and Santi Seguí](http://www.springer.com/de/book/9783319500164)
 * [Code academy Python course](https://www.codecademy.com/learn/python)
