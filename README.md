
## 👋 Hi! I'm Nazarii Kolesnikov. I am a Data Scientist

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nazarii-kolesnikov-84ba89357/?skipRedirect=true)
[![Viber](https://img.shields.io/badge/Viber-8B66A9?style=for-the-badge&logo=viber&logoColor=white)](tel:380678333023)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:380678333023)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nazarijkolesnikov053@gmail.com)
[![Blogger](https://img.shields.io/badge/Blogger-FF5722?style=for-the-badge&logo=blogger&logoColor=white)](https://www.blogger.com/blog/posts/1472892418534435877?hl=uk&tab=jj)

## 💻 Projects I'm currently working on

# Neural Networks Training (Wine Collection)

## 📝 Description

This project is dedicated to developing a `classification model` for determining wine varieties based on their chemical characteristics. The work demonstrates the application of data preprocessing methods, statistical analysis, visualization, and the fundamentals of working with artificial neural networks. As part of this work, an analysis is conducted on the `wine_collection.csv` dataset, which contains the results of chemical analyses of various wine varieties. The project covers the full data processing cycle: from preprocessing (data cleaning and removal of uninformative features, such as `Color` and `No.`) to exploratory data analysis (`EDA`) using class distribution visualizations and correlation matrices. The main task is to prepare the data for training an artificial neural network that will predict the target variable `Desired` (wine class) based on its properties (`e.g.`, alcohol content and flavonoid content).

⚙️ Project: [link](https://github.com/nazariikolesnikov/neural-networks-wine-collection)

## 🤖 Technologies

![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000.svg?style=for-the-badge&logo=keras&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

## 📊 Visualizations

<img width="5647" height="3107" alt="A/B Testing, Testing a Statistical Hypothesist" src="https://github.com/nazariikolesnikov/neural-networks-wine-collection/blob/main/Classification%20of%20Wines%20(Alcohol%20vs%20Flavanoids).png" />

<img width="5647" height="3107" alt="A/B Testing, Testing a Statistical Hypothesis" src="https://github.com/nazariikolesnikov/neural-networks-wine-collection/blob/main/Correlation%20Matrix%20of%20Wine%20Collection%20Characteristics.png" />

# Time Series Forecasting (Holt-Winters, ARIMA, XGBoost, Random Forest) (Practical Training)

## 🤖 Technologies

![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)

## 📝 Description

This project focuses on time series analysis and forecasting future sales volumes based on the company’s historical data. The main goal is to build reliable predictive models to optimize business processes. The `rohitsahoo-sales-forecasting.csv` dataset is used for the analysis. integrated key tools for data processing (`Pandas`, `NumPy`, `Matplotlib`) and building time-series forecasting models (`ARIMA`, `Holt-Winters`, `XGBoost`, `Random Forest`).  The code reads the file into a DataFrame and checks its structure, which consists of `9,800` rows and `18` columns. The Order Date column is converted from plain text to the datetime format for proper time series processing. The data is grouped by month (using `pd.Grouper`), after which the total sales (`Sales`) for each monthly period are calculated.

⚙️ Project: [link](https://github.com/nazariikolesnikov/time-series-forcasting-arima-holt-winters-xgboost-random-forest)

## 📊 Visualizations
<img width="5647" height="3107" alt="Time Series Forcasting (ARIMA)" src="https://github.com/nazariikolesnikov/time-series-forcasting-holt-winters-arima/blob/main/Comprehensive%20Sales%20Forecasting%20(ARIMA%2C%20Holt-Winters%2C%20XGBoost%2C%20Random%20Forest).png" />

# Decision Tree Algorithm with Machine Learning (Practical Training)

## 📝 Description

Cleaning the datasets, converting categorical text variables to numerical formats using `LabelEncoder`, and scaling features using `StandardScaler`. Splitting the data into training and test sets (train_test_split). Building and training two classifiers: Logistic Regression and Decision Tree. Comprehensive analysis of model quality using key statistical metrics: `Accuracy Score`, `F1-score`, `Confusion Matrix`, and a detailed `Classification Report`. Plotting a `ROC` (`Receiver Operating Characteristic`) curve using the matplotlib library to visually compare the algorithms’ ability to distinguish between classes. A visual and statistical comparison revealed that, for the selected dataset, the logistic regression model demonstrated better generalization ability than the decision tree. The area under the curve (`AUC`) for logistic regression was `0.69`, while for the decision tree it was `0.60`.

⚙️ Project: [link](https://github.com/nazariikolesnikov/decision-tree-algorithm-with-machine-learning)

## 🤖 Technologies

![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

## 📊 Visualizations

<img width="5647" height="3107" alt="A/B Testing, Testing a Statistical Hypothesist" src="https://github.com/nazariikolesnikov/decision-tree-algorithm-with-machine-learning/blob/main/ROC-curve.png" />

# A/B Testing, Testing a Statistical Hypothesis (Practical Training)

## 🤖 Technologies

![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
![Pandas](https://img.shields.io/badge/Pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)

⚙️ Project: [link](https://github.com/nazariikolesnikov/time-series-forcasting-arima-holt-winters-xgboost-random-forest)

## 📝 Description

This project is a custom toolkit for conducting `A/B testing`, testing statistical hypotheses, and performing in-depth data analysis using `Python`. The project demonstrates a fundamental understanding of mathematical statistics, as key statistical functions are implemented from scratch without using high-level statistical abstractions. Accurate calculation of parameters, `Z`-scores, and two-tailed `p-values` for comparing two samples. Development of scripts for simulating random events using the `random` module for the empirical validation of statistical hypotheses on large samples (for example, `1,000` coin-flip iterations). Construction of visual probability density plots for the standard normal distribution using the formula.

## 📊 Visualizations

<img width="5647" height="3107" alt="A/B Testing, Testing a Statistical Hypothesist" src="https://github.com/nazariikolesnikov/a-b-testing-practical-training/blob/main/AB%20Testing%20Results%20200%20sucesses%20versus%20180%20successes%20(N%20%3D%201000).png" />

# Logistic and Linear Regression with TensorFlow (Practical Training)

## 📝 Description

Building a model to predict continuous values based on generated data with random noise. Parameter optimization (`weights` and `bias`) is performed using gradient descent, and model quality is evaluated using the root mean square (`RMS`) error and `Pearson’s coefficient of determination`. : Solving a binary classification problem for two generated data clusters. The project involves calculating the loss function (cross-entropy), finding the optimal decision boundary, and evaluating the model’s classification accuracy. Creating informative and visually appealing graphs to display data distribution, trend lines, and classification boundaries, which allows for a clear interpretation of the algorithms’ results.

⚙️ Project: [link](https://github.com/nazariikolesnikov/time-series-forcasting-arima-holt-winters-xgboost-random-forest)

## 🤖 Technologies

![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000.svg?style=for-the-badge&logo=keras&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

## 📊 Visualizations

<img width="5647" height="3107" alt="A/B Testing, Testing a Statistical Hypothesist" src="https://github.com/nazariikolesnikov/logistic-and-linear-regression-with-tensorflow/blob/main/Linear%20Regression%20Model%2C%20y%20%3D%208.5x%20-%203.5%20%2B%20N%20(0%2C%200.5).png" />

<img width="5647" height="3107" alt="A/B Testing, Testing a Statistical Hypothesis" src="https://github.com/nazariikolesnikov/logistic-and-linear-regression-with-tensorflow/blob/main/Logistic%20Regression%20Model.png" />

# K-Nearest Neighbors Algorithm (Practical Training)

## ⚙️🤖 Technologies 

![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

⚙️ Project: [link](https://github.com/nazariikolesnikov/time-series-forcasting-arima-holt-winters-xgboost-random-forest)

## 📝 Description

Discussion of the wine classification problem. Training and test sets. Key parameters of the `train_test_split` procedure. Standardization. The `KNeighborsClassifier` procedure and its parameters. Confusion matrix and accuracy.
Determining the optimal number of nearest neighbors.

## 📊 Visualizations

<img width="5647" height="3107" alt="K-Nearest Neighbors Algorithm" src="https://github.com/nazariikolesnikov/k-nearest-neighbors-algorithm-practical-training/blob/main/Error%20rate%20for%20different%20values%20of%20K.png" />

# Data Analysis Practice with Polars (Python) (Practical Training)

## 🤖 Technologies

![Polars](https://img.shields.io/badge/polars-0075ff?style=for-the-badge&logo=polars&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

⚙️ Project: [link](https://github.com/nazariikolesnikov/time-series-forcasting-arima-holt-winters-xgboost-random-forest)

## 📊 Visualizations

<img width="5647" height="3107" alt="A/B Testing, Testing a Statistical Hypothesist" src="https://github.com/nazariikolesnikov/data-analysis-with-polars-python-practice/blob/main/Average%20number%20of%20downloads%20by%20platform%20Downloded%20vs.%20Uploaded%20Data.png" />
