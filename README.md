# Azure App Service Mobile Apps generator

[Yeoman](http://yeoman.io) generator to scaffold an [Azure App Service Mobile App].

## Getting Started

- Install: `npm install -g yo generator-azure-mobile-apps`
- Run: `mkdir myproject; cd myproject; yo azure-mobile-apps`

## Configuring an Azure Mobile Apps project

This project is designed to run inside [Azure App Service].  You will need to hook up a SQL
Azure database and [deploy your app] to Azure.

[Azure App Service]: https://azure.microsoft.com/en-us/documentation/services/app-service/
[Azure App Service Mobile App]: https://azure.microsoft.com/en-us/documentation/articles/app-service-mobile-node-backend-how-to-use-server-sdk/
[deploy your app]: https://azure.microsoft.com/en-us/documentation/articles/web-sites-deploy/

## What's included:

The scaffolding includes a complete Azure Mobile App with an associated ExpressJS app for a basic
web application.  The ExpressJS side of things includes transaction monitoring, static files, body
parser and compression.

In addition, basic web app tests are scaffolded out.

To run the web app after creation, use ```npm start```.  To run the tests, use ```npm test```.
