# Deploy a Flask app service

<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/101-webapp-linux-flask/PublicLastTestDate.svg" />&nbsp;
<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/101-webapp-linux-flask/PublicDeployment.svg" />&nbsp;

<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/101-webapp-linux-flask/FairfaxLastTestDate.svg" />&nbsp;
<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/101-webapp-linux-flask/FairfaxDeployment.svg" />&nbsp;

<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/101-webapp-linux-flask/BestPracticeResult.svg" />&nbsp;
<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/101-webapp-linux-flask/CredScanResult.svg" />&nbsp;

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-webapp-linux-flask%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-webapp-linux-flask%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png"/>
</a>

This template deploys a web app with Python support to let us to upload a Flask app. The web app with Python is an app service that allow you to deploy your Django website. This will deploy a free tier Linux App Service Plan where you will host your App Service.

If you are new to Azure App Service, see:

- [Azure App Service](https://azure.microsoft.com/en-us/services/app-service/web/)
- [Template reference](https://docs.microsoft.com/es-es/azure/templates/microsoft.web/allversions)
- [Quickstart templates](https://azure.microsoft.com/es-es/resources/templates/?resourceType=Microsoft.Compute&pageNumber=1&sort=Popular&term=web+apps)

If you are new to template deployment, see:

[Azure Resource Manager documentation](https://docs.microsoft.com/azure/azure-resource-manager/)

## Prerequisites

If you have already a Linux App Service Plan, you will have to deploy the new web app into the same resource group that the other web app is. That's because Student accounts has a limit of only 1 free tier Linux app service plan.

`Tags: Azure4Student, appServices , flask, linux, Beginner`
