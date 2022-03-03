![MATLAB BANNER](https://github.com/matlab-ambassadors-es/MATHACK2022/blob/main/assets/BANNER.jpg)

## About the challenge
<p align="justify">
The <b>European MATLAB Student Ambassadors</b> presents to you, a new challenge in our own new Hackathon edition! To be successful in this challenge, you will need to develop a small application that contributes to the <a href="https://sdgs.un.org/goals">UN Sustainable Development Goals</a> with the help of <b>MATLAB</b>, a mobile device and it’s sensors.
</p>

<p align="center">
  <img width="560" height="auto" src="https://upload.wikimedia.org/wikipedia/commons/a/a7/Sustainable_Development_Goals.svg">
</p>

## Table of Contents:

 - [Key Dates 📅](#key-dates) 
 - [What to Build 🛠️](#what-to-build) 
 - [Awards and Prices 🏆](#awards-and-prices) 
 - [Training Session Materials 📚](#awards-and-prices)

   - [Fitness tracker with data acquired from MATLAB Mobile](#fitness-tracker-with-data-acquired-from-matlab-mobile)
   - [DNN in MATLAB - Running detection](#dnn-in-matlab---running-detection)

## Key Dates
| Topic | Date |
|--|--|
| Training Session | 4 of April| 
| 1st HACKATHON Day | 5 of March| 
| 2nd HACKATHON Day | 7 of March|
| Submission Day | 7 of March 19:30h CEST|
| Awards Day | TBD |

## What to Build
<p align="justify">
In order to build an application that contributes to the <a href="https://sdgs.un.org/goals">UN Sustainable Development Goals (SDGs)</a>, you have to use <b>MATLAB</b> and <b>MATLAB Mobile</b> (either Androir or IOS). The idea is to acquire data using smartphone's sensors with <b>MATLAB Mobile</b> and manage this data with the aim to develop an application linked to UN SDGs. You are free to adopt any MATLAB Toolbox and functionality that you think is useful for you purpose (e.g. Deep Learning, Machine Learning, Sensor Fusion Tracking, Maps, Symbolic, Satellite etc) also because more solution technological novelty means more points for your team !  Be sure that your data are correct (filter your data should be a good idea) and try to use all the informations form sensors.

So, free your imagination and look the potential of the data you have at your disposal ! 
</p>

## Awards and Prices:

The prizes will consist of Amazon Gift Cards of several quantities (please check the Prizes section for more info). If you have the opportunity to be part of any of the organising european universities and you assit to the on site event you may recive some MathWorks Giveways. 

<p align="center">
  <img width="560" height="auto" src="https://github.com/matlab-ambassadors-es/MATHACK2022/blob/main/assets/prizes_img.png">
</p>

# Training Session Materials:

## Tools and technologies
- [MATLAB Mobile for iOS](https://es.mathworks.com/help/matlabmobile/)
- [MATLAB Mobile for Android](https://es.mathworks.com/help/matlabmobile_android/index.html)
- [TUTORIAL - How to Acquire Data from Android Device Sensors with MATLAB Mobile](https://blogs.mathworks.com/community/2014/10/06/acquire-data-from-device-sensors-with-matlab-mobile/?s_tid=blogs_rc_3&doing_wp_cron=1645022423.1221868991851806640625)
- [Types of MATLAB Plots Summary](https://es.mathworks.com/help/matlab/creating_plots/types-of-matlab-plots.html)
- [How to Use Source Control in MATLAB with GitHub](https://www.youtube.com/watch?v=O7A27uMduo0)

## Inspiration
- [Road profile and traffic analysis using MATLAB mobile By Darshan Ramakant Bhat](https://es.mathworks.com/matlabcentral/fileexchange/69513-road-profile-and-traffic-analysis-using-matlab-mobile?s_tid=srchtitle)
- [MATLAB4MOBILE Floor Racing by Boris Notkin](https://es.mathworks.com/matlabcentral/fileexchange/63321-matlab4mobile-floor-racing?s_tid=srchtitle)
- [MATLAB-mobile-fitness-tracker by MathWorks Student Competitions Team](https://es.mathworks.com/matlabcentral/fileexchange/77269-matlab-mobile-fitness-tracker?s_tid=srchtitle) 
- [Real Time GPS and data tracker applicatio by Jesper van Wordragen](https://es.mathworks.com/matlabcentral/fileexchange/63202-real-time-gps-and-data-tracker-application-for-the-matlab4mobile-contest?s_tid=srchtitle)
- [TUTORIAL - Create Your Own Fitness Tracker with MATLAB Online and MATLAB Mobile](https://blogs.mathworks.com/student-lounge/2020/06/24/create-your-own-fitness-tracker-with-matlab-online-and-matlab-mobile/?doing_wp_cron=1645022376.8629879951477050781250)

## Fitness tracker with data acquired from MATLAB Mobile:
<p align="justify">
  In this example we will show you how to acquire data from smartphone's sensor using <b>MATLAB</b> and <b>MATLAB Mobile</b> and develop a fitness tracker that counts steps.

To realize our task we have 2 options:
</p>
<ul>
<li>Log data locally on your smartphone and load automatically on <b>MATLAB Drive</b>, after that we can move on MATLAB laptop APP and load file with all the measurements from MATLAB Drive folder (main_log_data.mlx).</li>
<li>Stream data from <b>MATLAB Mobile</b> to <b>MATLAB</b> and acquire immediately the data (main_stream_data.mlx).</li>
</ul>

<p align="justify">
Having all the sensor's measurements (position, velocity, angular velocity, acceleration, heading) we can make a lot of things, for example using position is simple realize a steps counter knowing the total distance traveled and average stride. With this data many things can be done, the only limit is imagination.!
</p>

[Back to top ⬆](##about-the-challenge)
 
## DNN in MATLAB - Running detection:
 In this example we will show you how develop a simple deep neural network to train a "run or walk classifier". 
 
 * To download the dataset used in the Demo : [A dataset containing labeled sensor data from accelerometer and gyroscope](https://www.kaggle.com/datasets/vmalyi/run-or-walk)
 
 Remeber to follow this workflow during the development of your application (once data are collected, labeled and, of ocurse, pre-processed!):
 * Choose architecture of our network. Check deep learning toolbox documentation to see wich kind of pre-defined layer you could use : [List of Deep Learning Layers in MATLAB](https://it.mathworks.com/help/deeplearning/ug/list-of-deep-learning-layers.html)
 * Choose the optimizers and hyper-parameters : [Options for training deep learning neural network](https://it.mathworks.com/help/deeplearning/ref/trainingoptions.html?searchHighlight=optimizers%20deep%20learning&s_tid=srchtitle_optimizers%20deep%20learning_4)
 * Train the network 
 * Evaluate performance

[Back to top ⬆](#about-the-challenge)
