Assignment 2

Program Name : SanketBookStore
Program Purpose : Create a MVC App  
Program Author : Sanketkumar Arvindbhai Patel 
Program  Date :  2021-11-03 



steps for the program :

1. Read and understand the question for assignment  
2. Create an asp.net web app
3. Select the Asp.net core model view controller
4. change the startup.cs file 
5. Check the public IActionResult interface
6. Check the debugging 
7. Go to Bootswatch.com and select the theme, I have selected Cyborg theme and download it and paste it to the local server. Also, Go to wwwroot and replace
    the existing site.css file found in the main css folder and change file name bootstrap.min.css to bootstrap.css.
8. Unfortunately, I got the error. the theme is not working on it properly. 
9. Move forward to the next step, go to the _Layout.cshtml page the additional stylesheets and scripts from the CSS_JS.txt file 
10. Change the nav-class from navbar-light to navbar dark and bg-white to bg-primary. Also, remove the text-dark from the nav bar. 
11. add additonal Css and Js files which provide in the folder
12. Go to the _Layout.cshtml change the dropdown menu setting, add the code from the bootstrap files. Then, change the name of the dropdown to Content Management. 
13. Got the error and stuck ...... 
14 I got the error : Severity	Code	Description	Project	File	Line	Suppression State
Error	CS0246	The type or namespace name 'ErrorViewModel' could not be found (are you missing a using directive or an assembly reference?)	SanketBookStore	C:\Users\W0776059\source\repos\SanketBookStore\SanketBookStore\SanketBookStore\Controllers\HomeController.cs  , Severity	Code	Description	Project	File	Line	Suppression State
Error	CS0433	The type 'IdentityUser' exists in both 'Identity.Stores, Version=1.2.7.0, Culture=neutral, PublicKeyToken=adb9793829ddae60' and 'Microsoft.Extensions.Identity.Stores, Version=5.0.0.0, Culture=neutral, PublicKeyToken=adb9793829ddae60'	SanketBookStore	C:\Users\W0776059\source\repos\SanketBookStore\SanketBookStore\SanketBookStore\Startup.cs	36	Active
Severity	Code	Description	Project	File	Line	Suppression State
Warning		Unexpected comma after the last object member.	SanketBookStore	C:\Users\W0776059\source\repos\SanketBookStore\SanketBookStore\SanketBookStore\Properties\launchSettings.json	6	 
Got the error and could not run the app. the error is : 
Severity	Code	Description	Project	File	Line	Suppression State
Error	CS0433	The type 'IdentityUser' exists in both 'Identity.Stores, Version=1.2.7.0, Culture=neutral, PublicKeyToken=adb9793829ddae60' and 'Microsoft.Extensions.Identity.Stores, Version=5.0.0.0, Culture=neutral, PublicKeyToken=adb9793829ddae60'	SanketBookStore	C:\Users\W0776059\source\repos\SanketBookStore\SanketBookStore\SanketBookStore\Startup.cs	36	Active
How i resolved: removed Identity.Store, made sure the Microsoft.Extensions.Identity.Stores was present in the project(s).
Conclusion - duplication resolved...
