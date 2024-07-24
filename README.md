<div align="center">
  <img src="img/icon.png" alt="FullCalendar .Net Core MVC Appointment System Project" width="100" height="100">
</div>

## <img src="img/html.gif" width="25" style="margin-bottom: -5px;"> About The Project

In this project, the focus is on the effective use of the FullCalendar library. In addition, the Dental Hospital Appointment Information System, developed using .Net Core 3.1 MVC, provides the opportunity to practice how to use FullCalendar in projects.

In this project, an approach has been adopted in which, in addition to theoretical knowledge, each concept is put into practice and the most accurate usage methods are shared. You can use this documentation to understand how to use FullCalendar in projects and gain the necessary skills to develop your project. Hope it is useful, good luck!

```html
<!-- HTML Meta Tags -->
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
<meta name="author" content="Sinan Özçelik">
<meta name="publisher" content="VS 2023">
<!-- Web Site Title -->
<title>FullCalendar .Net Core MVC Appointment System Project</title>
<!-- Meta Open Graph -->
<meta property="og:locale" content="en_US" />
<meta property="og:type" content="website" />
<meta property="og:title" content="Homepage" />
<meta property="og:url" content="FullCalendar .Net Core MVC Appointment System Project" />
<meta property="og:site_name" content="FullCalendar .Net Core MVC Appointment System Project" />
```

## <img src="img/genius.gif" width ="25" style="margin-bottom: -5px;"> Features

- [x] Calendar Integration
- [x] Using Javascript, Jquery and Ajax
- [x] .Net Core 3.1 MVC
- [x] CRUD Operations
- [x] Entity Framework
- [x] Migrations
- [x] .Net Core Identity
- [x] Scaffolding

## <img src="img/code.webp" width ="25" style="margin-bottom: -5px;"> Build With

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![javascript](https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Sever-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)
![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white)

## <img src="img/visual-studio.gif" width ="25" style="margin-bottom: -5px;"> Installation

1. Check the database connection on the appsetting.json file. Customize the database connection path here according to your own computer. By default the database name is DentistDB.

   ```json
   {
      "ConnectionStrings": {
         "DefaultConnection": "Server=localhost\\sqlexpress; Database=DentistDB; Integrated Security=True;"
      },
      "Logging": {
         "LogLevel": {
            "Default": "Information",
            "Microsoft": "Warning",
            "Microsoft.Hosting.Lifetime": "Information"
         }
      },
      "AllowedHosts": "*"
      }
   ```
2. Type the add-migration command via the Package Manager Console.
   
   ```
   add-migration DbCreateFirst
   ```
3. After the migration process is completed, type update-database via the Package Manager Console.
   
   ```
   update-database
   ```

## 💻 Project View

![FullCalendar .Net Core MVC Appointment System Project](img/1.png)

![FullCalendar .Net Core MVC Appointment System Project](img/2.png)

## <img src="img/whatsapp.gif" width="30" style="margin-bottom: -5px;"> Contact Information

You can reach out to me using the following contact details:

[![Email](https://img.shields.io/badge/Email-info%40sinanozcelik.com-brightgreen)](mailto:info@sinanozcelik.com)

[![Website](https://img.shields.io/badge/Website-sinanozcelik.com-blue)](https://sinanozcelik.com)

I'm always open to development and collaboration. Feel free to reach out to me!