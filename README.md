# University-Financial-System-TMT
Overview
This project demonstrates a comprehensive Threat Modeling analysis for a University Financial System using the Microsoft Threat Modeling Tool (TMT). The goal of the project is to identify potential security threats, mitigate vulnerabilities, and enhance the overall security of the university's financial operations and data systems.

Key Features
Threat Modeling:
Developed a detailed threat model using Microsoft TMT to analyze the financial system, including user interactions via the University Web Portal.

Visual Representation:
Designed a data flow diagram (DFD) for the university's financial system, showcasing key components like:

Staff Portal
Student Access
Financial Server
Backup Server
Authentication Systems (e.g., Multi-Factor Authentication)
Network Firewalls and IPSec encryption
Attack Tree:
Created an Attack Tree for SQL Injection vulnerabilities, detailing:

Entry points for attacks
Methods of exploitation
Mitigation strategies to prevent such attacks.
Mitigation Strategies:
Implemented mitigation steps for identified vulnerabilities, including:

Input validation and sanitization.
Strengthening API validation processes.
Securing IPSec configurations.
Project Scope
Objective: To secure sensitive university financial operations and ensure data integrity and confidentiality.
Tools Used:
Microsoft Threat Modeling Tool (TMT) for threat identification.
Visual design tools to represent system architecture and data flow.
Key Components Analyzed:
Secure user authentication (via Staff and Student Portals).
Financial Database and Backup Servers.
Network communications between users and servers.
Secure data flow through external and internal firewalls.
System Architecture
The architecture comprises:

External Boundaries:
Internet Boundary with external firewalls.
Remote access for students and staff using HTTPS and VPN.
Internal Boundaries:
DMZ (Demilitarized Zone) for trusted components.
IPSec encryption for secure internal communication.
Key Components:
Web Portal: Central interface for users.
Financial Server: Stores and processes financial transactions.
Backup Server: Ensures data redundancy and recovery.
Monitoring and Audit Servers: Tracks system activities and logs events.
How It Works
Threat Identification:
Potential threats, such as SQL Injection, weak input validation, and IPSec misconfigurations, were identified using TMT.
Threat Mitigation:
Steps to address each identified threat were proposed and implemented, ensuring secure data transfer and system access.
Attack Tree:
Analyzed SQL Injection vulnerabilities, detailing exploit paths and prevention methods.
Key Files
SystemArchitecture.png: Detailed data flow diagram for the system.
AttackTree_SQLInjection.png: Attack tree representation for SQL Injection.
ThreatModel_Report.docx: Full threat model report generated using Microsoft TMT.
Setup and Usage
Clone the repository:
git clone https://github.com/your-repo/university-financial-system.git
View system architecture:
Open SystemArchitecture.png for an overview of the data flow.
Review Threat Model:
Open the ThreatModel_Report.docx for detailed threat descriptions and mitigations.
