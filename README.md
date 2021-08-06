## Title

By Gurshan Kaile

## Description 

This project is a Website that lets a user add and view Stylists and their clients

## Technologies

* C#
* ASP.NET 5.0
* ASP.NET MVC
* MySQL Workbench
* Entity Framework Core
* Razor
* NuGet

## Instructions for Installing C# and .NET: 

* Windows Download  [https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-5.0.102-windows-x64-installer](64-bit .NET 5 SDK)

* MacOs: Download  [https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-5.0.100-macos-x64-installer](.NET 5 SDK)

* Download or Clone the repo to your local machine

* Navigate to the 'HairSalon' Directory, run ``` dotnet restore ``` to install dependencies

* Download MySQL Database

* Create your own version of the MySQL database by importing the ``` gurshan_kaile.spl ``` file from the repo using MySQL WorkBench

* Create an appsetting.JSON file in the main 'HairSalon' Directory and add the following code 

```
{
  "ConnectionStrings":
  {
    "DefaultConnection": "Server=localhost;Port=3306;database={first_last};uid={YOUR_USERNAME_NAME};pwd={YOUR_PASSWORD};"
  }
}

```

* Replace your ``` first_last ``` ``` YOUR_USERNAME_NAME ``` and ``` YOUR_PASSWORD ``` with your information. Don't include curly brackets after inputting your information. 

* Navigate to the 'HairSalon' Directory in terminal, run ``` dotnet run ``` in order to see the website in a browser.


## Bugs 

* No known bugs

## License 

__MIT__ 

Copyright (c) 2021 Gurshan Kaile

## Contact Information 

gurshakaile206@gmail.com 





