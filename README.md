# powerApps-https
This Repository will contain all https PowerApps interactions including Validation and (coming soon) Programmatic Deployment.

## powerApps-validator

This validator runs on three parts. It is by no means the best or most optimal way to do it but, it definitely is the cheapest way to do it.
1. An excel spreadsheet with a detailed  model that covers various parameters that need to be validated
2. Powershell Script to pull Dataverse Entity Definition and export a comparison to the Model Spreadsheet
3. A PowerQueried Excel spreadsheet to identify the differences and present the differences in an effective fashion. 
