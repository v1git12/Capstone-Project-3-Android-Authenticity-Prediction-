# Capstone-Project-3-Android-Authenticity-Prediction-
Android Authenticity Prediction is a machine learning problem that aims to predict whether an Android application (app) is authentic or not
![image](https://user-images.githubusercontent.com/66788381/226249404-5cb4c47f-bc73-44ab-afca-a084616fd1e5.png)
## INTRODUCTION
The project Android Authenticity Prediction (AAP) system uses machine learning techniques to classify applications as authentic or malicious based on a set of application features extracted from static analysis of the application code. The first Android smartphone was launched in September 2008, and shortly thereafter, smartphones powered by the new open-source operating system were everywhere. In 2021, almost 12 new enhanced versions of Android were released, and it is the most widely used mobile operating system in the world, with an 84% share of the global smartphone market. With this level of adoption coupled with the open-source nature of Android applications, security attacks are becoming more and more ubiquitous and seriously threaten the integrity of Android applications. Statistics show that more than 50 million malware and potentially unwanted applications have been identified for Android.

The Android Authenticity Prediction ML model is based on supervised machine learning techniques. It is trained using a large dataset of Android applications, both malicious and benign. The model is then tested on a separate dataset to evaluate its performance. The performance of the model is measured using metrics such as precision, recall, and accuracy. One of the key advantages of the Android Authenticity Prediction ML model is that it is highly accurate in detecting malicious applications. The model can accurately detect up to 78% of malicious applications with a low false positive rate. This makes it an effective tool for protecting Android users from malicious applications. Another advantage of the model is that it is scalable and can be easily integrated into existing mobile security solutions. The model can be deployed on mobile devices or on servers to detect malicious applications in real-time. This makes it an ideal solution for mobile security providers, app stores, and other organizations that need to protect their users from malicious applications. However, there are also some challenges that need to be addressed when using the Android Authenticity Prediction ML model. One of the challenges is the need for a large dataset of Android applications for training and testing the model. This requires a significant amount of resources and expertise to collect and analyze the data.


## PROBLEM STATEMENT
The problem of Android Authenticity Prediction is to develop a machine learning model that can accurately predict whether an Android application (app) is authentic or not. With the increase in the number of mobile apps, the risk of downloading malicious apps has also increased. Malicious apps can steal sensitive user data, perform unwanted actions, and damage the user's device. Therefore, it is essential to develop a model that can accurately predict the authenticity of Android apps and help users make informed decisions about which apps to download and install on their devices. The challenge is to identify the relevant features that can distinguish between authentic and malicious apps and to train a classification model that can generalize well to new, unseen apps. Additionally, the model should be able to handle the large and dynamic nature of the mobile app ecosystem, where new apps are constantly being developed and released.


## INSIGHTS FOUND AFTER THE ANALYSIS 
![image](https://user-images.githubusercontent.com/120029190/226265310-c778cef7-0241-436e-ad31-22e56df14a33.png)
![image](https://user-images.githubusercontent.com/120029190/226265434-a3b9561b-fc67-4d8e-8d10-83b49e223295.png)
![image](https://user-images.githubusercontent.com/120029190/226265033-75a3b628-d087-452b-9f43-10476b99c014.png)
![image](https://user-images.githubusercontent.com/120029190/226265101-70e5c440-5822-4aae-9294-93bcc0a146a2.png)


## MODEL IMPLEMENTATION
We have implemented total 8 model and reported its accuracy. However, following is the some important models which gave us the great accuracy among all the models.
### Model 1 - Logistic Regression
![image](https://user-images.githubusercontent.com/120029190/226265931-3d95888c-b358-4244-a2a1-abac36746242.png)

### Model 2 - Random Forest Classifier 
#### Using Smote Technique :
![image](https://user-images.githubusercontent.com/120029190/226266518-87451876-69a2-4995-860c-2acbf0756cc6.png)

#### Using Tomek Link Technique :
![image](https://user-images.githubusercontent.com/120029190/226266896-9cba2145-e292-40f2-b574-8a6ad5ee953e.png)

### Model 3 - Random Forest Classifier 
#### Using Smote Technique :
![image](https://user-images.githubusercontent.com/120029190/226267130-26673d22-3ca5-4f58-8eb1-4a988116f002.png)

#### Using Tomek Link Technique :
![image](https://user-images.githubusercontent.com/120029190/226267229-e44ab793-c291-4917-bcee-afb8b4a5a444.png)

## RESULT
![image](https://user-images.githubusercontent.com/120029190/226267414-46ea8a82-1511-410a-99c4-17afdd21e8b4.png)


## FUTURE WORK
1.  Using advanced machine learning techniques:- 
Advanced machine learning techniques, perceptron, Data Mining can be applied to android authenticity prediction. These techniques can help in capture complex patterns in the data that may be difficult to detect using traditional modelling approaches.

2.  Developing AI bases Real-time Approach:- 
AI based approaches of real time Deep learning models, can be used to identify and examine new malicious applications. These methoda can be used to recognize malicious apps by analyzing the app's short history, browsing activity, and code structure. Further research should also be conducted to minimize online fraud and malware attacks by developing robust AI-based solutions.

3.  Cloud Computing for Huge Data:- 
Cloud computing can be used to store a large volume of Android data and detect malicious activities. So that we can get accurate prediction of authenticity of the applications.


## CONCLUSION
In conclusion, our goal was to use classification techniques to solve the problem of detecting malware applications on Android phones. We experimented with different supervised classification techniques and identified the best technique for each approach. The results obtained from this project show that artificial intelligence can be used effectively to detect and prevent malicious Android app downloads. This authenticator can save Android users from the potential dangers of downloading and installing malicious Android apps. By incorporating this AI-based authenticator into existing anti-malware safeguards, users can rest assured that their devices are protected from a wide variety of malicious threats. In addition, Random Forest and Gradient Boosting Classifier provide the great results in this approaches.

