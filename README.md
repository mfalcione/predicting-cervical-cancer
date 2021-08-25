# Predicting Cervical Cancer Using Machine Learning
Cervical cancer is one of the most common causes of death from cancer in the world and especially in developing countries. The objective of this project is to understand medical history information can be used to predict a cervical cancer diagnosis.

This is useful because in areas where resources are scarce, this will allow diagnostic resources to be allocated to women at high risk. The dataset used in this study was obtained from 856 patients in Hospital Universitario de Caracas in Caracas, Venezuela. Following data post-processing, methods include t-SNE visualization, tree-based and univariate feature selection, and neural network, random forest, and XGBoost classification. t-SNE visualization showed no discernable patterns or splits in the data for any of the screening tests or the class target value, meaning there are likely multiple factors needed to make an accurate prediction of the target value. The random forest, XGBoost, and neural network classification methods all resulted in similar true negative values while the XGBoost method had the highest true positive value.

The true negative rate was chosen as the primary evaluation metric because Type II error, or predicting that an individual will not be diagnosed with cervical cancer when in fact they will, is far more dangerous than its Type I counterpart. In the future, collecting data on a wider range of patients would help generalize results to a larger population. Building models on subsets of the data would also be useful so that it can be applied to individuals for whom some screening options are not available. 

### Project Files
- **project.ipynb:** this is the data processing and results notebook. 
- **requirements.txt:** contains all the required python packages to streamline installation.

### Install Project Dependecies
The project is dependent on the following python packages:

```
scikit-learn==0.24.1
xgboost==0.90
matplotlib==3.3.4
seaborn==0.11.1
numpy==1.20.0
pandas==1.2.1
```

Alternatively one can install all the required packages by running the pip command below.
* `pip install -r requirements.txt`

### Runing the Code

- Refer to [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) or [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/index.html#) documentation for instructions on running the code and setting up the notebook.
