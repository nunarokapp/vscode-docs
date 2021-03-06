---
Order: 1
Area: appservicetools
TOCTitle: Getting started
PageTitle: Node.js Deployment with Visual Studio Code
MetaDescription: Node.js Deployment to Azure App Services with Visual Studio Code
DateApproved: 12/18/2017
---
# Deploy to Azure using App Service

This tutorial walks you through deploying a Node.js application to Azure using the [Azure App Service](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azureappservice) extension. You'll be able to deploy to Azure on Linux in a matter of minutes from Visual Studio Code.

## Prerequisites

If you don't have an Azure account, [sign up today](https://azure.microsoft.com/en-us/free/?utm_source=campaign&utm_campaign=vscode-tutorial-node-git&mktingSource=vscode-tutorial-node-git) for a free 30-day account with $200 in Azure credits to try out any combination of services.

You need [Visual Studio Code](https://code.visualstudio.com/) installed along with [Node.js and npm](https://nodejs.org/en/download), the Node.js package manager.

## Install the extension

The Azure App Service extension is used to create, manage, and deploy Linux Web Apps on the Azure PaaS.

> <a class="tutorial-install-extension-btn" href="vscode:extension/ms-azuretools.vscode-azureappservice">Install the Azure App Service extension</a>

## Sign in

Once the extension is installed, log into your Azure account - in the **AZURE APP SERVICE** explorer, click **Sign in to Azure...** and follow the instructions.

![sign in to Azure](images/app-service-extension/sign-in.png)

## Prerequisite check

Before we continue, ensure that you have all the prerequisites installed and configured.

In VS Code, you should see your Azure email address in the Status Bar and your subscription in the **AZURE APP SERVICE** explorer.

----

<a class="tutorial-next-btn" href="/tutorials/app-service-extension/create-app">I've installed the Azure Extension</a>
<a class="tutorial-feedback-btn" onclick="reportIssue('node-deployment-azureappservice', 'getting-started')" href="javascript:void(0)">I ran into an issue</a>
