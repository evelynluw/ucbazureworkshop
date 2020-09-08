# UC Berkeley Datathon
**September 12, 2020**

This workshop was designed for UC Berkeley's PiE Datathon, sponsored by Microsoft.

We introduce you to Microsoft Azure's cognitive services using two datasets. In this repository, you'll find the materials to conduct text analytics on two datasets using the Cognitive Services Text Analytics API.

You can check out the text analytics demo [here](LINK).

## Setup Requirements
- [Free Azure student subscription](https://azure.microsoft.com/en-us/free/students/)
- Python
- Anaconda (Pandas, Numpy)
- Jupyter Notebooks or your preferred IDE
- Git

## Setup

### Import requests
Run the command `pip install --upgrade requests` in your terminal.

Add `import requests` at the top of your Python file in order to call the Azure text analytics API.

### Create a Text Analytics resource in the Azure Portal
It is recommended that you create a Text Analytics resource for your project (team members can share an API key). You are welcome to incorporate other [Azure Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/?&ef_id=CjwKCAjw19z6BRAYEiwAmo64LVDAg0XDqkMIu9giSdrSMtEj62pCT0xpuv43pOjooX0xCO6kF1_3choC4wYQAvD_BwE:G:s&OCID=AID2100131_SEM_CjwKCAjw19z6BRAYEiwAmo64LVDAg0XDqkMIu9giSdrSMtEj62pCT0xpuv43pOjooX0xCO6kF1_3choC4wYQAvD_BwE:G:s&gclid=CjwKCAjw19z6BRAYEiwAmo64LVDAg0XDqkMIu9giSdrSMtEj62pCT0xpuv43pOjooX0xCO6kF1_3choC4wYQAvD_BwE) as appropriate for the scope of your project!

Learn more about the Text Analytics API and what it offers in [the Azure documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/text-analytics/).

**Creating an Azure resource**

Follow [this tutorial](https://docs.microsoft.com/en-us/azure/cognitive-services/cognitive-services-apis-create-account?tabs=multiservice%2Cwindows) for creating a resource in Azure and accessing its API key.

When creating your resource, set the following configuration:
- `Subscription`: your Azure student subscription
- `Location`: this [depends on your team's general location](https://azure.microsoft.com/en-us/global-infrastructure/geographies/). We recommend selecting "(US) West US" from the dropdown menu if you are on the west coast or "(US) East US" if you are on the east coast. 
- `Pricing Tier`: Standard S if available or Free
- `Resource group`: Create a new [resource group](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal) that will contain all of your Azure resources



## The datasets

### Option 1: Seattle Police Dataset
Description: "Records of Officer Involved Shootings (OIS) from 2005 to the present, including a brief narrative synopsis."

More information about this dataset: [Seattle Police Data](https://data.seattle.gov/Public-Safety/SPD-Officer-Involved-Shooting-OIS-Data/mg5r-efcm)


### Option 2: Customer Service Data
Description: These are records of support tickets that a hardware general store has received in the form of emails or audio converted to text.

[-- Insert column description names --]