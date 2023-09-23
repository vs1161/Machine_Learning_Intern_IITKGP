# Objective of Intern

![objective](https://github.com/vs1161/Machine_Learning_Intern_IITKGP/assets/106301220/1d33e04b-f552-4169-9c58-bc7ea9619094)


# data description 

The appearance of atomic and formula datasets to understand the problem structure is shown below:
![data_description](https://github.com/vs1161/Machine_Learning_Intern_IITKGP/assets/106301220/9c7a05c9-5722-4a74-88c7-84ad9c0d09f7)

# Feature Engineering 

Performed feature engineering which utilizes the atomic data and formula dataset to generate a new final formula dataset which is named here as final_formula_df which will be used to train the models 

The sample of the generated final formula dataset and the methods used during feature engineering are presented below for visualization 
![final_formula_df](https://github.com/vs1161/Machine_Learning_Intern_IITKGP/assets/106301220/325aaa7c-85d8-437c-8b9d-94f774662cd3)

# Results 
The above-generated dataset has been tried on various ML models, and the obtained results are presented below:

RFC[1] is the model accuracy of the research paper which is being validated 
![various_models](https://github.com/vs1161/Machine_Learning_Intern_IITKGP/assets/106301220/6001963b-6b3c-42ad-97ca-7862c29f0abb)


The feature importance is generated from the random forest classifier model and has been validated the corresponding features shown, only features which has importance greater than 1.8% have been presented: 
![feature_importance](https://github.com/vs1161/Machine_Learning_Intern_IITKGP/assets/106301220/b1276de5-4f5e-454e-b41a-ae643f8ae2c9)


Below is the variation of K value in KNN and the number of estimators in AdaBoost with accuracy has been shown:
![knn_adaboost](https://github.com/vs1161/Machine_Learning_Intern_IITKGP/assets/106301220/0ff8ea5c-46c4-4981-99ca-dd6b253e23c0)


# ANN Classifier 

The same dataset has also been trained in the ANN model and effort has been made to increase its performance, The ANN model in the reviewed paper is implemented using keras and tensorflow while in this work Pytorch has been used. Initially, the hyperparameters have been kept the same as stated in the research paper, and then various experiments have been performed. 

# experiment - 1 

Based on initial parameters the model accuracy has been experimented on different split ration to observe the dependency of the split ratio of the dataset on model accuracy and all the trials made can be observed below:
![ann_timestamps_trial](https://github.com/vs1161/Machine_Learning_Intern_IITKGP/assets/106301220/95fc3ba2-2acd-4d31-89a7-6c51019458f1)

Also, the learning curve has also been tracked for each case to track the overfitting and underfitting of the model, It was observed that the model having two hidden layers was prone to overfit without dropout layer and without regularisation, one of the sample tracking is presented below:
![learningcurve](https://github.com/vs1161/Machine_Learning_Intern_IITKGP/assets/106301220/1932eccd-3d8d-4189-a4a1-1c510fbaed22)


# experiment - 2 
Now proceeding with the 80:10:10 split of data 
![experiment-2_des](https://github.com/vs1161/Machine_Learning_Intern_IITKGP/assets/106301220/4fa6c846-bbd9-4926-a263-78a5adb1905f)

Below is the performance metrics of the classifier:

![experiment2_metric](https://github.com/vs1161/Machine_Learning_Intern_IITKGP/assets/106301220/aeb16af1-25a3-4614-804d-9cefb6c1f3d7)

# experiment - 3
![experiment3](https://github.com/vs1161/Machine_Learning_Intern_IITKGP/assets/106301220/910f5865-a5a6-43cc-b068-95ed2f4895a4)


# experiment - 4
![experiment4](https://github.com/vs1161/Machine_Learning_Intern_IITKGP/assets/106301220/102adb3a-d6b1-485d-96b4-104091256936)


# Feature Recognition: Extracting Data From Material Project Database
![feature_recogni](https://github.com/vs1161/Machine_Learning_Intern_IITKGP/assets/106301220/518a1817-eeea-4841-ad97-a81f853c9c8a)

