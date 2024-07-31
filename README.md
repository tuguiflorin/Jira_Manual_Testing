<h1 align="center">Twitter social media platform</h1>
<h1 align="center">-Test Plan-</h1>


### Revision History
| Date   |      Description      |  Author |  Comments |
|----------|:-------------:|------:|------:|
| 01.05.2024 |  Test Plan Twitter Version 10.50 | Tugui Mihai Florin | Twitter Version 10.50 |
| 03.08.2024 |    Added more details for 2.4 Test Implementation    |   Ioana Popescu |   Test Plan version 1.1 |

Table of Content:
1. Introduction
   - 1.1 Project objective
   - 1.2 Functionalities in scope
   - 1.3 Functionalities and tests out of scope
2. Test process
   - 2.1	Test planning
   - 2.2	Test analysis
   - 2.3	Test design
   - 2.4	Test implementation
   - 2.5	Test execution
   - 2.5	Test execution
   - 2.6	Test closure
   - 2.7	Test monitoring and control
3. Test deliverables
   - 3.1	Test plan
   - 3.2 Test conditions
   - 3.3	Test cases
   - 3.4	 Daily test summary reports
   - 3.5	Traceability matrix
   - 3.6	Test case results
   - 3.7	 Bugs report
   - 3.8	Test completion report
4. Schedule
<p><br>   
1. Introduction

This document describes the test plan for the Twitter integration feature. The goal is to ensure that the integration works seamlessly, allowing users to authenticate, post tweets, read tweets, and handle errors appropriately.

1.1 Project Objective

This test plan details the methods and approaches used to verify the functionality, security, and performance of the Twitter social media platform. The objective is to ensure the quality and reliability of the application by identifying and correcting errors.

Application under test:
[Twitter social media platform](https://x.com/i/flow/login)

Application documentation:
[Twitter API Documentation | Docs | Twitter Developer Platform (x.com)](https://developer.x.com/en/docs/twitter-api)

 1.2 Functionalities in scope
 
 For this version of the application the functionalities in the scope of testing are: 
-	Functionality
-	User interface (UI)
-	Security
-	Performance
-	Compatibility
-	Usability
-	For the testing process we will use: functional testing, positive testing, negative testing, regression testing and retesting.
-	The testing process will be focused on the following browsers: Chrome and Mozilla latest versions. 

1.3 Functionalities and tests out of scope
-	Non-functional testing like performance, stress, volume testing are out of scope
-	Test process for mobile application is out of scope
-	Other browsers except Chrome and Mozilla are out of scope
-	Automation testing is beyond scope 

2.	Test process

2.1  Test planning
Roles and responsibilities
| Role 1      | Tugui Mihai Florin - Test lead - Will monitor the testing process      |
| -------------- | -------------- |
| Role 2  | Ana Gavrila- Junior Tester - Will write the test conditions and test cases  |
| Role 3  | Boier Alexandru - Senior Tester - Will create the test conditions and test cases for Registration, Authentication and Password Reset  |
| Role 4  | Giurgiu Alexandru - Tester - Will execute the test cases for Registration, authentication and password reset and report the defects  |
| Role 5  | Alina Maria - Senior Tester -  Will execute the test cases for Video Posts, Notifications, Comments and report the defects  |

Entry criteria:
-	Functional business specifications are defined 
-	Roles and responsabilities have been allocated 
-	The test environment is up and running
-	Initial risks were identified 
-	The test plan was created and test process is detailed for the functionalities in scope 

Exit criteria:
-	All the test cases were executed 
-	90% of test cases are passed 
-	The remaining defects/bugs have low severity and low priority 
-	The project deadline was reached 
-	The project budget was reached 

Project risks:
-	The team does not have the proper knowledge and experience for web testing 
-	Test environment not working 
-	Short/tight deadlines 
-	Due to the company changes we might have levers 

Product risks:
-	Taking into account that Admin is  the only module in scope of testing, the rest of them will be at risk of not fulfilling the user needs
-	Validation constraints on some of the fields might be too restrictive

2.2 Test analysis 
-	Analyze the business requirements to make sure that we have all the details for creating the test conditions 
-	Write test conditions that will be tested in our testing process 

2.3 Test design
- In this phase we will create the test cases based on the previously defined test conditions 

2.4 Test implementation
-	Verify if the test environment is up and running 
-	Access to the test environment is given: valid username and valid password 
-	Create test suites (Test cycles)
-	We prioritize the test cases based on risks and business priority 

2.5 Test execution
-	All functional test cases cases created in Test Design phase are executed and we set the test case status(passed/failed)
-	For the test cases failed we will raise defects 
-	Regression pack has been run 
-	Retesting for the bugs that are fixed by the developers to validate that they issues are not reproduced 

2.6 Test closure
-	Analyze if the exit criteria were met and the testing process can be closed
-	Generate the traceability matrix 
-	Generate the test completion report 

2.7 Test monitoring and control 
- In this phase various periodic reports will be generated to reflect the current status of the testing process. In case of major problems, control measures could be taken. 

3.	Test deliverables

The following test deliverables will be provided by the end of the testing process and sent to the stakeholders in order to create the basis of informed decision:

-	Test plan 
-	Test conditions 
-	Test cases
-	Daily test summary report
-	Traceability matrix
-	Test case results
-	Bugs report
-	Test completion report

3.1 Test plan 

[Twitter social media platform Test Plan](https://github.com/tuguiflorin/Jira_Manual_Testing/blob/main/Test_Plan.pdf)

3.2 Test conditions
- Functional Test Conditions:
    - Login Functionality: Verify that the user can log in with valid credentials.
    - Data Entry: Ensure that the user can successfully add a new record to the database.
    - Search Feature: Confirm that the search functionality returns accurate results based on user input.
- Non-Functional Test Conditions:
    - Performance: Test the application’s response time under heavy load.
    - Security: Validate that unauthorized users cannot access restricted areas of the application.
    - Usability: Ensure that the user interface is intuitive and easy to navigate.
- Boundary Conditions:
    - Boundary Values: Test input fields with boundary values, such as maximum and minimum limits.
    - Edge Cases: Verify the system's behavior with edge cases, like empty inputs or extremely large inputs.
- Negative Test Conditions:
    - Invalid data entry and error handling check.

3.3 Test cases




4. Schedule
-	The testing process will take place over a period of 1.5 months and will involve all the activities defined in the previous section
-	All the resources will be adapted accordingly in case new testing resources are detected as necessary



 
