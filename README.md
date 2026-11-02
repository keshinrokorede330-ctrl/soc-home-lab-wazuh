SOC Home Lab - Wazuh + Suricata IDS
Overview
This is a Security Operations Center (SOC) home lab built to simulate real-world threat detection, log analysis, and incident investigation. This project demonstrates hands-on experience with IDS/IPS, SIEM, and Linux forensics.

Architecture
- Host: Windows 11 + Oracle VirtualBox
- SIEM: Wazuh
- IDS/IPS: Suricata
- Log Sources: Suricata EVE JSON, Fast.log
- OS: Ubuntu Server 22.04 (Lab VM)

Tools & Technologies
- Wazuh Manager
- Suricata IDS
- Ubuntu Linux
- VirtualBox
- GitHub for evidence preservation

What I Did
1. Installed and configured Suricata IDS on Ubuntu VM
2. Generated and monitored network traffic
3. Captured IDS alerts in:
   - eve.json - Full JSON alert logs with metadata
   - fast.log - Human-readable alert summary
4. Uploaded logs to GitHub for incident investigation
 Sample Detection
Logs in this repo contain Suricata alerts triggered by suspicious traffic.
These can be used for:
- Threat hunting
- Rule tuning
- Incident triage (True Positive vs False Positive analysis)

 Evidence
- eve.json - Suricata EVE JSON output
- fast.log - Suricata fast log format

Next Steps
- Forward Suricata logs to Wazuh Manager
- Create custom Wazuh rules for Suricata alerts
- Build Wazuh dashboards for visualization
- Perform full incident investigation workflow

Author
Keshinro Korede - Aspiring SOC Analyst | GenXcel Program
