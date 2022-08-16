# Dr. Sillystringz's Factory Machine Repair Tracker

#### By: Nick Tse

#### This project demonstrates use of the model-view-controller methodology, many-to-many relationships, and basic database usage with MySQL

## Technologies Used

* C#
* MSTest
* .NET 5 SDK
* ASP.NET Core
* Razor
* HTML
* MySQL
* Entity


## Description 

The project is a simple web application that allows a factory manager employed by the famous Dr. Sillystringsz keep track of their machine repairs. The homepage of the app at the root path (localhost:5000/) is a splash page welcoming the user and providing them with a link to a see machines or engineers, following which they may add, edit, or delete, or update which engineers are assigned to repair which machines. 

## Setup/Installation Requirements

* _Clone repository from GitHub_
* _Open your terminal and run the command $ git clone https://github.com/n-tse/SillystringszFactory.solution_
* _Using the command $ cd Factory, navigate to the Factory directory_
* _Run the command $ dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0_
* _Run the command $ dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2_
* _Within the Factory project directory, create a file called appsettings.json_
* _Add the following code to the new appsettings.json file: 
  {
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=sillystringsz_factory;uid=[YOUR-USERNAME-HERE];pwd=[YOUR-PASSWORD-HERE];"
    }
  }_
* _Run the command $ dotnet build_
* _Run the command $ dotnet run_
* _In your web browser, type "http://localhost:5000"_
* _The browser should now display the web application for the user to interact with_"

## Known Bugs

* no known bugs

## License

_MIT_

Copyright (c) _2022_ _Nick Tse_