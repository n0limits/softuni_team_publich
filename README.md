# softuni_team_publich
Teamwork for quality assurance course of softuni.bg
Steps to do :
(everybody should write here)

Test Cases for Login Screen Page

 
This article explains test cases both negative and positive for the login screen. I’m taking example of gmail login screen. If you want you can take example of WordPress or yahoo login screen or any other of your choice. The positive and negative scenarios depends on the information given the requirement document. As we are testing gmail login screen we are limited to the application which is already published with limited set of information available to test. So our best approach is exploratory testing of the web app.

I’m laying down a process which you can follow in order to come up with a login screen test cases. First we’ll write the test requirements based on our exploratory testing observation and after tht we’ll write the test scenarios and then form the negative and positive test cases.  If you want to use existing testing templates and test cases, I suggest you check these templates out.

You can make use of following login screen of  
Test Requirements

Username should contain letter, number and period.
Username should not be left blank.
Username should not be more than 40 characters.
Username should not start with or contain any symbols.
Password should be at least 6 characters.
Password should contain combination of letter, numbers and symbols.
Password should not contain spaces and period.
Password should not be more than 40 characters.
Test Scenarios

Write down the test scenarios based on the following test types

User Interface

Here are some of the questions that can help you form test cases.

Where is the cursor focus in text area when you load the page
Does enter key works as a substitute for the sign in button action
Does username and password text field appears in order
Does remember me check box selected by default
Does the login page has register link for new users
Does the user interface look as per the design specification
Does login screen behaves responsively to mobile or tablet screen
Do the links on page remain active or are dead
Functionality

Here’s some general possible functionality scenarios.

Does the login form works successfully
Is logout link redirects back to the login screen is logout link functional
Does forgot password link works Does it redirect to valid password recovery page
Do forward and backward buttons work properly while logged in and also for logged out user
Does the form works similar in every popular browser
How errors are handled and displayed
Security

Security of the form is very crucial and you can use following scenarios to form your test cases.

Does textbox offers masking of characters in password field
Does masked characters allow deciphering if copied
Is it possible to copy and paste the password
is there any minimum password length
is the form giving away security information if the source is viewed
is the form vulnerable to SQL injection
Does form allows accessing pages without logging in
is URL manipulation allows access to members only area of mail
is multiple accounts from same IP but different browser allowed at the same time
are cookies allowed are they disabled or allowed to be edited
Once you go through these scenarios, you need to come up with following possible positive and negative test cases.

Positive test cases.

Enter valid username and password.
Click on forgot password link and retrieve the password for the username.
Click on register link and fill out the form and register username and password.
Use enter button after typing correct username and password.
Use tab to navigate from username textbox to password textbox and then to login button.
Negative test cases

Enter valid username and invalid password.
Enter valid password but invalid username.
Keep both fields blank and hit enter or click login button.
Keep username blank and enter password.
Keep password blank and enter username.
Enter username and password wrong.

