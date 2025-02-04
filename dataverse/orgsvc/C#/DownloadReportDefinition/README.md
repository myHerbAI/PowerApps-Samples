# Download report definition

This sample shows how to download a report definition (.rdl) file by using the [DownloadReportDefinitionRequest](https://learn.microsoft.com/dotnet/api/microsoft.crm.sdk.messages.downloadreportdefinitionrequest) message. 

## How to run this sample

See [How to run samples](https://github.com/microsoft/PowerApps-Samples/blob/master/dataverse/README.md) for information about how to run this sample.

## What this sample does

The `DownloadReportDefinitionRequest` message is intended to be used in a scenario where it contains the data that is needed to download a report definition.

## How this sample works

In order to simulate the scenario described in [What this sample does](#what-this-sample-does), the sample will do the following:

### Setup

Checks for the current version of the org.

### Demonstrate

1. The `QueryByAttribute` method  queries for an existing report.
2. The `DownloadReportDefinitionRequest` method downloads  the report definition.

### Clean up

Display an option to delete the sample data that is created in [Setup](#setup). The deletion is optional in case you want to examine the entities and data created by the sample. You can manually delete the records to achieve the same result.