# Active Directory & Attack Detection Lab

## Objective

This project involves simulating real world threats through the use of Splunk SIEM to ingest data from the Windows Domain Controller and a Windows Target Machine. I then used Kali Linux to perform a Brute Force Attack to see if Splunk was able to display the events of an attempted logon.s.

### Skills Learned
- SIEM Implementation & Management: Deployed and configured Splunk Enterprise on Ubuntu to ingest, parse, and visualize security telemetry.
- Endpoint Detection & Monitoring: Implemented Sysmon across Windows endpoints using custom XML configurations to capture high-fidelity logs, including Image Loads and Process Creation.
- Log Ingestion & Pipeline Configuration: Configured Splunk Universal Forwarders and managed inputs.conf files to route Windows Event Logs (Security, System, Application) and Sysmon data into specific Splunk indexes.
  
### Tools Used

- Sysmon
- Splunk Enterprise & Universal Forwarder
- Kali Linux
- Hydra
- Atomic Red Team
- Windows Server 2022, VMWare, Linux
- Powershell, Active Directory Users and Computers
