# ODBC-in-.NET
Easy example of how to connect a local database running on something like [UniServer](http://www.uniformserver.com/) to a Windows application using ODBC drivers in either VB.NET or C# (Example written in VB because this was part of an example project originally which needed to be in VB). All interaction with the Database is done using BackgroundWorkers to take the load off the UI thread.

Local SQL Database used : [SqlYog](https://www.webyog.com/product/sqlyog)

 Allows for the interaction and execution of SQL commands using `System.Data.Odbc`'s namespace, database, table, field names are of course dependent on your database, so make sure to change them before attempting to use it.

UI is made in WPF using [MahApps](mahapps.com) and [Material Design in XAML](http://materialdesigninxaml.net/) 

![Login Demo](https://github.com/peaches6/ODBC-in-.NET/blob/master/media/loginDemo.PNG?raw=true)
