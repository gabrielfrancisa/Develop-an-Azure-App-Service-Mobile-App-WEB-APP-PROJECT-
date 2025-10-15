# Develop-an-Azure-App-Service-Mobile-App-WEB-APP-PROJECT-
In this Project, we will create an Azure mobile app. 


## At the end of the project, we will develop the following:
1.	Created an Azure mobile app back end by using an App Service Web App.
2.	Tested connectivity to an Azure mobile client app.
3.	Verified the integration with an Azure SQL database.


## Steps
1.	First, I create an App Service Web App that will serve as the mobile app back end, and then configure a connection to a pre-existing Azure SQL database. 
2.	Next, I configure a development environment on an Azure virtual machine, and then deploy the mobile app back end by using Visual Studio. 
3.	Then you will test the mobile app by using the mobile device emulator in Visual Studio and Microsoft Edge.

## 1. Create an Azure mobile app back end by using a Web App
1.	Open Microsoft Edge, go to https://portal.azure.com, and sign in to the Azure portal 
Select the Type Text icon to type the associated text into the current field in the virtual machine.

>>> Create an Azure Web App by using the values in the following table. For any property that is not specified, use the default value.
## Property         ------------------------     	Value
1.	Resource Group:  gabriel-datalod55544381
2.	Name:	Gabriel66844381
3.	Unique default hostname:	Disabled
4.	Publish	Code
5.	Runtime stack:	ASP.NET V4.8
6.	Region:	East US
7.	Windows Plan: (East US) (new)	AppPlan1
8.	SKU and size:	Standard S1
Please look over the documentation on creating an Azure Web App.
>>> Open a new browser tab, go to the URL for the new mobile app at https://webappcreatedname.azurewebsites.net, and then verify that the default home page is displayed.
You should see a default home page in the mobile phone form factor.

## 2. Publish an Azure mobile app back end by using Visual Studio
1.	Open Microsoft Edge and then sign in 
2.	If prompted: Automatically sign in to all desktop apps and websites on this device?, select Yes, all apps. If Microsoft Edge closes unexpectedly, try starting it again.
3.	When Microsoft Edge launches successfully and opens the Bing home page on the internet, you have successfully initialised the browser for testing with Visual Studio. You may now close Microsoft Edge.
4.	Open Visual Studio 2022, and if prompted, select Continue without code, then sign in to your Microsoft Work or school account
5.	Wait for Visual Studio to initialise. It will take approximately 2-3 minutes for Visual Studio to open for the first time. Do not try to open Visual Studio more than once, as this will open multiple instances, which will slow things down, and then you will need to close the other instances later to release the memory used.
6.	Minimise the Visual Studio 2022 for later use

## Open Windows PowerShell, and then run the following commands to clone the GitHub repo that contains the Apache Cordova mobile app solution and verify the download:
## PowerShell
cd "c:\users\student\Documents\Visual Studio 2022\"
## PowerShell
git clone https://github.com/Azure-Samples/dotnet-sqldb-tutorial.git
## PowerShell
cd ./dotnet-sqldb-tutorial/
Close Windows PowerShell.
>>> Return to Visual Studio 2022, and then open the DotNetAppSqlDb Project/Solution in C:\Users\Student\Documents\Visual Studio 2022\dotnet-sqldb-tutorial.
>>> Wait for the Project to be opened.

## 3. Initiate a Publish operation for the DotNetAppSqlDb project to the existing ********1213 Azure App Service.
>>> You may need to unpin the RDP session Connection bar and then select the background to see the Build menu and the Publish option. You can also use Alt+B to open the Build menu.z8amfz9t.jpg
>>> Configure the publish profile to set the MyDbConnection connection string to Server=tcp:sql*******.database.windows.net,1433;Initial Catalog=sampledb;Persist Security Info=False;User ID=SQLAdmin;Password=AzureSQLPassw0rd!;MultipleActiveResultSets=False;Encrypt=True;TrustServerCertificate=False;Connection Timeout=30;, before proceeding to Publish the project.
>>> Wait for the publish operation to complete. You can ignore any vulnerability warnings. The publish operation will take approximately 2-3 minutes to complete. You should eventually see the home page for the mobile app in the browser. The mobile app's default home page

## If you receive a Runtime error, the code may not have fully published yet in the background. Runtime errorWait a minute and try to refresh the browser. You can also close the browser and select Publish again on the Publish page as the error may be cached. The home page for the mobile app may take an extra couple of minutes to load successfully for the first time.
>>> Create 2 new to-do items with Descriptions of the Reserve meeting room for the team meeting. and send a meeting invitation to team members by using the TodoList App.
>>> You should see the 2 new to-do items listed in the application. Todo list
>>> Close the Microsoft Edge browser window. Leave Visual Studio open for the next task.

## 4. Verify the SQL database entries
>>> Unable to retrieve content from https://raw.githubusercontent.com/LODSContent/project-V3-Framework/main/Templates/Sections/Toggle.md

>>> Open a new Microsoft Edge browser window, go to the Azure portal at https://portal.azure.com, and if necessary, sign in as a user.

>>> Connect to the Query Editor for the sampledb SQL database as SQLAdmin using AzureSQLPassw0rd! as the password, and then verify the entries in the Todoes table used to store data for the mobile app.

>>> Record the total number of items in the Todoes table in the following Total Number of Items text box, without leading or trailing spaces:

## Total Number of Items
>>> Record the number of the ID column for the first row in the following First ID text box, without leading or trailing spaces:

>>> First ID 

Congratulations.

