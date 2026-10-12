# ICMP Flood DoS — Network Security Incident Report

## Project Overview

This project presents an educational analysis of an ICMP flood Denial-of-Service (DoS) scenario. It documents the incident lifecycle, identifies a firewall misconfiguration as the assumed root cause, and outlines security controls for detection, response, and recovery.

## Objectives

- Analyze the impact of an ICMP flood on network availability.
- Identify the security configuration weakness.
- Recommend preventive and detective security controls.
- Apply the NIST Cybersecurity Framework (CSF) functions to incident management.
- Document response, recovery, and lessons learned.

## Incident Summary

The scenario describes a high volume of ICMP traffic disrupting internal network services for approximately two hours. A firewall configuration that permitted unrestricted inbound ICMP traffic is treated as the assumed root cause.

This is an educational scenario, not a claim of a verified real-world incident or data breach.

## Attack Flow

![ICMP Flood Attack Flow](images/attack-flow.png)

## NIST Cybersecurity Framework

![NIST CSF Five Core Functions](images/nist-csf-functions.png)

The report maps the incident to the five CSF functions: Identify, Protect, Detect, Respond, and Recover.

## Recommended Security Controls

- Firewall hardening and ICMP rate limiting
- Anti-spoofing and ingress filtering
- Network traffic monitoring and centralized log analysis
- Intrusion detection and alerting
- Incident evidence preservation and recovery validation

## Report

[Read the full incident report (PDF)](report/incident-report.pdf)

## Scope and Disclaimer

This project is intended for educational and portfolio purposes. Recommendations are distinguished from actions described as having occurred in the scenario. No claim of unauthorized access, data exfiltration, or confirmed data loss is made.

## Framework

NIST Cybersecurity Framework (CSF) — Identify, Protect, Detect, Respond, Recover
