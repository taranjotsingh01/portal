# Interview portal
Clone this repo in your local system.
To run this project you have to install NodeJS (npm) and MySQL server on your machine.

## For Database 
Create a DB named InterviewDB, 
Add two tables "users", to hold data of the our interviewers and "interviews", to hold the data of the upcoming interviews.

CREATE TABLE users (
  name VARCHAR(100) NOT NULL,
  email_id VARCHAR(100) NOT NULL,
  PRIMARY KEY (email_id));
  
CREATE TABLE interviews (
  id INT NOT NULL AUTO_INCREMENT,
  email1 VARCHAR(100) NOT NULL,
  email2 VARCHAR(100) NOT NULL,
  startTime DATETIME NOT NULL,
  endTime DATETIME NOT NULL,
  PRIMARY KEY (id));
  
  ## For mail Service 
  make changes in mailService.js, Add your email id and password (the mail id from where you will send the mail).
 
 ## For run 
 Run nodemon app.js in terminal.
 
  
