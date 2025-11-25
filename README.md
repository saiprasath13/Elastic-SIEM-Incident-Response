 Security Alert Monitoring & Incident Response using Elastic SIEM

This project was completed as part of the **Future Interns Cybersecurity Internship (Task 2)**.  
The objective of this task is to simulate the role of a SOC (Security Operations Center) analyst by monitoring security logs using a SIEM platform, identifying suspicious activity, classifying alerts based on severity, and drafting an incident response report.

Project Overview

Using Elastic Cloud (SIEM + Kibana), system-generated log files were uploaded and analyzed to detect unusual activities such as:

- Repeated failed login attempts (Brute force indicators)
- Suspicious or foreign IP access
- Authentication anomalies
- Potential malware or command execution attempts

Based on the findings, a formal incident response process was followed.

 Tools & Technologies

| Tool / Platform | Purpose |
|----------------|---------|
| Elastic Cloud (Kibana SIEM) | Log ingestion & threat monitoring |
| KQL (Kibana Query Language) | Filtering & analyzing logs |
| Future Interns Sample Logs | Simulated SOC dataset |
| PDF Report | Final deliverable containing findings |

 Workflow Steps

1. Spin up Elastic SIEM deployment in cloud
2. Upload and index provided system log dataset
3. Use Discover & Dashboard modules for:
   - Event correlation
   - IP tracking
   - Alert triage
4. Identify & tag suspicious events
5. Classify alerts based on severity (Low → Critical)
6. Create an **Incident Response Report** with:
   - Evidence screenshots
   - Root cause analysis
   - Impact assessment
   - Recommended remediation steps

Summary of Detected Incidents 

| Incident | Details | Severity | Status |
|----------|---------|----------|--------|
| Brute force login attempt | 20+ failed attempts from unknown IP |  High | Escalated |
| Unauthorized login | Logged in from unusual geo-location |  Medium | Investigating |
| Normal login events | Approved user access |  Low | No action |



## 📁 Repository Structure

