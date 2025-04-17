# Prerequisites
#####
- JDK 11
- Maven 3
- MySQL 8 

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
# Steps 
Windows

- To install helm
```
choco install kubernetes-helm
```
-  go to project folder and run command
```
helm create profilecharts
```
-  move the profilecharts folder to helm folder which you should create
```
mkdir helm
mv profilecharts helm/
```
-  Replace the default template with the project's yml file 
```
rm -rf helm/profilecharts/templates/*
cp kuberbetes/vpro-app/* helm/vprofilecharts/templates/
```
-  then you can run the workflow in Github Action 

