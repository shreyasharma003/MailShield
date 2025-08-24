# MailShield
MailShield: Real-time Email Threat Detection; IP Tracing with Java Spring Boot + React.

**MailShield** is a hackathon ready web application that scans emails directly from your mailbox, detects potential threats, and traces suspicious IPs to their location.
The platform combines a Java Spring Boot backend with a React frontend, offering a seamless, realtime threat detection experience.
---
## Features
-Direct Mailbox Scan: Connects to IMAP supported email accounts and fetches emails automatically.

-Threat Detection: Scans email content for suspicious keywords such as `bomb`, `fraud`, `attack`, etc.

-IP Extraction & Geolocation: Extracts sender IP from email headers and maps it to city/country using MaxMind GeoIP2.

-Risk Scoring: Assigns a risk level (Low/Medium/High) based on keyword count and foreign IPs.
