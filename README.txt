Pre-requisites: Connected to VPN and have access to REST Server

Step1: Open command prompt and navigate to the RESTFramework folder. 
Step2: Run below command to open Jmeter with properties for base url and other config details. If you wish to create multiple property file please add '-q' switch to load the properties for your test. Please commit all your property files to the config folder
Step 3: Save GeneralTest.jmx as deired Test name. 


-----------------
commands
-----------------
To load Jmeter in GUI mode:
>apache-jmeter-2.11\bin\jmeter.bat -q config\config.properties -t common\GeneralTest.jmx

To run jmeter headless mode: 
>apache-jmeter-2.11\bin\jmeter.bat -q config\config.properties -t common\GeneralTest.jmx -n 

To be updated.

1. How to add Requests?


2. How to 


