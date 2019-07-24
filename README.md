# Workshop: Dockerize a .NET Core application

## Introduction
 This workshop demonstrates how to dockerize an ASP.NET Core application. The application will be a REST Store Book Api integrated to a MongoDb. The REST Api and MongoDb will be docker containers.

 ## Why build ASP.NET Core + Docker?
- Open-source
- Develop and run your ASP.NET Core apps cross-platform on Windows, MacOS, and Linux.
- Great for modern cloud-based apps, such as web apps, IoT apps, and mobile backends.
- ASP.NET Core apps can run on .NET Core or on the full .NET Framework.
- Modular components with minimal overhead retain flexibility while constructing your solutions.

## Prerequisites
- Install Visual Studio (Mac OS / Linux / Windows).
- Install Docker Desktop. 

## How to use it
- Download or clone the project.
- Run the following command `docker build -t dotnetcoredocker .`
- Run `docker-compose up` command.