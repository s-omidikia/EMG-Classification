# EMG-Classification
Machine Learning for detection of change in the ankle joint angle based on sEMG signals. 

* In this experiment, I would like to compare the performance of some Machine Learning models including Logistic regression and Naïve Bayes in a classification problem. Given a dataset of sEMG(Surface ElectroMyography) signal for three muscles named TA(Tibialis Anterior), GM(Gastrocnemius Medialis), and GL(Gastrocnemius Lateralis), the goal is to classify the angle of ankle joint into two classes of fixed(0) or changing(1). The location of electrodes to measure the sEMG signal and the ankle joint angle are shown in the figure below.  

![image.PNG](attachment:image.PNG)

* For each three muscles, two features called FR(Frequency Ratio) and SSR(Slopes Sign Changes) are extracted from their sEMG signal so totally there are 6 features for every sample from the entire signal. 
* The implementation for each algorithm is both by hand and with the scikit-learn library.


