Portfolio
========
## *Portfolio of my projects*

Below You can see listing of a couple of projects I did by myself or was involved into during commercial work, my studies at Silesian University Of Technology and hobby projects:

* **Commercial AI projects - 6+ years of experience, 8+ projects**
  * **Autonomous driving**
  * **Brain tumour population modelling**
  * **Predictive maintenance**
  * **Anomaly detection**
* **PhD**
  * **Topic**
  * **Algorithm ©**
  * **Articles**
  * **Conferences**
* **AI projects - hobby**
* **Open Source Contributions**
* **Other commercial projects**
  * **IT projects**
  * **Projects for automotive**
* **Other hobby projects**
* GameDev
* IoT
  * GameDev - RPG: GemPrisoners(Box2D + SFML)
  * Raspberry Pi - Computer Vision, NLP, Speech recognition...
  * Pottery Factory BeagleBone version
  * Pottery Factory EVK1100 + freeRTOS version
  * SmartRoom web version
  * SmartRoom LabVIEW version
* Private lessons for students: physics, mathematics, mechanics

Documentation of some projects is available on my GitHub repository as *.pdf* files. You can simply download them or read on GitHub.

## Commercial projects
### AI projects
**Autonomous driving**
<br />
*Skills: Computer Vision, Python, Pytorch, Tensorflow, OpenCV, Deep learning, Machine Learning*
<br />

**Brain tumour population modelling - Project with association with Institute of Automatic Control of Silesian University of Technology**
<br />
*Skills: Python, Deep learning (Autoencoders), Machine Learning, MATLAB, mathematical modeling*
<br />

**Manufacturing events prediction**
<br />
Several techniques used for prediction of events that came into centralized alarm system implemented on production hall.
<br />
*Skills: Python, pandas, scikit-learn, Tensorflow, Data Science, Machine Learning, Deep Learning, Jupyter Notebook*
<br />

**Hydraulic oil-pump predictive maintenance**
<br />
Classification and regression algorithms used for prediction of oil-pump failure. Interestingly, distinction depending on different kind of failure was made.
* First stage of a project was to indicate if "someting is going wrong with the pump".
* Second stage was to distinct what kind of failure will appear.
* The late stage was to perform multidimensional regression task and to estimate approximately when the pump will fail.

Algorithms used: RandomForestClassifier, MLP with softmax layer, DecisionTreeClassifier, GaussianNB, SGDClassifier
Because of lack of data during training and model deployment StratifiedKFold cross-validation was be performed.
<br />
*Skills: Python, scikit-learn, Tensorflow, Microsoft Azure, Data Science, Machine Learning, Deep Learning, Jupyter Notebook*
<br />

**Water pumps predictive maintenance**
<br />
Aim of a project was to estimate Remaining Useful Life (RUL) of each of pump system with usage of vibration- and temperature data. Using several models trained with GridSearch combined with curve fitting - finally VotingRegression (ensemble learning) was applied.
<br />
*Skills: AzureML, Python, pandas, scikit-learn, Tensorflow, numpy, Data Science, Machine Learning, Deep Learning, Jupyter Notebook (AzureNotebooks)*
<br />

**Train predictive maintenance**
<br />
Goal of a project was to estimate Remaining Useful Life (RUL) of each subsystem (hydraulic, pressure, running-subsystem...) on a train. It was regression task with a bit of anomaly detection. Several modelling techniques were involved - LinearRegression, LogisticRegression, curve fitting ensemble learning (VotingReggressor).
<br />
*Skills: AzureML, Python, pandas, scikit-learn, Tensorflow, numpy, Data Science, Machine Learning, Deep Learning, Jupyter Notebook (AzureNotebooks)*
<br />

**Predictive maintenance for industrial fans**
<br />
With the use of vibration data Remaining Useful Life (RUL) with precisely described fault should have been calculated. Both cloud and on-premise analysis was performed.
<br />
*Skills: AzureML, Python, pandas, scikit-learn, Tensorflow, numpy, Data Science, Machine Learning, Deep Learning, Jupyter Notebook (AzureNotebooks)*
<br />

**High pressure aggregate anomaly detection**
<br />
Real-time analysis with the usage of measurements of several factors that described the aggregate
<br />
*Skills: Python, scikit-learn, Tensorflow, Microsoft Azure, Data Science, Machine Learning, Deep Learning*
<br />

## PhD
**Topic** </br>
Predicting failure of industrial devices using vibrodiagnostics using artificial intelligence </br>
**Algorithm ©** </br>
**SCFCTfRUL** - **S**pectrogram -> **C**NN -> **F**latten -> **C**ompress -> **T**rajectory -> **f**or **RUL** </br>
Pick a spectrogram -> put it on CNN -> take flatten layer outputs -> compress to 2D -> track how extracted features move on a plane -> put confidence vector from CNN as output for MLP regression -> create trajectory of working point on 2D plane -> calculate Remaining Useful Life-> visualize to client
* **Publications**</br>
    * Anomaly detection for Hydraulic Power Units - case study ->  DOI: [https://doi.org/10.3390/fi15060206](https://doi.org/10.3390/fi15060206)</br>
    * State of art in predictive maintenance with use of digital signal processing </br>
    * Predictive maintenance for trains - case study</br>
    * Vibration velocity prediction with regression and forecasting techniques for axial piston pump</br>
* **Conferences**</br>
    * DSS 2021 ML Edition:
      * How to handle big HPU so as not to spoil it? Predictive maintenance for HPU
      * Stop, we are losing the wheel! Predictive maintenance for trains
    * POB5.T3 - digitization & IT: Digital transformation of a batch manufacturing plant
    * NWDPN XI:
      * Summary of vibrodiagnostic indicators of industrial equipment for the implementation of Predictive Maintenance systems
      * Predicting industrial equipment failures based on vibrodiagnostic analysis using artificial intelligence
      * Microsoft Azure capabilities in the context of deploying machine learning models on edge devices.

## AI projects - hobby
**"Speech Template Recognition System"**
<br />
Git repository: Speech-Template-Recognition-System https://github.com/kajakIYD/Speech-Template-Recognition-System <br />
*Skills: Python, C++, Digital Signal Processing, RaspberryPi, Deep Learning, QtCreator, Qt libraries*
<br />
**System-Identification-ANN**
<br />
My master thesis, complex analysis of dynamic system identification using Recurrent Neural Networks (RNN) and its variations (LSTM, GRU)
https://github.com/kajakIYD/system-identification-ann
<br />
**AI classification**
<br />
Kaggle "Sick or well heart disease" classification challenge.
https://github.com/kajakIYD/AI-Classification
<br />
**"StockPricesPrediction"**
<br />
Is it worth to buy Apple stock right now?
Available on GitHub. https://github.com/kajakIYD/Stock-Prices-Predictions
<br />
**Wine classification**
<br />
How good is wine based on several phisycal-measurable factors?
https://github.com/kajakIYD/Wine-classification
Dataset: https://archive.ics.uci.edu/ml/datasets/Wine+Quality
<br />
**"Energy efficiency prediction"**
<br />
What is the efficiency of a building based on its shape, surface area, roof area...
Available on GitHub. https://github.com/kajakIYD/Energy-efficiency-regression
Dataset: https://archive.ics.uci.edu/ml/datasets/Energy+efficiency#
<br />
**"Expert System"**
<br />
Git repository: https://github.com/kreeaq/Expert-System <br />
*Skills: C#, WPF, Horn clauses*
<br />
**SPAM or HAM?**
<br />
Famous kaggle mail-classification challenge.
Available on GitHub. https://github.com/kajakIYD/SPAM-or-HAM
<br />
**"GenderClassifier"**
<br />
Classification used
Available on GitHub. https://github.com/kajakIYD/GenderClassifier
<br />
**"RecommendationSystem"**
<br />
Would You like "Lord Of The Rings" if You like "Troy"?
Available on GitHub. https://github.com/kajakIYD/Recommendation-System
<br />
**"TwitterSentimentAnalysis"**
<br />
Answering the question: was the Tweet gentle or violent using Twitter and NLTK.
Available on GitHub. Work in progress.
<br />
**"Grouping-Algorithms"**
<br />
Clusterization on students grades performed and compared in 4-ways.
Available on GitHub. https://github.com/kajakIYD/Grouping-Algorithms
<br />
**"Association-Rules"**
<br />
Software useful for supermarkets, because it indicates where to place products in shops (ex. mustard nearby sausage ;))
Available on GitHub. https://github.com/kajakIYD/Association-Rules
<br />
**"Probability"**
<br />
Sandboxes for Bayes theorem and binomial distribution
https://github.com/kajakIYD/Bayes_Theorem | https://github.com/kajakIYD/Binomial_distribution
<br />
**"Taylor series"**
<br />
Taylor series analysis
https://github.com/kajakIYD/Taylor-series
<br />
**"Data science from scratch"**
<br />
Several ML and data analysis algorithms from scratch
https://github.com/kajakIYD/data-science-from-scratch
<br />
**Timeseries analysis**
<br />
GRU/LSTM, RNN, MLP, SARIMA...
https://github.com/kajakIYD/sequences
<br />
## Open Source Contributions
See my Issue at IoT Edge: https://github.com/Azure/iotedge/issues/1815 </br>
Commit & PR at IoT Edge: https://github.com/Azure/iotedge/pull/2681 https://github.com/Azure/iotedge/pull/2681/commits/1ca932094f6164df5c9f578555fa3154191f8f63 </br>
Issue at VSCode/Anaconda: https://github.com/microsoft/vscode-python/issues/18436

## Other commercial projects 
### IT projects
**"MOLOS IoT - real-time machines monitoring"**
<br />
I was a pioneer in development of contentenerized applications used for acquisition of measurements from machines. I have made several Docker-IoTEdge containers:
  * Modbus data acquisition
  * IoT Hub container <br />

*Skills: Python, Docker, Azure Cloud[IoTEdge, IoT Hub], Modbus, AT-Commands*
<br />
**"MOLOS security - secure data transfer "**
<br />
Multithreaded applications used for secure data transfer and processes monitoring.
  * Dispatcher - multithreading, stable, configurable via SSL-TCP connection (also by GUI!) process monitoring
  * Sink - multithreading, multiclient, TCP Server, used for sending messages to PostgreSQL <br />
  * EventSender - multithreading, multiclient, TCP Server, directory monitor, used for sending alarms and critical events to PostgreSQL/SCADA systems/AzureCloud <br />
  * ChannelMonitor - multithreading, multiclient, TCP Server, used for serving data to Zabbix (a'la Graphana, but less common :)) <br />
  * ModbusSink - multithreading, multiclient, TCP Server, used for aggregation data from many Modbus Slaves and serving as single ModbusSlave <br />

*Skills: Python, Threading, TCP-Client-Server, PostgreSQL, Azure Cloud, Process management in Linux/Windows, pyModbus*
<br />
**"Adaptive Machine Vision"**
<br />
The biggest project I have been involved into. My main responsibilities are:
  * Development of highly efficient and stable algorithms for image processing.
  * A little bit of unit testing and documentation writing - mainly for algorithms I have developed. <br />

Example algorithms I have already developed are: ImageProjection::Median, JoinImages, SplitSegment, ReplaceInArray<Generic>.
<br />
*Skills: C++, GTest*
<br />
**"AuditHelper"**
<br />
Application for optimal multiworker scheduling. Maintenance only.
<br />
*Skills: C#, EntityFramework, ASP.NET*
<br />
**"Migrating Tool SD"** 
<br />
Application used for users files migration. Developed and maintenanced fully by myself.
<br />
*Skills: C#, WPF*
<br />
**"Trackingster"**
<br />
Application used for measuring time of specified tasks of company workers.  Development and maintenance.
<br />
*Skills: C#, WPF*
<br />
**Binary state veryfication**
<br />
.dll created for checking if .exe and other .dll files created by KAMSOFT are obfuscated and if binaries was created using .NET technology. I have created that .dll as a part of more complex project in cooperation with my colleague.
<br />
*Skills: C#*
<br />
**"BEFSQC"**
<br />
Application used for accountancy automation. Development and maintenance.
<br />
*Skills: C#, WPF, iTextSharp*
<br />
**"Time Tracking"**
<br />
Application used for measuring time of specified tasks of company workers. Older version of Trackster. Development and maintenance.
<br />
*Skills: C#, WPF*
<br />
**"Tamee Tiger"**
<br />
Application used for accountancy automation. Maintenance only.
<br />
*Skills: C#, WPF, Selenium*
<br />
**"Highlight tool"**
<br />
Script used in Adobe Acrobat for accountancy automation. Development and maintenance.
<br />
*Skills: C#, JavaScript, Adobe Acrobat API*
<br />
**"Tickmark Calculator"**
<br />
Script used in Adobe Acrobat for acquiring statistics from financial statements. Development and maintenance.
<br />
*Skills: JavaScript, Adobe Acrobat API*
<br />
**"Remove Green Stamps"**
<br />
Script used in Adobe Acrobat for accountancy automation. Development and maintenance.
<br />
*Skills: JavaScript, Adobe Acrobat API*
<br />
**"Gaap Dammit"**
<br />
Application used for accountancy automation. Development and maintenance.
<br />
*Skills: C#, WPF*

### Projects for automotive
**Laser welding diagnostic interface**
<br />
*Skills: Arduino, electronics*
<br />
**Doors station production flow improvement**
<br />
Documentation available as *.pdf* file.
<br />
*Skills: PLC, FANUC robots control* 
<br />
**Production flow simulation at Body Department**
<br />
Documentation available as *.pdf* file.
<br />
*Skills: Tecnomatix Plant Simulation, programming in SimTalk, bottlenecks detection, mathematical modeling*
<br />
**SharePoint programming and administration**
<br />
*Skills: SharePoint Designer, workflows programming*
<br />
**Factory layout update**
<br />
*Skills: AutoCAD*
## GameDev - RPG: GemPrisoners(Box2D + SFML)
Project developed with @kreeaq and @PiotrBatko
More details at:
https://bitbucket.org/projektpss/gemprisoners/branches/

## Pottery Factory BeagleBone+MSP430 version
Documentation available soon as *.pdf* file. Git repository: Pottery-Factory.
<br />
*Skills: C, C++, QtCreator, Linux, BeagleBone, MSP430*

## Pottery Factory EVK1100 + freeRTOS version
Documentation available as *.pdf* file. Git repository: https://github.com/kreeaq/avr_RTOS
*Skills: C, C++, QtCreator, freeRTOS, electronics*

## SmartRoom web version 
Documentation available as *.pdf* file.  
*Skills: C, C#, PHP, Joomla*

## SmartRoom LabVIEW version
Documentation available as *.pdf* file.  
*Skills: LabVIEW (CLAD certificate), C*
