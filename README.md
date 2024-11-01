# Machine learning Practices examples by Santiago Hernández Machine Learning Course in Udemy

All the examples that I developed based on the Udemy course about Machine Learning
by Santiago Hernández [Course link](https://www.udemy.com/course/machine-learning-desde-cero/) 

## Exercises

### 1. Lineal Regression:
- Predict segurity issue cost from random generated data.

### 2. Logistic Regression:
- Predict if an email must be classified as SPAM or HAM.

### 3. Data Manipulation:
- Process of data analysis, dataset partitioning and data cleaning.

    * **Data visualization-analysis**: Learn the data and select the best attributes for a better training process. 
    * **Dataset partitioning**: Split the dataset on 3 sub-datasets (training, validation, test)
    to get the necessary data to test and improve our model.
    * **Data cleaning**: Best techniques to clean null values, transform categoric values into
    numeric values and scaling numeric values.
    * **Transforms & Pipelines**: The creation of personalizated transforms and
    aplication of pipelines to reuse code and make more efficient our prepocessing phase. 
    * **Model evaluation**: Evaluate de accuracy of our model through diverse numeric and
    graphic methods.

### 4. SVM
- Suport Vector Machine algorithm applied to the dataset *Benigns and Malicious URLs*, the algorithm has 3 sub-algorithms:

    * **Soft Margin Classification**
    * **Polinomial Regression Kernel**
    * **Gaussian Kernel**

### 5. Desicion Trees & Random Forests
- The algorithm of decision trees applied to the *Android Malware* dataset and 
we can compare de difference between fit a unique decision tree model or apply
the random forest technique.


## Path distribution

    ├── DataVisualization
    │   └── 01-Visualizacion-ConjuntoDatos.ipynb
    │   └── 02-DivisionConjuntoDatos.ipynb
    │   └── 03-Preprocesamiento-LimpiezaDatos.ipynb
    │   └── 04-PipelinesTransformadores.ipynb
    │   └── 05-EvaluarResultados.ipynb
    |
    ├── RegresionLogistica
    │   └── RegresionLogistica-DeteccionSpam.ipynb
    |
    ├── RegresionLineal
    │   └── RegresionLineal-CosteIncidenteSeguridad.ipynb
    |
    ├── SVM
    │   └── SupportVectorMachine.ipynb
    |
    ├── ArbolesDecision
    │   └── 01-ArbolesDecision.ipynb
    │   └── 02-ArbolesDecision-RandomForests.ipynb
    
