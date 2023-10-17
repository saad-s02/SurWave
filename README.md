# SurWave

Use Secrets.json to store and access connection string for SQLServer "connectionStringSql"

### Description<br/>
SurWave is a web application that allows administrators to create and manage surveys, users, and user groups. Users can log in with their email and password, and take the surveys assigned to them. The application is built with Angular and .NET 7, and uses a SQL database to store the data. <br/>

### Features<br/>
- Admin dashboard: Admins can create, edit, delete, and view surveys, users, and user groups. They can also assign surveys to user groups, and view the results of the surveys.<br/>
- User dashboard: Users can log in with their email and password, which are auto-generated by the the backend and sent to their email. They can view and take the surveys assigned to them, and see their progress and scores.<br/>
- Survey taker: Users can take the surveys in a user-friendly interface, with features such as timer, progress bar, skip logic, etc. They can also save their answers and resume later.<br/>
- Survey results: Admins can view the results of the surveys in various formats, such as pie charts and bar graphs. They can also export data to CSV.<br/>
- Survey Notifications: Users will be notfied by email when they are assigned to a new survey.<br/>

### Admin Login Info: <br/>
email : Administrator <br/>
password : Admin@123 <br/>

### User Login Info: <br/>
email : open.survey@hottempmail.cc <br/>
password : User@123 <br/>

### Database setup
- Run Survey_1.sql to Survey_11.sql <br/>
- Run Database_Reconstruction After that <br/> (comment out the Survey, Questions, Option table delete)
