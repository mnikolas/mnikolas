# mnikolas
TestActivity# Google Search TestA small tutorial task for selenium+testin relations used for testing google.com search# 

# How to use* 
Get project from github and place it to any location at your PC
* Navigate to the project's root folder* Perform command: mvn test# Configuration* Main configuration file is testng.xml which is located here: src\test\resources\testng.xml* You can perform initial setup of the test parameters like browser [chrome, firefox, ie], test suites to be executed and so on...# Test steps* Navigating to google.com and check page title* Verifying that search text area exists* Verifying that button "Search" exists* Performing search with google by pattern and checking results
