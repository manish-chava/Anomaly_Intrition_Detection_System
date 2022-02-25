# Intrution-detection-system-IDS-
Emerging security threats and attacks like unauthenticated network penetration, policy breaches, traffic flooding, and more have increasingly become common across global companies, leading them to substantial revenue losses. Therefore it is the high time for companies to make use of
an highly dependable Intrusion Detection System(IDS). An Intrusion Detection System (IDS) is a system that monitors network traffic for suspicious activity and issues alerts when such activity is discovered. This project demonstrates the working of an intrusion detection system software that scans the network for any malicious activity. Intrusion detection system uses the data to create risk assessment reports, and identify highly advanced threats before they wreak the system

This project Involves two modules. In the first module the dataset is used to develop a network based anomaly intrusion detection model with machine learning for predicting any forceable attacks in the network. Through the model we will be able to predict if there is a potential attack in the network and if so the model will be capable of predicting the kind of attack possible. The model will be trained on supervised machine learning algorithms like Logistic regression and random forest classifier. The output of these will be compared with k nearest neighbours and XGboost algorithms and is investigated if the performance of the model can be increased. The model will also be tested on deep learning and will be ivestigated if deep learning has an edge over the previous algorithms.

In the second module an Intrusion detection software is developed.This software is capable of collecting the network intrusion detection system logs. The incoming network data is stored in the database and used for data analysis for studying areas like frequency of attacks, login failures and guest login. An interactive dashboard is embedded into the software that shows the visualisations of the details of the network traffic. For developing the software the flask framework is used to Create webpages in python.

Output:
(i) Network attack prediction by machine learning algorithms.
(ii) Comparision between the algorithms based on performance metrics and cross validation score.
(iii) Software implementation of the IDS showing data of previous network traffic along with an interactive dashboard showcasing visualisations of the network data.
