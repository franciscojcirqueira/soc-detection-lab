SOC Detection Lab - Brute Force Attack
Scenario

A Linux server showed multiple failed SSH login attempts followed by a successful login.

Objective

Identify signs of a brute force attack and analyze suspicious activity.

Analysis Performed
Detected repeated failed login attempts
Identified suspicious IP: 192.168.1.10
Observed successful login after multiple failures
Findings

Potential brute force attack with possible system compromise.

Tools Used
Linux
grep
Response Actions
Recommended IP blocking
Password reset
Log review for lateral movement
Project Structure
auth.log → Raw authentication log data used for analysis
analysis/investigation.txt → Incident investigation report
analysis/commands_used.txt → Linux commands used during analysis
