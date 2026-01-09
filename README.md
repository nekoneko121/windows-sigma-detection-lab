# windows-sigma-detection-lab
Hands-on detection engineering with Windows Event Logs and Sigma rules
## Overview
This repository demonstrates basic detection engineering using Windows Event Logs and Sigma rules.
It focuses on understanding attacker behavior and translating it into practical detection logic.

## Threat Scenario
- Suspicious PowerShell execution
- Abuse of built-in Windows administrative tools
- Potential lateral movement activity

## Environment
- Windows 10 / Windows Server
- Windows Event Logs (Security)
- Optional: Sysmon

## Detection Content
- Sigma rules for:
  - Suspicious PowerShell execution
  - Abnormal process creation patterns

## How to Use
1. Collect Windows Event Logs from a test system
2. Apply Sigma rules using a Sigma-compatible backend
3. Review matched events and validate detection accuracy

## Why This Detection
This detection focuses on behavioral patterns rather than specific malware signatures,
making it more resilient against simple evasion techniques.

## Limitations
- False positives may occur in administrative or scripting-heavy environments
- Detection accuracy depends on log configuration and event coverage
