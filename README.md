# Splunk-Brute-Force-Login-Detection
This project demonstrates the use of Splunk Enterprise to ingest, analyze, and detect suspicious authentication activity within security logs.
Splunk Brute-Force Login Detection

Project Overview

This project demonstrates the use of Splunk Enterprise to ingest, analyze, and detect suspicious authentication activity within security logs.

I created a custom Splunk source type for authentication logs and used Search Processing Language (SPL) to identify failed login attempts that could indicate a potential brute-force attack.

What I Did

- Ingested authentication logs into Splunk Enterprise.
- Created a custom source type for the log data.
- Searched and filtered authentication events using SPL.
- Identified multiple failed login attempts.
- Analyzed authentication activity to detect suspicious behavior.
- Practiced investigating security events from a SOC Analyst / Blue Team perspective.

Detection Query

index=main "status=failed"

This search filters the events in the "main" index where the authentication status is recorded as "failed".

Security Relevance

Repeated failed login attempts can be an indicator of a brute-force attack, where an attacker attempts multiple passwords or credentials to gain unauthorized access.

This project demonstrates practical skills in:

- SIEM monitoring
- Log analysis
- Threat detection
- SPL queries
- Authentication monitoring
- Security event investigation
- SOC Analyst fundamentals

Tools Used

Splunk Enterprise | Windows 10 | VMware Workstation

Project Goal

The goal of this project was to gain hands-on experience using Splunk as a SIEM platform and develop practical skills for detecting and investigating suspicious authentication activity in a SOC environment.
