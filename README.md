# purviewautomation
Automate Purview Operations with Python SDK

This notebook is based on some parts of the Tutorial on Microsoft Learn
Link: https://learn.microsoft.com/en-us/purview/tutorial-using-python-sdk
However, it extends the tutorial by showcasing how to work with the query results in pyspark.

## Intro

This tutorial will introduce you to using the Microsoft Purview Python SDK. You can use the SDK to do all the most common Microsoft Purview operations programmatically, rather than through the Microsoft Purview governance portal.

In this tutorial, you'll learn how to use the SDK to:

- Grant the required rights to work programmatically with Microsoft Purview
- Register a Blob Storage container as a data source in Microsoft Purview
- Instantiate the Purview Clients in Python
- Define and run a scan
- Search the catalog
- Delete a data source

## Prerequisites
For this tutorial, you'll need:

- Python 3.6 or higher
- An active Azure Subscription. If you don't have one, you can create one for free.
- A Microsoft Entra tenant associated with your subscription.
- An Azure Storage account. If you don't already have one, you can follow our quickstart guide to create one.
- A Microsoft Purview account. If you don't already have one, you can follow our quickstart guide to create one.
- A service principal with a client secret.

## Get Started
For the notebook to work, you need a service principal and you need to grant specific rights to the service principal in your collection in Purview. For more info see here: https://learn.microsoft.com/en-us/purview/tutorial-using-python-sdk#grant-your-application-the-access-to-your-microsoft-purview-account

The notebook focuses on the "Search Catalog" experience, so only "Data Reader" is required on the Collections.
