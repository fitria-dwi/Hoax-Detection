# Hoax Detection Model for Identifying Deceptive Content

_Created by Fitria Dwi Wulandari – September, 2020_

### **Project Background**
In today's digital age, the spread of misinformation and fake news poses a significant challenge, impacting public opinion, decision-making processes, and even social cohesion. Recognizing the importance of combating this issue, the project aims to develop a hoax detection model capable of identifying and flagging potentially deceptive content across various online platforms.

### **Objectives**
The primary objective of this project is to develop a hoax detection model capable of identifying and flagging potentially deceptive content, thereby helping users discern between reliable and unreliable sources and preventing the spread of harmful information.

### **Methodology**
#### <code style="color : darkpurple">Data Preparation</code>
* **Source**: The dataset was obtained from the Satria Data for Big Data Challenge, which contains text data such as article titles and content.
* **Actions**: Involves removing unnecessary noise, transforming text into a consistent format, and handling any irregularities that may hinder meaningful analysis, such as removing stop words, removing punctuation and special characters, tokenization and stemming.
  
#### <code style="color : darkpurple">Machine Learning</code>
* **Approach**: Building predictive models to classify the sentiment of user feedback.
* **Algorithms Tested**: Four different algorithms were evaluated to determine the best model for hoax detection.

#### <code style="color : darkpurple">Tools</code>
* **Programming Language**: Python
* **Libraries**: Pandas, NumPy, Scikit-learn, NLTK, Matplotlib, Seaborn

### **Results**
The analysis revealed that the Logistic Regression model, achieving an accuracy of 83%, emerged as the most effective in predicting the truthfulness of articles. This model can serve as a valuable tool for users, enabling them to discern between reliable and unreliable sources and preventing the spread of harmful information that could lead to confusion, panic, or societal harm.

### **Future Work**
* **Implementation**: The best model will be used to predict unseen data (new articles), aiding in the continuous detection of deceptive content.
* **Model Improvement**: Explore more advanced natural language processing techniques and models to improve accuracy.
* **Extended Analysis**: Include additional data sources and variables for a more comprehensive detection system.

### Repository Contents
* [**Script**](https://github.com/fitria-dwi/Hoax-Detection/blob/main/Hoax%20Detection.ipynb): Python scripts for data preprocessing, cleaning, and model training.
