DiagnoChat is an innovative healthcare chatbot designed to assist users in identifying potential health issues based on their symptoms. This user-friendly platform allows individuals to input symptoms via text or images, utilizing advanced machine learning models, particularly Bernoulli Naive Bayes, to provide accurate disease predictions. DiagnoChat also recommends nearby medical assistance for critical conditions, enhancing its utility and accessibility. This project highlights the development, functionality, and potential impact of DiagnoChat in democratizing healthcare access.

Keywords: Bernoulli Naive Bayes, GridSearchCV, SVM, KNN, Logistic Regression, Random Forest, DiagnoChat Interface, Symptom Description, Synonym Matching, Natural Language Processing (NLP).

Introduction

Precise disease diagnosis is critical for timely treatment and improved patient outcomes. Leveraging advancements in machine learning and NLP, DiagnoChat aims to provide an accessible and accurate disease diagnosis tool. This study focuses on developing a system that interprets user symptoms using synonym matching and symptom suggestion, utilizing machine learning models for precise predictions.

Related Work

Prior research has demonstrated the efficacy of machine learning models like Gaussian and Bernoulli Naive Bayes in disease diagnosis. Studies have shown high accuracy rates for these models, emphasizing their potential to enhance diagnostic processes and healthcare accessibility.

Design and Methodology

Dataset

The dataset, sourced from the National Health Portal of India, contains information on over 200 diseases and 489 symptoms. This data is used to train machine learning models for disease prediction.

Design Approach

The project integrates machine learning and NLP techniques to develop a versatile chatbot interface. Key steps include refining user input, employing dynamic classifiers, and incorporating a recommendation system for medical assistance.

Methodology

1. Probability Calculation: Bayesian inference is used to calculate disease probabilities based on symptoms.
2. NLP Feature Extraction: Symptoms are extracted using regular expressions and a custom synonym dictionary.
 ![image](https://github.com/user-attachments/assets/1ab73087-9d61-4378-bee3-eeac08f253c0)

![image](https://github.com/user-attachments/assets/ad33971c-20d8-4dee-8c0d-9e885ea7b2e2)

4. Machine Learning Predictions: A trained classifier predicts diseases based on user-input symptoms.
5. ChatBot Interface: The interface, built with HTML and JavaScript, supports text and image inputs for symptom description.
6. Medical Assistance Recommendations: Critical conditions trigger recommendations for nearby healthcare facilities.

Machine Learning Models

Various models, including Logistic Regression, SVM, KNN, Decision Tree, Random Forest, and Bernoulli Naive Bayes, were evaluated. The Bernoulli Naive Bayes model, optimized with GridSearchCV, achieved the highest accuracy of 90.11%.

![image](https://github.com/user-attachments/assets/ef635051-36b1-4bcb-b850-b26782e0ee19)

Accuracy and Validation

The disease prediction model demonstrated substantial accuracy, with a custom Naive Bayes model achieving 70.91% and the GridSearchCV-optimized model reaching 90.11%. Rigorous validation techniques confirmed the model's reliability and potential for clinical use.

![download (4)](https://github.com/user-attachments/assets/3e7f19b0-a5b3-4241-a600-255df7076fef)


![download (5)](https://github.com/user-attachments/assets/1f8ad5b6-f0a2-4668-bf19-8d17edb9b34c)


Experimental Results

The optimized Bernoulli Naive Bayes model significantly outperformed traditional models, highlighting its effectiveness in handling binary features for symptom-based disease prediction. The user-friendly interface ensures accessibility for all users, regardless of technical expertise.

![download (6)](https://github.com/user-attachments/assets/9d09abd1-9dfd-48d8-acd2-b396ac652641)

![image](https://github.com/user-attachments/assets/9462ddf9-17b5-4813-b724-d6744914a7ef)

![image](https://github.com/user-attachments/assets/c2128869-e5c9-45fd-a0bc-816361123b05)

Summary and Implications

Through comprehensive experimentation with various machine learning models, DiagnoChat achieved notable accuracy improvements in disease prediction. The project underscores the potential of AI in healthcare, providing a foundation for future advancements in accessible and precise disease diagnosis.
![image](https://github.com/user-attachments/assets/855aa87c-beea-4d94-9811-212f0b68ec45)

![image](https://github.com/user-attachments/assets/5bdc559e-5b74-496d-b3a8-b3e5923f816b)
