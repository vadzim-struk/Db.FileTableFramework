# Db.FileTableFramework

CLR Integration functions and stored procedures for SQL FileTables.

## Steps to Deploy
1. Download and build the solution. There are two solutions, one with only code and one in the Install directory that has an additional Windows Installer Xml (WIX) project. If you build the WIX project as Any CPU or X64, you get a 64 bit msi.
2. Use the msi installer to install on your database server. Alternately, you can manually copy the Rhyous.Db.FileTableFramework.dll file to a location on your database server.
3. Enable CLR integration on your database.
4. Run his SQL file against your database.
[Install Funcs and Procs.sql](https://github.com/rhyous/Db.FileTableFramework/blob/master/src/Rhyous.Db.FileTableFramework/Sql/Install%20Funcs%20and%20Procs.sql)

Done

## Functions Provided

- FileTableExists 
- DirectoryExists
- FileExists

## Stored Procedures Provided

- CreateFile
- CreateDirectory
