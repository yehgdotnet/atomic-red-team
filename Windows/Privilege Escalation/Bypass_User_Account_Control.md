# Bypass User Account Control

MITRE ATT&CK Technique: [T1122](https://attack.mitre.org/wiki/Technique/T1122)

There are many ways to perform UAC bypasses when a user is in the local administrator group on a system, so it may be difficult to target detection on all variations. Efforts should likely be placed on mitigation and collecting enough information on process launches and actions that could be performed before and after a UAC bypass is performed.

## Test Script

[UACBypass](https://github.com/redcanaryco/atomic-red-team/tree/master/Windows/Payloads/UACBypass)

