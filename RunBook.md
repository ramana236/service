## Application Run Book
##### Purpose : The Application Run Book will be a reference to understand execution and maintenance of the service

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Service Charachteristics
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Description |	This section requires information on: 1. Service hours : eg 24*7 or 2 days a week 2. Data and Process flow : eg data flows from Mobile devices to application server.
----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Hours of Operation | 	
Data and Processing flow | 	


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Back Up and Restore
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Description |	This section requires procedures to follow for : 1. backup : eg - stop the traffic to app server and take a sql dump. 2. restore : eg - Load the lates dump from s3 bucket to RDS. Restart the app server.
----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Backup Process | 	
Restore Process | 	

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Monitoring
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Description |	This section requires information on monitoring aspects of the service. 1. Log Aggregation tool/Solution : eg ELK/Cloudwatch & Kibana. 2. Log message format : eg JSON, log4j style single line output. 3. Error Message expression to be captured. 4. Metrics : Metrics to be captured eg : CPU, Netrowk In/Out
----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Log Aggregation Tool | 	
Log Message Format	| 
Error Message expression | 	
Metrics	|
Need of Log Rotation |

---------------------------------------------------------------
Health Checks
-----------------------------------------------------------------
Description	| This section intends to capture: 1. Health check on dependencies : eg /health HTTP endpoint for internal components. 2. Health Check on Service : eg /health HTTP endpoint: 200 --> basic health, 500 --> bad configuration
----------- | --------------------------------------------------
Health Check on Dependencies	|
Health check on Service	|

-----------------------------------------------------------------
Operational Tasks
----------------------------------------------------------------
Description |	This section requires 1. Deployment : How is the software deployed eg : Jenkins job url / scripts path. 2. Roll Back : How is roll-back done. 3. Sanity Checks : What kind of checks should be undertaken to confirm the functionality 4. (Optional) Batch Processing : What kind of batch processing happens.
----------- | ---------------------------------------------------
Deployment |	
Roll Back	|
Sanity Checks |	
Batch Process (Optional) |	
Troubleshoot Process	|

----------------------------
Maintenance Tasks 
----------------------------
Description	| This section requires : 1. Patching : How should be patches deployed and tested. 2. Data Clear Down : What data needs to be cleared on reg basis
----------- | -------------------------------------------
Patching	|
Data Clear Down |	

------------------------------
Partial Shutdown (Optional) 
------------------------------
Description	| This section requires: 1. Partial Shutodown : How can the service be throttled or partially shut down e.g. to avoid flooding other dependent systems. 2. Internal Requests : How can the service avoid/block internal requests. 3. How can the service avoid/block external requests
----------- | --------------------------
Partial Shutdown	|
Internal Requests	|
External Requests	|

---------------------------------
Load on Application 
---------------------------------
Description	| This section requires: 1. Peak Periods : Estimated time of peak load on application e.g. Friday @16:00 - Sunday @20:00. 2. Moderate Periods : Estimated time of moderate load on application e.g. Daily @11:00 - @16:00 3. Lean Periods : Estimated time of less load on application e.g. Daily @20:00 - @05:00
----------- | -------------------
Peak Periods	|
Moderate periods |	
Lean Periods	|


