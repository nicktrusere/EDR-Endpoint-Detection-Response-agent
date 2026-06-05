# EDR-Endpoint-Detection-Response-agent
clean, working design + code skeleton EDR (Endpoint Detection &amp; Response) agent
This is a mini-EDR system

System Summary
This project implements a lightweight EDR-style monitoring agent that collects endpoint and network telemetry, applies rule-based detection, correlates events across 
multiple sources, and forwards alerts to a SIEM system for analysis and visualization.
Developed a Python-based EDR-style monitoring agent that collects Windows security logs, process metadata (PID/PPID), and network connections, applies detection 
rules for brute force, suspicious execution, and reverse shells, and correlates multi-source events to identify attack chains before forwarding alerts to a SIEM backend.

