# MachineLearning_Practice
This repository contains ML models from low to highly complex models

### StudentGrade_Linear_model
Attribute Information:
There are all together 32 attributes, out of which we use following attribute to make our model. In this project we create the model and save it using Pickle package as .pickle file and while creating the model we re iterate creation 30 times in order to get the best accuracy. the accuracy achieved is 93%. There is a surprise twist in the end to decreaze the error in the score predicted. DO CHECK IT OUT.
14 studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
15 failures - number of past class failures (numeric: n if 1<=n<3, else 4)
30 absences - number of school absences (numeric: from 0 to 93)
31 G1 - first period grade (numeric: from 0 to 20)
31 G2 - second period grade (numeric: from 0 to 20)
32 G3 - final grade (numeric: from 0 to 20, output target)
< Model was created to predict G3 based on 5 attributes - studytime,failures,absences,G1,G2 >
