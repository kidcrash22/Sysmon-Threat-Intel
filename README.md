# Sysmon-Threat-Intel

Collection of sysmon specific searches for Splunk all packaged in one app. Still very much a work in progress.

Requirements:

- [Sysmon-TA](https://splunkbase.splunk.com/app/1914/)

- A macro is used for all saved searches, you will need to modify it for your environment to ensure the proper Sysmon sourcetype/index is searched.

    Macros: Settings --> Advanced Search --> Search Macros. Edit to your environment

    Default - sourcetype="XmlWinEventLog:Microsoft-Windows-Sysmon/Operational"

Current Dashboards:  
- Sysmon Overview - Shows basic overview and usage for sysmon events.  
- Investigator - Allows searching of events for specific hosts, users.  
- Network Overview  
- Network Connections - Provides searchable list of network connections
- File Creation Overview  
- Registry Overview
- Process Overview  
- Suspicious Indicators - Collection of some known IOC  
