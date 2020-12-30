# WasteManagement
Meet our diverse and international team
Mahabir Gupta
Aaradhanah A
Harsh Ghodkar 
Arpit Dubey
# Overview
We are leavening the capability of AI to generate a model which will convey whether the waste product in an image is recyclable or not. Moreover it will also suggest the proper way to handle it.
We generated a Machine Learning Model and trained it over the existing datasets of images of Waste Products found on Kaggle. We have created the model to categorize accurately if the waste product shown in the image is recyclable or not. 

# Goals
Classifying products as Recyclable or Disposable/Organic
Generating a signal/alert telling the result in a visual format


# Problem Explanation 
According to a statistical analysis conducted in the United States of America , 75 % of the country’s waste is recyclable yet only 30 % of the waste is actually recycled. So tons and tons of recyclable waste makes its way to the landfills instead of getting recycled leading to wastage of resources , soil contamination and harm towards the environment. 
A single recycled plastic bottle saves enough energy to run a 100 watt bulb for 4 hours. It also creates 20% less air pollution and 50 % less water pollution than would be created when making a new bottle.
The United States throws away $11.4 billion worth of recyclable containers and packaging every year. If 1/10 of all discarded American newspapers were recycled annually, approximately 25 million trees would be saved.
Thus, recycling becomes a huge concern when we want to work towards a better environment. We are trying to propose a solution to this problem via Machine Learning. 

# What it does
We built up an application which allows the user to click a picture of the waste products and via the Deep Learning model it categorizes if a waste product is recyclable or disposable. This way an automated system could be installed in the places where waste management is done.
Technologies Used
Flutter - (Frontend)
We used Flutter to build an application which would do the task of capturing the image and then sending that image for processing to the model. 
MongoDB - (Backend)
A  NO SQL database to store all the scanned pictures of the users and storing the classification and use it in case of recurring images for faster processing.

AI ( PyTorch, TensorFlow and Keras )  
A model with brilliant accuracy was required in order to read the image and classify it. We tried different methods in order to achieve that accuracy in a low number of epochs. Finally, we were able to reach the accuracy of 97% using a multilayered Neural Network.

Further Scope 
This is just a key foundation step of using Deep learning models for the problems faced by humans.
We could install such a model in places where waste products need to get categorized. We are talking about scales varying from regular household to large scale industries.
The model could be connected to a separator via IoT and this way the waste management process will be completely automatized.

# Challenges we ran into 
The frontend and backend were created on various platforms and were working independently , connecting the different parts and making it work as a single unit was a difficult task to accomplish. 

# References 
For the facts and information : 
The Recycling Industry is losing money 
Think Twice about your trash 


# Flutter 
1. Install flutter 
2. Go the bin directory 
3. Execute script ./flutter 
4. run flutter doctor 
5. Flutter run which will run the application in real device if your phone 
   is connected to laptop otherwise it will open on emulator.
