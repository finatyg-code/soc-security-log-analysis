# SOC Security Log Analysis — Investigation Report

## Project Overview
This project demonstrates a simulated SOC investigation of suspicious SSH login activity using Kali Linux and Linux command-line tools.

## Investigation Findings
- Suspicious IP: 192.168.1.50
- Failed login attempts: 4
- Targeted accounts: admin and root
- Time of activity: October 24, 10:02:15 to 10:02:25
- Successful logins from suspicious IP: None observed

## Security Assessment
Four failed SSH login attempts occurred within 10 seconds from the same IP address. This may indicate a brute-force attempt, but the available logs do not confirm an attack or successful compromise.

## Recommended Response
1. Investigate the source IP and affected accounts.
2. Review additional authentication logs.
3. Monitor for repeated failed login attempts.
4. Enable account protection and rate limiting where appropriate.
5. Escalate confirmed suspicious activity to the security team.

## Skills Demonstrated
- Security log analysis
- Suspicious login detection
- Basic threat investigation
- Linux command-line analysis
- SOC incident documentation

## Lab Disclaimer
This investigation uses simulated authentication logs created for educational and portfolio purposes.
