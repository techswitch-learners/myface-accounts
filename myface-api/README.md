# MyFace

## Introduction
The is the API for the MyFace Application.
Most of the endpoints are CRUD like, with a few exceptions for making it easier to create feeds of posts.

The application is written in C# with .NET Core, and uses ASP.NET Core, Entity Framework Core and a SQLite Database.

## Getting started
This _should_ just be a case of running `dotnet run` in the terminal.

Entity Framework will automatically generate the database for you, and it is populated in code (see Data).
If you need to trigger the database to be recreated, the easiest way is just to delete the `myface.db` file.