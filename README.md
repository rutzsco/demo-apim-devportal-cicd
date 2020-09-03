# Using Azure Pipelines to deploy API Managment Developer Portal content

This project shows how to use Azure Pipelines to deploy developer portal content to a target API Management Instance

## Management Scripts

The management scripts are sourced from the api-management-developer-portal Repository:

https://github.com/Azure/api-management-developer-portal/tree/master/scripts.v2

These have been copied into this repo for use by the release pipeline:

https://github.com/rutzsco/demo-apim-devportal-cicd/tree/master/scripts.v2


## CICD

## Build

### Build Pipeline

- https://github.com/rutzsco/demo-apim-devportal-cicd/blob/master/azure-build-pipelines.yml

## Release Pipeline

- https://github.com/rutzsco/demo-apim-devportal-cicd/blob/master/azure-release-pipelines.yml

### Variables
These pipline variables are required for release:
 
 - SourceAPIMEndpoint - instance-name.management.azure-api.net
 - SourceAPIMToken - SharedAccessSignature integra... 
 - TargetAPIMEndpoint - instance-name>.management.azure-api.net
 - TargetAPIMToken - SharedAccessSignature integra...

## Reference

- https://github.com/Azure/api-management-developer-portal/wiki
