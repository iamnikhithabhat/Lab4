# **Lab4**
### Problem description
I have created a logistic regression model for fish species dataset. I have predicted the class to which the fish belongs using a set of training and test datasets.
The main aim of lab4 activity given to me is to launch my model in Heroku application.Hence I have kept my model simple to logistic regression.Although I tried models like decision tree,KNN and random forest,for the given training and test data,logistic regression model performed better.Hence I finalised this model.
### Description of the dataset
The dataset consists of dimensions and species name of 160 different fishes.The distribution is :
| Species |count |
| ---------- | ----- |
| Perch | 56 |
| Bream | 35 |
| Roach | 20 |
| Pike | 17 |
| Smelt | 14 |
| Parkki | 11 |
| Whitefish | 6 |

No of instances:160
Attribute information:
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 159 entries, 0 to 158
Data columns (total 7 columns):

Each instance has 7 values of a fish as mentioned below:
1.Weight in cm\
2.Vertical length in cm defined by Length1\
3.Diagonal length in cm defined by Length2\
4.Cross length in cm defined by Length3\
5.Height in cm\
6.Diagonal width in cm defined by Width\
7.Species to which the fish belongs\

### Prediction and accuracy
There are 7 fish breeds and our model is designed to make prediction of these species to which a test fish belongs.
Please find the accuracy score of logistic regression model:
Logistic regression:0.8333333333333334
Confusion matrix is given below:
<img width="284" alt="confusion matrix" src="https://user-images.githubusercontent.com/47333294/124164975-ed9c0a80-dabe-11eb-89af-06fdbfadb21f.PNG">

I haven't focused on accuracy of the model ,since my aim was to build a decent enough model to host it to Heroku and to ensure I make no mistakes in Flask and html files.

### Installations
This repository is public.Anyone can download in a .zip format or can be cloned using the link.
requirements.txt file is autogenerated by pip-compile.File should list all Python libraries that your notebooks depend on, and they will be installed using: 
pip install -r requirements.txt
