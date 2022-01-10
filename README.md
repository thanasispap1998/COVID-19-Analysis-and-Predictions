# COVID-19-Analysis-and-Predictions

This project aims to show some graphs and information concerning COVID-19 as well as predict two different things. The first one is if a patient of COVID-19 will eventually die from the disease, by using his medical and personal history, and the second is what possible disease a patient has based on his symptoms. (co-authored by Fivos Tzavellos)

First of all, all files mentioned below, except the report of course, must be placed in the same folder for the notebooks to properly work. In the GitHub repository they are separated in different folders only for the purposes of clarification and order.

This GitHub repository contains all the Jupyter Notebooks and any additional necessary files for this project to work. More specifically it contains:

1) a folder named "Notebooks" containing the "Disease-Symptoms-Predictions" and "Graphs and Predictions - COVID 19 Patients" notebooks

2) a folder named "Datasets" containing the two datasets used for both notebooks

3) a folder named "Report" containing the report of this project

Here is a quick summary of the notebooks:

1) Disease-Symptoms-Predictions: In this notebook we are using the "Training" dataset which consists of many diseases and the symptoms they cause to patients. Through some data cleaning and processing we are able to use this information and feed it into many regression and classification models. Our goal is to connect every symptom with eevry disease and be able to predict what disease a patient probably has based on his symptoms. After training and testing the accuracy of every algorithm we use a "chat-bot" to test all the algorithms. The chat-bot asks questions involving the symptoms the patient has and after all questions are correctly answered it shows the predictions of each regression and classification algorithm that we trained. Of course not all algorithms performed the same, which is why some of them produce completely different results and predict a different disease than most of the others

2) Graphs and Predictions - COVID 19 Patients: On the other hand this notebook focuses solely on COVID-19. It starts of by showing a lot of graphs containing information on the disease but grouped by with specific details such as age, sex and other personal or medical information, showcasing how some graphs are different than others when comparing different age groups or different underlying diseases. However, after all the graphs we try to make predictions once again using only classification algorithms, only this time it is about if a patient will live or unfortunately die from the disease. By answering some questions about personal and medical information through another chat-bot, the different models show us their predictions, only this time all models have equal and very high accuracies.

And here is a quick summary of the datasets:

1) covid: The dataset contains the information of patients of COVID-19. More specifically it contains personal information such as age and sex, when they were infected, when they got well or died, as well as other medical information such as underlying diseases.

2) training: The dataset consists of many diseases and the symptoms caused by them to patients.

Feel free to experiment with any algorithm, any process or even use totally different datasets from what I used!
