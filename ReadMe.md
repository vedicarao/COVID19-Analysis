# IBMHACKCHALLENGE 2020
## COVID-19 TWITTER SENTIMENT ANALYSIS VISUALISATION DASHBOARD
![intro](https://images.unsplash.com/photo-1552120476-9ee56c8611f7?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

## PROJECT DEMONSTRATION VIDEO AND REPORT
Find **Video** here -> https://drive.google.com/drive/folders/17T-ytbKAgtg1z0wrf-MMXJC_bssDsEQD?usp=sharing

Find detailed **Project Report** here -> https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/IBM%20HACK%20CHALLENGE%20PROJECT%20REPORT%20(1).pdf

Find **Project PPT** here -> https://docs.google.com/presentation/d/1khU2b31zzD5HEGPFnvS4dBTM_QMKjtBnt1EkYxWK1SU/edit?usp=sharing

## Introduction

   Sentiment Analysis (Opinion Mining) is an extremely powerful tool for predictive modelling and analysis. Sentiment Analysis relies on advanced text mining techniques and then performs Natural Language Processing on the texts to predict the latent sentiment or opinion of the text in a given context like analysing movie reviews, restaurant ratings or in this case government response against the backdrop of the coronavirus pandemic.
   
## Features of our app
   1.It can translate tweet of any language including all Indian languages like Hindi, Marathi, Bengali, Gujarati, Tamil, Kannada etc and calculate corresponding sentiment score.</br>
   2.Tweets with sentiment score is live plotted on a map clearly indicating positive,negative and neutral.</br>
   3.Dynamic Charts and plots showing COVID-19 statistics from all countries across the  world.</br>
   4.Tweets on lockdown saved in database for predictive analysis and displayed on visualisation dashbaord with pie charts, line graph etc.</br>
   5.Latest Twitter News updates from Health Agencies(Eg WHO,MOHFW), Travel(AAI,IRCTC etc), News Channels(BBC).</br>
   6.COVID-19 ChatBot assistant to answer any and all COVID related queries.</br>
   7.Name, Address of all COVID-19 Centres in Karnataka plotted clearly on a map.</br>
   

## Prerequisites
   1.IBM Cloud Account(https://cloud.ibm.com)</br>
   2.Twitter Developer Credentials(https://developer.twitter.com/en#)</br>
   3.Create a Mapbox account(https://www.mapbox.com/)
   
Getting access to twitter API: 
Connect to twitter API by creating a developer account and request credentials for access.
Link->https://docs.inboundnow.com/guide/create-twitter-application/

Setting up IBM cloud services: 
Setting up an IBM cloud account in and creating Node Red Cloud Foundry App. Create Cloudant,ElephantSQL,Visual Recognition, Watson Language Translator Services and connect to Node Red app.

Getting MapBox API Credentials
Create a MapBox account,and get the API tokens

## Procedure
### Importing Flows
1.Open Node-red Flow Editor.</br>
2.Go to the top-right menu section and click on the import option.</br>
3.Import the flows from the folder. After importing the flows, if certain nodes are not installed, install all required nodes from the manage palette of the menu section in node red flow editor.</br>
4.Put your corresponding credentials in the Visual Recognition API node, MapBox Access Token node,the Twitter node,the Postgrestor node and the Cloudant nodes.</br> 

### User Interface
   Copy the HTML code from the HTML/CSS folder in the repo(inline CSS)[use only on desktop]</br>
     1.Landingpage.html</br>
     2.News.html</br>
     3.Stats.html</br>
 Copy the HTML code and paste the entire code in the corresponding template nodes in the Main Page flow.
 
 ### Deploying
 1.Once all the Flows have been imported,the API key values inserted in the respective access nodes,and the HTML codes copied into the template nodes.Click on the red deploy button on top right corner of the node red flow editor.</br> 
</br>

 
 ![Landing Page](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/LandingPage.gif)
 
 
 # Node-Red Flows
 
 ![](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/Flows_pics/HomePage.JPG)
 # Flow 2 - Tweet Dashboard
 ![](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/Flows_pics/MainPage.JPG)
 ![](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/Flows_pics/DashboardFlow.JPG)
 ![](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/Flows_pics/LineGraph.JPG)
 ![](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/Flows_pics/MapFlow.JPG)
 ![](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/Flows_pics/ImageFlow.JPG)
 ![](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/Flows_pics/PostgrestorFlow.JPG)
 
 
 # Preview
 
 ![](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/Screenshots/dashboard.JPG)
 ![](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/Screenshots/imageanalysis.JPG)
 ![](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/Screenshots/lockdown.JPG)
 ![](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/Screenshots/mapnew.jpg)
 ![](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/Screenshots/StatsNew.jpg)
 ### COVID-19 STATISTICS
 ![](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/Screenshots/NewsUpdates.JPG)
 ### NEWS UPDATES
 
 ![](https://github.com/SmartPracticeschool/SBSPS-Challenge-4486-Sentiment-Analysis-of-COVID-19-Tweets-Visualisation-Dashboard./blob/master/Screenshots/Chatbot.JPG)
 ### CHATBOT
 ## Conclusion
 This COVID-19 Twitter Sentiment Analysis Web Application can stream live tweets and update the sentiment score on a visualisation dashboard. All user locations along with sentiment score can be reflected on the map of India clearly indicating positive, negative and neutral tweets. It can also visualize images attached to tweets. Besides this, latest news from twitter is contantly updated in the news headlines page, and dynamic charts on the statistics page brings to the user the most recent trends and numbers relating to the pandemic.
 Tweets are also saved in a database for historical analysis. Future scope involves overcoming the twitter streaming API limitations.



 ### Images Used 
   All Images have been taken from Unsplash(https://unsplash.com/)</br> 
   **Visualisation Dashboard Home Page**</br>
   ![](https://images.unsplash.com/photo-1579869847557-1f67382cc158?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)
   
   **Statistics Page**</br>
 ![](https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=60)

   
   **Landing Page**</br>
 ![](https://images.unsplash.com/photo-1480694313141-fce5e697ee25?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)
 
 ## Team Members
 1.Ahan Bose</br>
 2.Vedica Rao</br>
 3.Prithwijit Banerjee
