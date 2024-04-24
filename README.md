
# SC1015-FDAA-MINI-PROJECT-GROUP-9 - ShopSentinel: Safeguarding Ecommerce Customer Satisfaction

### Members:

Heng Yun Tat yheng015@e.ntu.edu.sg , Parameswaran Sethu Rugma RUGMA001@e.ntu.edu.sg, Saad Farhatullah Mohammed saad002@e.ntu.edu.sg

### Contributions:

Heng Yun Tat - The full IPYNB code, Data cleaning, Data Visualisation , Exploratory Analysis, Machine learning,  Problem statement generation, Dataset finding, Project Aims, Project Justifications and theory,  Video

Parameswaran Sethu Rugma - Data Cleaning and Exploratory Analysis,  Slides and Video 

Saad Farhatullah Mohammed - Slides 


### About:

This project is about optimising the ECommerce Customer Satisfaction Score (CSAT SCORE)  by looking at the contributing variables in a ECommerce platform called Shopzilla.

### Problem Statement:

Are we able to predict CSAT Score of Customers? 

How does the different features of an item and the nature of the interaction with the client affect the ultimate satisfaction rating of the customer in ECommerce shopping? 

### Navigating the Repository:

* ReadMe: Project aims and project details

* DSAIMiniProject.ipynb: Full code for Data Extraction, Data Visualisation, Data Cleaning, Machine Training and Prediction Model

* Excel: Dataset excel sheet

* Report: Full report on the project

### Models used, new concepts, Algorithms and Libraries:

* Numpy

* Pandas

* Seaborn

* Matplot

* Principal Component Analysis - Simplifying of multiple variables and capturing essential information

* Chi Square Test of Independance - Correlation between categorical varaibles 

* One Hot Encoder  - Conversion of categorical variables to numerical inputs for learning models

* Decision Tree Machine Learning Model - Both MultiVariate and PCA 


### Conclusion of project:


From Principal Component Analysis, the 2 variables that are most significant in capturing and influencing final CSAT score are the Response Time, with a negative correlation, and the Channel Name (inbound, outcall, email etc), with a positive correlation. The response time is a clear and logical component that affects CSAT score as how long the interaction takes directly translates to the efficiency of the problem resolution. Quick responses boost satisfaction levels, while delays may lead to dissatisfaction. 
The Channel Name, as depicted by the exploratory analysis, calls, inbound and outbound do better in CSAT score at 4-5 which is high, and emails are more spread out. The channel name component and its influence, could be a result of human psychology where telephone calls are more personal whereas while emails are instantaneous, telephoning someone means taking time out of your day to stop and make the call. This shows more care, demonstrates more attention and better can demonstrate better customer service.
Secondly, Phone calls are often faster, Messages can be conveyed more quickly over calls than exchanging them  via email, making the interactions more efficient. 

The result of our project indicates that these 2 components are something that the company Shopzilla should consider more on, to reduce response time and focused channel name on calls instead of emails, especially for conflict resolution. 
Mainly, fast response time increases customer satisfaction by providing quick solutions to problems and reducing issue resolution time. A fast response to customer queries builds trust and loyalty, demonstrating a commitment to excellent customer service.

### References: 

* https://docflite.com/importance-of-response-time-in-customer-service#:~:text=Fast%20response%20time%20increases%20customer,commitment%20to%20excellent%20customer%20service.
* https://www.similartech.com/technologies/shopzilla
* https://icuc.social/resources/blog/importance-of-brand-reputation-management/#:~:text=A%20strong%20reputation%20increases%20customer,they%20perceive%20your%20brand%20positively.
* https://kaizo.com/blog/importance-of-customer-satisfaction/#:~:text=Positive%20customer%20satisfaction%20leads%20people,services%20to%20increase%20sales%20revenue.












