﻿<head>
	<h1>  GoStack - GoBarber API</h1>
</head>
<body>
	<p align="center">
  <img src="logogobarber.svg" width="150" title="Go Barber">
</p>
<div>
  
  ##  Description:  
   - This project is a barber shop system where services are scheduled, customers and service providers login and listings, notifications are also displayed and email is sent.
   
  ##  Running:  
   - Clone code - "git clone url_repository" .
   - Running "yarn" in path .
   - Create instances docker: 
        - `Postgres:` docker run --name INSTANCE_NAME -e POSTGRES_PASSWORD=PASS -p 5432:5432 -d postgres:11
        - `MongoDB:` docker run --name INSTANCE_NAME -p 27017:27017 -d -t mongo
        - `Redis:` docker run --name INSTANCE_NAME -p 6379:6379 -d -t redis:alpine
   - For better structuring of the code used, Eslint, Editor config and Prittier, installation of plugins in Vscode.
   
   - Create an .env file from .envexample
  
   ##  Technologies Used:
   - Express  
   - NodeMailer
   - AWS API
   - Multer
   - JWT
   - DotEnv
   - Bcrypt
   - Mongoose
   - TypeORM
   - Database: 
        - `Postgres` - Structured Data
        - `MongoDB`  - Unstructured data / notification control
        - `Redis`    - Queue control for sending email
   - Developer:
        - `Eslint`
        - `Prittier`
        - `Editor Config`
   
     
  
  ## Features:
  - Login/Create/Update User using JWT
  - Create/Liste/Delete Appointments
  - List/Update Notifications
  - Send Email Notifications
  - List Schedule provider
  - List Available hours
  - List Provider
  - Upload Avatar Image
   
</div>

</body>

<footer>
  <p>Mário Wessen - <a href="mailto:mariowessen@gmail.com">mariowessen@gmail.com</a></p>
</footer>
