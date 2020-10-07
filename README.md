## Project details
The overall goal of this project is to create an eCommerce website using microservice architecture. As a first step, I created a catalog API that displays products on the website. I have also performed simple CRUD operations on Catalog API.

## Technology used
- C#
- Web API using ASP.NET Core
- MongoDB
- Docker

## Prerequisite
You will need the following tools:
- Visual Studio 2019
- .Net Core 3.1 or later
- Docker Desktop

## Running the application
- Clone the repository
- Run the following command to the rood directory including the docker file

      docker-compose -f docker-compose.yml -f docker-compose.override.yml up –d

- Launch the catalog microservice -> http://localhost:8000/swagger/index.html
