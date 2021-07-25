# covid-patient-managment
This is a java project designed for displaying hospital list and total number of beds available in respective hospitals and to admit
the patient in the selected hospital
This is a java project designed during my second year of engineering as a part of the oop JAVA course @NIE Mysore
CONCEPTS ILLUSTRATED :
Abstraction -classes
Scope and lifetime of variables
Declaring objects
Instance Variables of different data types
Constructors/method.
'this' Keyword
Inheritence
Overloading 
Overriding
Objects as parameters
Access Control mechanism
Use of 'Super'
Packages
Exception Handling
Creation of thread
working: As we run the programe it ask the user to enter login id and password if the user enter correct userid and password which has been set already in the programe system 
allow user to get log in to the sytem otherwise it will show message as invlaid login id or password.
After user succesfuly enter the correct login details system show menu bar containing options 
1)hospital list 
2)bed availability list
3)admit patient
4)system existing
user can select the option which ever they want among the 4 choices given
if the user selects option 1 it display the list of all the hospital along with hospital id 
if the user select option 2 it shows the list of beds available in each hospital along with hospital name 
if the user select option 3 he can admit patient .first user has to select in which hospital does the patient as to be admitted 
after user enter the hospital id it will display the hospital name then user as to enter patient name and hospital name which he as selected
and the patient will be admitted into the respective hospital
if the user as to admit another patient then they as to press key 1 and repeat same procedure as mentioned above 
if not they have to press key other than 1
if the user selects option 4 the system will exit and programe will stop
project has been done using core java concepts.my project totaly consists of 2 packages namely Bed_allocation and Hospitalmanagment
bed_allocation package consists of classes :login_info,login,bed_info,admit_patient,repository,report service,data_entry and excecution
Hospitalmanagment consists of class : hospital
