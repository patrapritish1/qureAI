# qureAI

1. Unzip the file.
2. Once java_home and maven_home variables are set, command prompt and go to the project directory [jdk (version 8 or above) and maven should be setup on local machine]
3. enter command "mnv test"
this should trigger the tests, given the chromedriver version is compatible with the browser version. if not then please change the chromedriver version accordingly (path in project -- /E2EProject/src/main/java/resources/chromedriver.exe).

Note - if using eclipse ide after importing as a maven project please install testng plugin to run the testng.xml file as TestNG Suite
