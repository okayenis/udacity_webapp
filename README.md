# Overview


## Agile Development with Azure

This project demonstrates an Agile approach to developing and deploying a Flask-based application using GitHub and Azure. The workflow integrates GitHub Actions and Azure Pipelines for efficient CI/CD and deployment. Key aspects of the project include:

1. **GitHub Repository and GitHub Actions**: The Flask starter code was set up in this repository, leveraging GitHub Actions for streamlined version control and collaboration.
   
2. **Azure Pipeline Deployment**: An Azure pipeline was created to automate the deployment of the application to an Azure Web App. The pipeline was configured to build and release updates with each code change, ensuring rapid iteration and deployment.

3. **Self-Hosted Agent**: The pipeline utilized a self-hosted agent, which provided control over the build environment and optimized the deployment process to Azure resources.

4. **Prediction API Integration**: After deployment, the application was successfully configured to fetch predictions through an integrated API endpoint.

This project illustrates the full lifecycle of developing, deploying, and testing a web application on the Azure platform, showcasing the power of Agile practices with modern cloud tools.

## Project Plan

Trello Board
https://trello.com/b/HqgvA3rc/udacity

Spread Sheet TBA

## Instructions

<TODO:  
* Architectural Diagram (Shows how key parts of the system work)>

<TODO:  Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

* Project running on Azure App Service

* Project cloned into Azure Cloud Shell

* Passing tests that are displayed after running the `make all` command from the `Makefile`

* Output of a test run

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

* Running Azure App Service from Azure Pipelines automatic deployment

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

* Output of streamed log files from deployed application

> 

## Enhancements

<TODO: A short description of how to improve the project in the future>

## Demo 

<TODO: Add link Screencast on YouTube>


