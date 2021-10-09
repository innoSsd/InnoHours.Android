# InnoHours.Android
# Description
This is a mobile application that simplifies the interaction of students and professors with office. It will help students to enrol for office hours to professors via a mobile device. This mobile app could make lifes of students and professors easier.

# Contents
[Development Plan](#Development_Plan)    
  * 2.1. [Business Goal](#Business_Goal)  
  * 2.2. [Roles and responsibilities](#Roles_and_resposibilities)  
  * 2.3. [Project Glossary](#Project_Glossary)  
  * 2.4. [Technical Stack](#Technical_Stack)  
  * 2.5. [Requirement Analysis and Specifications](#Requirement_Analysis_and_Specifications)    
    - 2.5.1. [Features](#Features)  
    - 2.5.2. [User Stories](#User_Stories)
    - 2.5.3. [Non-functional requirements](#Non-functional_requirements)      
  * 2.6. [Architecture](#Architecture)  
  * 2.7. [Prototype Screenshots](#Prototype_Screenshots)   
  * 2.8 [Milestone](#Milestone)  
 
[Authors](#Authors)

# Development Plan <a name="Development_Plan"></a>
## Business Goal <a name= "Business_Goal"></a>
Build an application for mobile platforms where students can easily see professor’s available office hours and remotely apply for them; professors can specify the office hours that students can apply to. In addition, everyone can see their actual schedule in a handy way.

## Roles and resposibilities <a name= "Roles_and_resposibilities"></a>
| Stakeholder's Name     | Roles                                                        | Responsibilities                                                                |
|------------------------|--------------------------------------------------------------|---------------------------------------------------------------------------------|
| Developer              | Develop apps and server                                      |  Backend, developing app features                                               |
| Designer               | Design the app                                               | App sketches, creating app design                                               |
| User                   | Test features, create a schedule and use other features      | Use application                                                                 |
| Owner                  | See users activity                                           | Moderate user activity, report bugs to developers, check for forbidden activity |

## Project Glossary <a name= "Project_Glossary"></a>  
* Backend (server) - the part of code that is not visible to end user
* Frontend (application) - the part of the service responsible for the functioning of its internal part which which end user directly interacts
* Developer - a specialist who develops backend and frontend
* Designer - a specialist who develops the design of applications for Android operating system
* User - an assistance in integrating testing features, creating a schedule and using other features
* Owner - an individual who moderate user activity, report bugs to developers, check for forbidden activity
* Schedule - a plan for carrying out classes, giving lists of intended events and times
* Office hours - hours that the professor could spend to additionally explain material and answer the questions for individual students

## Technical Stack <a name= "Technical_Stack"></a>
* Kotlin programming language  

## Requirement Analysis and Specifications <a name="Requirement_Analysis_and_Specifications"></a>
### Features <a name="Features"></a>
|ID |User Story Title              |Priority|
|---|------------------------------|--------|
| 1 |   Scheduling                 |low     |
| 2 |Registration and authorization|hight   |
| 3 |Push-notifications            |medium  |
|4.1|Create office hours           |hight   |
|4.2|Apply for office hours        |hight   |
| 5 |Filtering data for users      |low     |

### User Stories <a name="User_Stories"></a>
|User Type  |User Story Title              |User Stories|
|---|------------------------------|--------|
| Student, Professor |   Filtering data for users                 |As an authorized user, I want to see a filtered schedule for me only in the more user-friendly interface|
| Student, Professor |Scheduling|As an unauthorized user I want to see the entire schedule|
| Student |Apply for office hours            |As an authorized user I want to apply to the professor’s office hours, if the professor allows <br /> As an authorized user I want to send a request for personal office hours to the professor|
| Student, Professor |Push-notifications|As an authorized user I want to receive notifications about classes, office hours and can set them|
| Student, Professor |Registration and authorization           |As a user I can register into the application by entering my email password and confirming the password <br />  As a user, I want to login in by entering my nickname/mail and password|
| Professor |Create office hours        |As a user, I want to create a schedule for all office hours of my courses that will be visible to all students <br /> As a user, I want to see list of student that was requested for my office hours <br /> As a user, I want to have the possibility to decline requests|
| Student, Professor |Scheduling      |As an authorized user I want to see the entire schedule of other users|
| Student, Professor |Push-notifications|As an authorized user I want to receive notifications about classes, office hours and can set them|
| Student, Professor |Registration and authorization|As a user I can register into the application by entering my email password and confirming the password <br /> As a user I want to login in by entering my nickname/mail and password <br /> As a user I want to request professor permissions|

### Non-functional requirements <a name="Non-functional_requirements"></a>
* The registration confirmation email message must be delivered within 5 minutes   
* The office hours slot must have maximum available slots for students   
* The schedule may be filtered by grade, group and visualized more readable way   
* Unauthorized users should not have an opportunity to apply for office hours   


## Architecture <a name="Architecture"></a>
We use MVC for web server and MVVM for android application as it is the most popular approach
[Link to the board (2 pages)](https://app.diagrams.net/#G1zkhNU5fc5XHF-9UQ4puewK5DyX-7-eoU)


## Prototype Screenshots <a name="Prototype_Screenshots"></a>
![main_menu](https://user-images.githubusercontent.com/69847242/136660988-f6cd775c-5e88-4a54-89fc-7cc1cd996e87.PNG)    
![image](https://user-images.githubusercontent.com/69847242/136661224-0f2ffe27-a52d-4ca3-8172-7877d22b3f38.png)   
![image](https://user-images.githubusercontent.com/69847242/136661134-7debe4a9-4618-45b1-944a-ac985e8dafdc.png)   
![image](https://user-images.githubusercontent.com/69847242/136661052-90ac5e9a-1e94-4895-81fc-adb47c5a0bca.png)   
![image](https://user-images.githubusercontent.com/69847242/136661103-f74836a5-31bf-41a3-a315-9538a415c15a.png)   
  

## Milestone <a name="Milestone"></a>
|Milestone|Timeline                     |Status     |
|---------|-----------------------------|-----------|
|Alpha    |31/08/2021 - 06/09/2021      |Done       |
|Beta     |18/09/2021 - 25/09/2021	|Done       |
|Gamma    |04/10/2021 - 09/10/2021	|In progress|



## Authors <a name="Authors"></a> 
Designer - Alisa Ivanova   
App developers - Alexey Smolyakov, Ilnur Davletshin   
Server Developer - Arina Kilmukhametova   


