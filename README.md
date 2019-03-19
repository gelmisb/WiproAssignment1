# Wipro Assignment 1

## This is a small web application with jQuery and JS integration.

The form takes in different parameters and then it is manually validted using jQuery functionality. 
The steps the progress in executed:

1. User inputs details in order to register ;
2. A jQuery function is then excecuted, which collects all the information ;
3. The gathered information is then used within series of functions ;
4. First name and last name ar evalidated using simple JS Regex syntax ;
```
/^[a-zA-Z]+$/
```
5. Email has a different syntax that checks for certain symbols that would appropriate to an email format ;
```
/\S+@\S+\.\S+/
```
6. The date is then validated using Regex to see if there are numbers present in a correct date format ;
```
/^(?=.*?[1-9])[0-9()-]+$/
```
7. When all these become valid, the information is then stored (cached) within the browser's memory files for further processing  ; 
8. If all the data is valid then it is loaded within the ``` textarea ``` showing all the information ; 
