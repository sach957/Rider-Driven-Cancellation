# Rider-Driven-Cancellation
This code is a part of hackathon contest conducted by IIT-Guwahati.
This is real business problem given by Shadowfax.

The aim of this code is to predict rider driven cancellation.

PROBLEM OVERVIEW:-

The order gets allocated to a rider.
The rider accepts the order.
The rider goes to the pickup location.
The rider picks up the order.
The rider goes to the delivery location and delivers the order.
The rider also has the option to get the order cancelled before delivery by calling the client’s call centre. We would like to predict this kind of cancellation before it happens so that we can try and reassign the order to another rider before it gets cancelled.

PROBLEM STATEMENT:-

Given the order and rider details as described, create a model that can predict rider-driven cancellation in advance (i.e. before getting marked as cancelled or delivered)

APPROACH:-

The main part of this problem solving involvbes feature engineering and new feature building.
For making prediction I have used ensemble model (Xgboost Classifier).
The evaluation metric used is ROC-AUC.
ROC-AUC score of approx(80) is achieved on train-test split.

