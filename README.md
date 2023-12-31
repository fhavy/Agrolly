# Agrolly #

By Gabriel Favour 
_______________________________________________________________________________________________________________________________________________  

## What is Agrolly? ##
Agrolly is a mobile app solution to help rural household farmers in developing countries tackle the challenges of climate change effectively. These farmers have suffered the most from abrupt variations rainfall and temperature decreasing their crop yields, given their small scale, the burden of economic exclusion, and lack of access to critical resources. Agrolly brings expert knowledge and cutting edge technology to the small farmers' hands, so they are able to make more educated agriculture planning decisions, increase the possibility of obtaining financing, and improve their economic outcome. It combines weather predictive algorithms built on IBM's platform with crop water requirements from the Food and Agriculture Organization for the United Nations (FAO), delivering an integrated solution tailored for the location of each farmer, type of crop, and stage of the plantation. With the support of Agrolly, farmers are able to efficiently design their plantation process and prevent disaster risks caused by extreme weather conditions. Besides, financial institutions could leverage Agrolly to risk assess each crop and provide more inclusive and lower-cost loans to rural household farmers. Using Agrolly, rural household farmers are also able to connect and learn from each other by building a national-level network.

## Contents 

01. [Short Description](#Short-Description)
02. [Demo Video](#Demo-Video)
03. [How it works](#How-it-works)
04. [Long Description](#Long-Description)
05. [Innovation/Competition](#Innovation)
06. [Project Roadmap](#Project-Roadmap)
07. [Getting Started](#Getting-Started)
08. [IBM Cloud Services](#IBM-Cloud-Services)
09. [Deployment/Pilot](#Pilot)
10. [Authors](#Authors)
11. [License](#License)

## Short Description <a name="Short-Description"></a>

### What's the problem?
Household farmers in emerging countries face a massive burden of economic exclusion accentuated by climate change. Family farming traditionally lacks access to basic resources for plantation given its small scale, poor access to information, and financing. Climate changes have made this situation worse. While rural household farmers are the ones who least contribute to climate change, they are the most vulnerable to change in climatic conditions given their economic dependence, as abrupt changes in rainfall and temperature result in reduced crop yields. These farmers also do not have adequate networking, from which they can learn and easily exchange know-how. They also do not have access to educated information regarding climate change trends and knowledge of climate-smart practices. Furthermore, those farmers are not skilled in climate risk assessment, which is an important factor in obtaining financing from financial institutions. This situation has made family agriculture unsustainable in many locations, causing an exodus of unskilled workers to the large cities who get rapped in an endless cycle of financial struggle and poverty, which is the root cause of many other social problems. Access to credit, networking, and climate-related information, most importantly on weather, would help to break this cycle.  While local banks have been interested to invest in green development and sustainable social businesses, they have struggled to implement more inclusive financing practices, given the unpredictability associated with family farming. 


### How can technology help?

* Connect rural household farmers with the ability to exchange text and photos.
* Real-time weather monitoring (*text and visual*).
* Provide Long-Term Weather Forecast (*temperature and rainfall*). 
* Talk with Specialist tool (using Artificial Inteligence bot to match farmers and local resources)
* Crop selection based on the forthcoming forecast. 
* Crop risk assessment by identifying weather problem areas in advance (before it started).

Improving on-farm techniques and data capabilities is critical to help farmers make more educated decisions within the context of climate change, based on predicted regional climate trends and knowledge of climate-smart practices. The ability to build a virtual ecosystem in which farmers will be able to network, learn and exchange know-how will also create a solid base for future developments. As a result, family farmers will increase their resilience in the face of environmental challenges, and also improve their ability to obtain financial credits and loans more favorable to their economic situation. 

Agrolly's solution uses cuting-edge technology to do the data analysis heavy lifting on behalf of household farmers, bringing the best fitted results of weather predictions to the farmers' hands. Furthermore, it combined weather predictions with the crop water requirements for Food and Agriculture Organization for the United Nations (FAO), which is tailored for the location of each farmer, type of crop and stage of the plantation. Agrolly's technology is built on IBM DB2 and IBM WATSON RStudio technology, and our program is written in: C/C++, Java, Javascript (ES6/ES7), PHP, AngularJS, IONIC, RxJS, Rstudio, Qt framework to provider the user the best operation system.

### What are the Languages available?
English, Portuguese (*Brazil*), Mongolian.


## How it works <a name="How-it-works"></a>
![picture alt](https://github.com/ajinkyadatalkar1/Agrolly/blob/master/Arquitecture.PNG?raw=true/20x10"Architecture")
1. App uses IBM’s **The Weather Company** to display hourly and weekly forecasts based on the location of the user.
2. We collect the weather information for the past 5 years from **NASA** and we generate annual predictions with the help of the IBM Watson studio.
3. For more information related regression , please read [our article here](https://github.com/ajinkyadatalkar1/Agrolly/blob/master/Draft%20Forecast%20Article%20-%20Partial%20Study..pdf)
4. We use FAO's guideline for the Risk Mangament caulcualtion for more information see [**guideline here**](http://www.fao.org/3/s2022e/s2022e00.htm#Contents)

## Long Description <a name="Long-Description"></a>
[Long Description Document Link](https://github.com/ajinkyadatalkar1/Agrolly/blob/master/Long%20Description%20Pitch%20Agrolly.docx)

## Innovation/Competition <a name="Innovation"></a>
![picture alt](https://github.com/ajinkyadatalkar1/Agrolly/blob/master/competitor%20chart.png?raw=true)
#### What to plant? 
Many familiar farmers face this question when they needed to decide some months ahead which crop to plant. Mainly decisions are based on the type of crops that work and last year's forecast. There is not a tool int the market that helps farmers to improve their decision.  
Some government and non-profit organizations such as FAO and the Brazilian government, each year provide a list os recommendations based on the weather forecast. However, it is no constantly updated, is in the paper base, sometimes several sheets per crop. Unlikely, those small farmers would use this information, because of the lack of knowledge and access to such information. Agrolly provides an interactive, visual risk crop assessment to help these farmers in making better decisions. #CropRisk #ClimaRisk

*Sample of the APP visual risk crop assessment:*
<div align="center">
        <img width="140%" src="Sample APP- Risk assesment Forecast.png" alt="About screen" title="About screen"</img>
        <img height="0" width="10px">

</div>

## Project Roadmap <a name="Project-Roadmap"></a>
![picture alt](https://github.com/ajinkyadatalkar1/Agrolly/blob/master/Agrolly_Road_Map.PNG?raw=true)
* For the 1st Phase, we focused on given farmers tools and knowledge to fight against changes in the weather.
  We are testing with some of the Mongolian farmers to identify user interface opportunities.
* The 2nd phase is planned to focus on the interactions between farmers so they can increase their relationship. This will enable them to know what others are planting and explore their options. We are also planning to integrate some tools so the farmers can leverage their know-how, such as the expert advice feature will allow farmers to get in touch with specialists and trends in the agriculture sector.
We plan in this phase to deploy  APP testing in Brasil - Parana. We already have done some contacts with local authorities. 
* Our 3rd goal is to connect small farmers with banks and customers, by implementing QR code for food traceability and farming credit score algorithms. We also plan to expand the risk mgm for deceases and market risks.

## Getting Started <a name="Getting-Started"></a>

#### Prerequisite
* Register for an [IBM Cloud account](https://www.ibm.com/account/reg/us-en/signup?formid=urx-42793&eventid=cfc-2020).
* Request a [Weather Company API key](https://callforcode.weather.com/)
* Dowload Forecast from [NASA webiste](https://power.larc.nasa.gov/data-access-viewer/) or use github library:
``` nasapower ```
* Read and select any forecast regression from the article provided.

#### Run it
* Download the Github code
* Install node.js
* Install Ionic and Cordova
* This app makes use of 18 plugins all of which are needed to be installed in order to compile the app or run on localhost
     1. Photo Viewer Plugin <br /> (https://ionicframework.com/docs/native/photo-viewer)
     2. Android Permission Management Plugin <br /> (https://ionicframework.com/docs/native/android-permissions)
     3. AndroidX Plugin <br /> (https://ionicframework.com/docs/native/firebase-x)
     4. AndroidX Adapter Plugin <br /> (Should automatically install when you install firebase plugin)
     5. Camera Plugin <br /> (https://ionicframework.com/docs/native/camera)
     6. Device Plugin <br /> (https://ionicframework.com/docs/native/device)
     7. Firebase Cloud Messaging Plugin <br /> (https://ionicframework.com/docs/native/fcm)
     8. File Plugin <br /> (https://ionicframework.com/docs/native/file)
     9. File Manager Plugin <br /> (https://ionicframework.com/docs/native/file-transfer)
    10. Full Screen Plugin <br /> (https://ionicframework.com/docs/native/android-full-screen) <br />
            * Available only on Android for devices with notch/ not supported on iOS
    11. Keyboard Plugin <br /> (https://ionicframework.com/docs/native/keyboard)
    12. Webview Plugin <br /> (https://ionicframework.com/docs/native/ionic-webview)
    13. Screen Orientation Plugin <br /> (https://ionicframework.com/docs/native/screen-orientation)
    14. Splash Screen Plugin <br /> (https://ionicframework.com/docs/native/splash-screen)
    15. Statusbar Plugin <br /> (https://ionicframework.com/docs/native/status-bar)
    16. Vibration Plugin <br /> (https://ionicframework.com/docs/native/vibration)
    17. Sql Lite Storage Plugin <br /> (https://ionicframework.com/docs/angular/storage)
    18. Google Services Plugin <br /> (Will be automatically installed when installing Firebase)

* Once the plugins are installed the platforms are needed to be added:
    01. In order to add the Android Platform run the following command:<br />
        <code>ionic cordova platform add android</code>
    02. In order to add the iOS Platform run the following command:<br />
        <code>ionic cordova platform add ios</code>

* Running the app:
    01. To run the app on a local node server:<br />
        <code>ionic serve</code>
    02. To run the app on an Android device:<br />
        <code>ionic cordova run android --device</code>
    03. To run the app on Android emulator:<br />
        <code>ionic cordova run android</code>

* Building packages:
    01. To build an Android package:<br />
        <code>ionic cordova build android</code>

## IBM Cloud Services <a name="IBM-Cloud-Services"></a>
* [IBM Cloud Object Storage](https://www.ibm.com/cloud/object-storage)
* [IBM Watson Studio](https://www.ibm.com/cloud/watson-studio)
* [IBM Watson Assistant](https://www.ibm.com/cloud/watson-assistant/) 
* [The Weather Company API](https://callforcode.weather.com/)   
Check out Agrolly's website  repository database [click here](https://github.com/helentsai17/agrolly) 

## Deployment/Pilot <a name="Pilot"></a>
In order to create the APP, we did previous research with the farmers to identify their main concerns and needs. The mains focus areas that we found were the lack of access to rainfall and bank loans.
We then started testing the APP features with a selected 15 farmers in the Mongolian householder farmers to identify any gaps in the user interface and improvements need in the APP.
* Start Date: 01/June/2020
* Region: Mongolia (Dornord Province)
* Currently real users :[15 users]( https://github.com/ajinkyadatalkar1/Agrolly/blob/master/Pilot%20Mongolia%20Users.png)
* Currently Situation: OnGoing. Collecting data.

Check the firsts feedbacks from the field test done to the APP's user interface: 
* [Feedback Director of the Alt Margad- Khentii province](https://www.youtube.com/watch?v=_mRERF0wa1Y).
* [Feedback family farmer Sukhbaatar province](https://www.youtube.com/watch?v=SHfCFlWM-5c).

## Authors <a name="Authors"></a>
* Ajinkya Datalkar - Product & Sotware Developer[*See Linkedin*](https://www.linkedin.com/in/ajinkya-datalkar/)
* Manoela Morais - Data Intelligence (R program) & Project Management [*See Linkedin*](https://www.linkedin.com/in/manoelamorais/)
* Gabriel Favour - Web Developer & system design [*See Linkedin*](https://ng.linkedin.com/in/favour-gabriel-390a79188)
* Chimka Munkhbayar - Mongolian Deployment [*See Linkedin*](https://www.linkedin.com/in/chimka-munkhbayar-0ab421b5/)


