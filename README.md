# Using M365 Hunting as Targetting for KMSAT

Here you will find some samples, scripts, tools and other pieces of information.

1 Scripts in this location is:
Get Targeted Users

Requires PS v5 to run.
You will need to register an Azure App in your tenant, User Read and Threat Hunting permissions.

## DO NOT USE IN PRODUCTION ENVIRONMENTS, THESE ARE DEMONSTRATION SCRIPTS WITH LIMITED ERROR CHECKING. 

### Get Targeted Users
Auths against our api app registration.  
Gets top targeted users for phish attacks from advanced hunting.  
Puts them into variable that you can save as a CSV for input into KMSAT etc 
