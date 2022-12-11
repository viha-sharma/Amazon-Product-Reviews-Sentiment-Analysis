## Amazon-Product-Reviews - Sentiment-Analysis

---

### **Table of Contents**

[1. Problem Statement](#problem-statement)   
[2. My Approach](#my-approach)   
[3. Technologies used](#technologies-used)   
[4. Project Objectives](#project-objectives)   
[5. Running My Deployed project on your Local Server](#running-my-deployed-project-on-your-local-server)   
[6. Data source files](#data-source-files)

---
### **🔹Problem Statement**

It is observed that the maximum number of customers look at product reviews before they make a purchase. Survey results show that positive product reviews are a key factor for purchasing by 57% of Amazon buyers (Statista, 2019). 

As product reviews are often the deciding factor for many customers, it’s very important to have a well-automated system for monitoring them.

The traditional manual process of Amazon product reviews is time-consuming and inefficient when millions of reviews are being posted all the time. It doesn’t show any trend or patterns over time. Moreover, it is tough to understand customers’ sentiment towards any product or its delivery.

---

### **🔹My Approach**

I will be classifying Amazon customer reviews from the source files mentioned below, into 3 categories of positive, negative and neutral. The techniques used to solve this problem involve Text Classification and Time Series Analysis.  

An automated system was developed to analyze and monitor an enormous number of reviews. By monitoring the entire review history of products, we analyzed the tone, language, keywords, and trends over time to provide valuable insights that increase the success rate of existing and new products as well as marketing campaigns. 

*Sentiment Analysis* is a technique used in Natural Language Processing that converts unstructured text into data that can be analysed. It is an emerging tool that helps businesses differentiate and categorize opinions about their products, services and brand image.

*Time Series Analysis* helps in highlighting trends to forecast sentiment trends for particular subcategories in the future. Brands can discover many hidden trends in customer sentiments from historical data.

---

### **🔹Technologies used**

<img width="576" alt="image" src="https://user-images.githubusercontent.com/106082126/206910501-2117e9e8-b694-4872-b618-d28503ff3e3f.png">

---

### **🔹Project Objectives**

➣ Reviews Preprocessing and Cleaning

➣ Story Generation and Visualization from reviews - Tableau

➣ Extracting Features from Cleaned reviews

➣ Model Building: Sentiment Analysis

➣ Model Building: Time Series Analysis

➣ Model Deployment

---

### **🔹Running my Deployed project on your Local Server**

Go to your command prompt/terminal, change your directory to the folder that includes all the files in the deploymed_files folder 

Then, enter the following codes:

1. pip install virtualenv
2. virtualenv ENV
3. ./ENV/Scripts/activate
4. install all required dependencies listed in requirements.txt
5. To run our website on your local server, enter the code **python app.py**
6. Enter the ip address generated, on your browser's search bar. 

---

### **🔹Data Source Files**

I would like to deeply thank Julian McAuley for sharing this mass collection of datasets containing Amazon reviews. These files can be accessed from the link below:-

http://jmcauley.ucsd.edu/data/amazon/

4 datasets that I used in this project are (Per-category files):

1. Home and Kitchen - reviews 
2. Home and Kitchen - metadata
3. Musical Instruments - reviews
4. Musical Instruments - metadata

---

Feel free to send me your queries on <vihasharma1099@email.com>
