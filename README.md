## **Objective**

The objective is to solve machine learning classification problem (predicting heart arrhythmia) in this case while applying various statistical methods using R.
The report is an output of R markdown containing all the code and the outcomes with comparison. The report contains the below:
* Exploratory Data Analysis
* Overview of the problem 
* Dataset description 
* Data cleaning
* Data visualization
* Feature engineering (PCA, Step forward feature selection)
* Various classification algorithms 
* Performance evaluation 
* Conclusion 


## **Problem**

Diagnosis of a heart arrhythmia involves measuring the heart activity for irregular heart beat using Electrocardiogram (ECG)  and then analysing the recorded data. These parameters coupled with patient information can then be used by doctors to identify arrhythmia and its category.

Some challenges in identifying arrhythmia are:

* Many of the current algorithms are rule based implementation but the cardio log’s classification is different and better.
* Impossible  for a doctor to identify minute steeps and irregularities due to the high number of parameters (i.e. > 270) involved.
* **90% of clinical alarms in intensive care units might be false**. This high percentage negatively impacts both patients and clinical staff. The alarm overload might also lead to desensitization and could result in true alarms being ignored.

Hence we aim to create a classification model which will draw conclusions from the cardio log's data as a gold standard and will distinguish between the presence and absence of cardiac arrhythmia and to classify it in one of the 16 groups from ECG data of new patients. This will help in achieving the below.

* Reducing false alarms which in turn helps clinical staff to focus on the attention required areas.
* Accurate detection to expedite patient's treatment.

## **Dataset**

The data has been captured as a part of study by H. Altay Guvenir and is available in [uci](http://archive.ics.uci.edu/ml/datasets/Arrhythmia) Machine Learning repository.
