Yellow RAT Lab – Malware Analysis Report

Platform: CyberDefenders
Category: Threat Intelligence
Difficulty: Easy
Level: SOC Analyst Tier 1 – Level 2
Tools: VirusTotal, Red Canary
MITRE ATT&CK Tactics: Initial Access, Execution
Status: Completed – 6/6 Questions

---

1. Lab Overview

The objective of this lab was to investigate a Yellow RAT malware incident at GlobalTech Industries.

Abnormal network traffic was detected from multiple workstations, and employees' search queries were being redirected to unfamiliar websites.

The investigation focused on analyzing malware artifacts, identifying Indicators of Compromise (IOCs), determining the malware's C2 infrastructure, and gathering threat intelligence to understand the adversary's activities.

2. Investigation Findings

#| Investigation Question| Finding

Q1| Threat Cluster Name| Yellow Cockatoo

Q2| Common Malware Filename| "111bc461-1ca8-43c6-97ed-911e0e69fdf8.dll"

Q3| Compilation Timestamp| "2020-09-24 18:26"

Q4| First Submission to VirusTotal| "2020-10-15 02:47"

Q5| Dropped DAT File| "solarmarker.dat"

Q6| C2 Server| "https://gogohid.com"


3. Technical Analysis

The investigation revealed several important indicators associated with the Yellow RAT malware:

- Threat Attribution: Red Canary identifies the associated threat cluster as Yellow Cockatoo.
- Malware Identification: Identified the common DLL filename using VirusTotal.
- Compilation Timeline: Extracted the malware's compilation timestamp to understand its development timeline.
- Threat Intelligence: Identified the first VirusTotal submission date, providing insight into when the sample became known to the cybersecurity community.
- Malware Artifacts: Identified "solarmarker.dat" as a dropped file in the AppData directory.
- C2 Infrastructure: Identified "https://gogohid.com" as the Command and Control server.

4. Evidence & Screenshots

Q1 – Threat Cluster Identification

Finding: "Yellow Cockatoo"

Evidence:

<img width="815" height="486" alt="Screenshot (67)" src="https://github.com/user-attachments/assets/d2f7e7c0-21f8-4be6-9ddb-0fa02f5da2b8" />


Q2 – Common Malware Filename

Finding: "111bc461-1ca8-43c6-97ed-911e0e69fdf8.dll"

Evidence:

<img width="1335" height="627" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/0e25e1f3-191e-46c8-9ee2-a9539716dc98" />


Q3 – Compilation Timestamp

Finding: "2020-09-24 18:26"

Evidence:

<img width="1661" height="701" alt="Screenshot (63)" src="https://github.com/user-attachments/assets/d8b37426-1b53-45db-814a-043ab52044fa" />


Q4 – First VirusTotal Submission

Finding: "2020-10-15 02:47"

Evidence:

<img width="1662" height="685" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/1e0cfa3e-d976-4b5e-b5a8-3206a7da276e" />


Q5 – Dropped DAT File

Finding: "solarmarker.dat"

Evidence:

<img width="1371" height="764" alt="Screenshot (65)" src="https://github.com/user-attachments/assets/95d0be81-cd6b-4bd4-8f4b-50398b5caab9" />


Q6 – Command and Control Server

Finding: "https://gogohid.com"

Evidence:

<img width="1385" height="751" alt="Screenshot (66)" src="https://github.com/user-attachments/assets/45f2fd74-d816-4f47-a192-e9d4a59de571" />


5. Skills & Knowledge Gained

- Malware artifact analysis using VirusTotal.
- Threat intelligence research using Red Canary.
- Identifying malware filenames and file artifacts.
- Analyzing compilation and submission timestamps.
- Identifying Command and Control infrastructure.
- Extracting and documenting Indicators of Compromise (IOCs).
- Understanding malware investigation from a SOC Analyst perspective.

6. Conclusion

This lab provided practical experience in investigating Yellow RAT malware using threat intelligence platforms.

The investigation helped identify the associated threat cluster, malware artifacts, timeline indicators, and C2 infrastructure.

These findings demonstrate the importance of threat intelligence and IOC analysis in supporting incident response, threat detection, and containment.

Lab Status: Successfully Completed – 6/6 Questions.
