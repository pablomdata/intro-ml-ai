# Intro to Machine Learning and AI


Course materials adapted from [Microsoft's course](https://github.com/microsoft/ML-For-Beginners).


| Lesson Number |                             Topic                              |                   Lesson Grouping                   | Learning Objectives                                                                                                             | 
| :-----------: | :------------------------------------------------------------: | :-------------------------------------------------: | ------------------------------------------------------------------------------------------------------------------------------- | 
|      01       |                Introduction to machine learning                |      [Introduction](1-Introduction/README.md)       | Learn the basic concepts behind machine learning                                                                                | 
|      02       |                Techniques for machine learning                 |      [Introduction](1-Introduction/README.md)       | What techniques do ML researchers use to build ML models?                                                                       | 
|      03       |                   Introduction to regression                   |        [Regression](2-Regression/README.md)         | Get started with Python and Scikit-learn for regression models                                                                  | 
|      04       |                North American pumpkin prices 🎃                |        [Regression](2-Regression/README.md)         | Visualize and clean data in preparation for ML                                                                                  | 
|      05       |                North American pumpkin prices 🎃                |        [Regression](2-Regression/README.md)         | Build linear and polynomial regression models                                                                                   | 
|      06       |                North American pumpkin prices 🎃                |        [Regression](2-Regression/README.md)         | Build a logistic regression model                                                                                               | 
|      07       |                          A Web App 🔌                          |           [Web App](3-Web-App/README.md)            | Build a web app to use your trained model                                                                                       | 
|      08       |                 Introduction to classification                 |    [Classification](4-Classification/README.md)     | Clean, prep, and visualize your data; introduction to classification                                                            | 
|      09       |             Delicious Asian and Indian cuisines 🍜             |    [Classification](4-Classification/README.md)     | Introduction to classifiers                                                                                                     | 
|      10       |             Delicious Asian and Indian cuisines 🍜             |    [Classification](4-Classification/README.md)     | More classifiers                                                                                                                | 
|      11       |             Delicious Asian and Indian cuisines 🍜             |    [Classification](4-Classification/README.md)     | Build a recommender web app using your model                                                                                    | 
|      12       |                   Introduction to clustering                   |        [Clustering](5-Clustering/README.md)         | Clean, prep, and visualize your data; Introduction to clustering                                                                | 
|      13       |              Exploring Nigerian Musical Tastes 🎧              |        [Clustering](5-Clustering/README.md)         | Explore the K-Means clustering method                                                                                           | 
|      14       |        Introduction to natural language processing ☕️         |   [Natural language processing](6-NLP/README.md)    | Learn the basics about NLP by building a simple bot                                                                             |  
|      15       |                      Common NLP Tasks ☕️                      |   [Natural language processing](6-NLP/README.md)    | Deepen your NLP knowledge by understanding common tasks required when dealing with language structures                          |  
|      16       |             Translation and sentiment analysis ♥️              |   [Natural language processing](6-NLP/README.md)    | Translation and sentiment analysis with Jane Austen                                                                             | 
|      17       |                  Romantic hotels of Europe ♥️                  |   [Natural language processing](6-NLP/README.md)    | Sentiment analysis with hotel reviews 1                                                                                         | 
|      18       |                  Romantic hotels of Europe ♥️                  |   [Natural language processing](6-NLP/README.md)    | Sentiment analysis with hotel reviews 2                                                                                         | 
|      19       |                  Neural Networks and Deep Learning                  |   [Neural Networks](7-Neural-Networks/README.md)    | Introduction to Neural Networks and Deep Learning | 
|      20       |                  Anomaly Detection and Autoencoders                  |   [Neural Networks](8-Anomaly-Detection/README.md)    | Neural networks for fraud detection and image reconstruction | 
|      21       |                  Using Pretrained Deep Learning Models                 |   [Neural Networks](9-Pretrained-Deep-Learning-Models/README.md)    | Introduction to Neural Networks and Deep Learning | 

## Setup 

- You need Python 3.11 installed in your system.
- Clone the repository:
```git clone https://github.com/pablomdata/intro-ml-ai```
- Go to the folder in the command prompt. Once there, use the command
```python -m venv env```
to create a virtual environment.
- Activate the virtual environment:
	- In Windows: `env\Scripts\activate.bat`
	- In Mac/Linux: `source env/scripts/activate`
You should see an `(env)` next to your prompt.
- Install dependencies:
```pip install -r requirements.txt```
- Launch Jupyter notebook:
```jupyter notebook```