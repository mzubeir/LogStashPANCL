# LogStashPANCL
LogStash PAN OS logs to Azure Sentinel for Modified Custom Tables
For Windows only Platforms/Infrastructure where no Linux servers exist or can be used.  
This Data connector has been modified to point to the custom tables in the Azure Log Analytics table.  This addresses issues when using Windows with Logstash to feed logs
from PAN's.  These go into a custom Table which the existing PAN Connector points to the CommonSecurityLog Tables so does not go green.

Refer to the orignal PaloAlto Connector:
https://github.com/Azure/Azure-Sentinel/tree/master/DataConnectors/Palo%20Alto%20Networks

Compare the Table Headers etc. and amend according to your table name etc.  All references to the Tables etc. have an *_CL and columns have _s.



