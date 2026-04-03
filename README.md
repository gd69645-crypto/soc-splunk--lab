# SOC Splunk Lab 
This repository contains hands -on SOC investigations using splunk. 
## Projects
User Activity Analysis
### Objective
Analyze user activity logs to identify patters and anomalies.
### Tools used
Splunk
SPL (Search Processing Language)
TryHackMe
## Key Query
| from datamodel:"internal_audit_logs.Audit"
| stats count by user
## Findings
The anaylysis showed that the "admin" account had the highest activity count,which may indicate normal administrative behavior or potential overuse that requires further investigation.
|from datamodel:"internal _audit _logs.Audit"
|stats count by user
## Skills Practiced 
Log Analysis
Siem investigation
SPL queries
Pattern recognition 
Tools
Splunk
Tryhackme
