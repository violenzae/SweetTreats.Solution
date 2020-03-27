# _Pierre's Sweet Treats_

#### _A web application that allows the user to add and view Flavors and Treat types to a SQL database with many-to-many relationships._

#### By _**Rachel Schieferstein**_

## Description

_This is a SQL database/C#-based web application that has an HTML UI. The user comes to a splash page which prompts them to view all types of treats or all types of flavors. From there, they can create an account, login and choose to add new items and then connect the different categories once they are created. Users that are not logged in cannot access CRUD functionality, but they can view everything. They can further drill down into individual flavor and treat details, which list which of the opposite category they are associated with. It also uses ASP.NET MVC, ASP.NET Identity, Razor, shared layouts, static files, branching logic, classes, methods, HTML helpers and auto-implemented properties._

## Setup/Installation Requirements


* _Clone or download from Github Repository._
* _Install .NET Core SDK_
* _Install MySQL and start and login to a local server._
* _Navigate the terminal in the "SweetTreats" directory in the project, and run "dotnet restore"_
* _Recreate the database by running the migration command "dotnet ef database update"_
* _In the terminal in the "SweetTreats" directory, type "dotnet run" and open http://localhost:5000/ in a web browser._

## Known Bugs

N/A

## Support and contact details

_If there are any questions, please contact me at violenza@gmail.com._

## Technologies Used

_This project was created using mySQL, ASP.NET Identity, Entity Framework 2.2.6, C#, ASP.NET MVC, Razor 2.2.0, CSS, Bootstrap 4.4.1 and HTML._

### License

*This software is licensed under the MIT license.*

Copyright (c) 2020 **_Rachel Schieferstein_**