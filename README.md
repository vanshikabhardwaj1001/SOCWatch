# 🛡️ SOCWatch

SOCWatch is a hands-on Security Operations Center (SOC) lab created to practice defensive cybersecurity, security monitoring, log analysis, threat detection, and incident investigation.

The project simulates a small SOC environment using Windows, Kali Linux, VMware, Sysmon, SIEM monitoring, Windows Event Logs, and security dashboards.

---

## 📌 Project Overview

SOCWatch demonstrates the basic workflow followed by a SOC analyst:

```
System Activity
      ↓
Log Generation
      ↓
Log Collection
      ↓
SIEM
      ↓
Event Analysis
      ↓
Threat Detection
      ↓
Investigation
      ↓
Security Dashboard
```

The main goal of this project is to understand how security events are generated, collected, monitored, investigated, and visualized.

---

## 🎯 Objectives

- Build a practical SOC environment
- Understand SIEM fundamentals
- Collect and analyze security logs
- Monitor Windows security events
- Monitor process activity
- Investigate authentication events
- Detect suspicious activity
- Analyze security alerts
- Understand Event IDs
- Track Process IDs
- Build security dashboards
- Perform basic incident investigation
- Practice Blue Team methodologies
- Understand the workflow of a SOC analyst

---

## 🏗️ Lab Environment

### 💻 Virtual Machines
- Windows VM
- Kali Linux VM
- VMware virtualization environment

### 🔐 Security Technologies
- SIEM
- Sysmon
- Windows Event Viewer
- Windows Security Logs
- Windows System Logs
- Windows Application Logs
- Security Event Monitoring
- Log Analysis
- Dashboard Visualization

---

## 🔎 Topics Covered

### 1. SOC Fundamentals
- Security Operations Center
- SOC Analyst
- Blue Team
- Security Monitoring
- Threat Detection
- Incident Investigation
- Log Analysis
- Alert Monitoring
- Security Events
- Incident Response Workflow

### 2. SIEM

The project covers the fundamentals of Security Information and Event Management (SIEM).

Topics practiced:
- Log collection
- Log ingestion
- Event monitoring
- Event searching
- Event filtering
- Event analysis
- Security alerts
- Dashboard creation
- Security visualization
- Detection concepts

### 3. Windows Event Monitoring

Windows Event Viewer was used to understand and investigate system activity.

Important event categories include:
- Windows Security Logs
- Windows System Logs
- Windows Application Logs

Events investigated include:
- Successful authentication
- Failed authentication
- Account activity
- Process creation
- System activity
- Security-related events

---

## 🧾 Windows Event IDs

SOCWatch includes practical investigation of Windows Event IDs.

Examples:

| Event ID | Description |
|----------|-------------|
| 4624 | Successful account logon |
| 4625 | Failed account logon |
| 4688 | A new process has been created |

These events can help SOC analysts investigate authentication activity and process execution.

---

## ⚙️ Sysmon

Sysmon was used to provide additional visibility into Windows system activity.

Topics covered:
- Sysmon installation
- Sysmon configuration
- Process monitoring
- Process creation
- Process IDs
- Parent-child process relationships
- Network-related events
- File activity
- System activity monitoring

Sysmon provides additional telemetry that can help analysts investigate suspicious behavior.

---

## 🔍 Process Investigation

Process monitoring is an important part of the project.

Topics covered:
- Process ID (PID)
- Process creation
- Parent process
- Child process
- Process relationships
- Suspicious process identification
- Process investigation
- Command-line activity

Example investigation flow:

```
Suspicious Event
      ↓
Find Event ID
      ↓
Identify Process
      ↓
Check Process ID
      ↓
Check Parent Process
      ↓
Investigate Activity
```

---

## 🔐 Authentication Monitoring

SOCWatch also focuses on authentication-related activity.

Topics covered:
- Successful logins
- Failed login attempts
- Account activity
- Authentication events
- Login investigation
- Brute-force detection concepts
- Suspicious authentication patterns

Repeated failed login attempts can indicate possible password attacks or unauthorized access attempts.

---

## 🚨 Threat Detection

The project demonstrates basic threat detection concepts.

Examples of suspicious activity:
- Multiple failed login attempts
- Unexpected process creation
- Suspicious process execution
- Unusual account activity
- Abnormal system activity
- Unexpected network activity

The objective is to identify unusual behavior and investigate it using available logs.

---

## 📊 SOC Dashboard

A security dashboard was created to provide a centralized view of important events.

Dashboard concepts covered:
- Security event visualization
- Authentication monitoring
- Failed login monitoring
- Successful login monitoring
- Process activity
- Event trends
- Security event counts
- Event filtering
- Visual monitoring

The dashboard helps an analyst quickly understand what is happening inside the monitored environment.

---

## 🖥️ Windows Event Viewer

Windows Event Viewer was used during investigations.

Topics covered:
- Opening Event Viewer
- Navigating Windows logs
- Security logs
- System logs
- Application logs
- Finding Event IDs
- Filtering events
- Reading event details
- Investigating timestamps
- Investigating usernames
- Investigating Process IDs

---

## 🐧 Kali Linux

Kali Linux was used as the security testing environment.

Topics covered:
- Kali Linux
- VMware
- Linux terminal
- Network security tools
- Security testing
- Basic reconnaissance concepts
- Security lab testing

Kali Linux was used only within the controlled lab environment.

---

## 🌐 Networking

The project also connects SOC monitoring with basic networking concepts.

Topics covered:
- IP addresses
- Network connections
- Ports
- Network activity
- Client-server communication
- Network monitoring
- Suspicious connections
- Basic network investigation

---

## 🕵️ Security Investigation

A basic SOC investigation workflow was followed:

```
1. Detect suspicious activity
        ↓
2. Identify the event
        ↓
3. Check Event ID
        ↓
4. Check timestamp
        ↓
5. Identify user
        ↓
6. Identify Process ID
        ↓
7. Investigate process activity
        ↓
8. Analyze related events
        ↓
9. Determine whether activity is suspicious
        ↓
10. Document findings
```

---

## 🧪 Lab Testing

Controlled activities were performed inside the virtual lab to generate security events.

Examples:
- Login attempts
- Failed authentication attempts
- Process execution
- User activity
- System activity
- Network activity

The generated events were then investigated through Windows logs and SIEM dashboards.

---

## 📚 Concepts Learned

Through SOCWatch, I gained practical exposure to:

- SOC Operations
- Blue Team Security
- SIEM
- Security Monitoring
- Log Collection
- Log Analysis
- Event Correlation
- Windows Event Logs
- Windows Event Viewer
- Sysmon
- Event IDs
- Process IDs
- Process Monitoring
- Authentication Monitoring
- Threat Detection
- Alert Investigation
- Incident Investigation
- Network Monitoring
- Security Dashboards
- Kali Linux
- VMware
- Virtual Machines

---

## 🛠️ Tools & Technologies

- Windows
- Kali Linux
- VMware
- Sysmon
- Windows Event Viewer
- SIEM
- Security Dashboards
- Log Analysis
- Network Monitoring

---

## 📸 Project Screenshots

The repository contains screenshots showing:
- SOC dashboard
- Windows Event Viewer
- Security events
- Event IDs
- Process monitoring
- Sysmon activity
- Kali Linux environment
- Investigation workflow
- Dashboard visualizations

---

## 🧠 Skills Demonstrated

**Defensive Security**
- Security Monitoring
- Threat Detection
- Log Analysis
- Incident Investigation
- Authentication Monitoring
- Process Investigation

**Networking**
- IP addressing
- Ports
- Network connections
- Network activity analysis

**Windows Security**
- Event Viewer
- Security Logs
- Event IDs
- Sysmon
- Process Monitoring
- Authentication Events

**SOC / SIEM**
- Alert Investigation
- Dashboard Monitoring
- Event Analysis
- Detection Workflow

---

## 🚀 Future Improvements

Future versions of SOCWatch may include:
- More detection rules
- Automated alerts
- Brute-force detection
- Suspicious PowerShell detection
- Malware detection scenarios
- Network traffic monitoring
- Wireshark integration
- Nmap-based asset discovery
- Threat intelligence integration
- MITRE ATT&CK mapping
- Automated incident response
- Multiple Windows endpoints
- Linux endpoint monitoring
- Centralized log collection
- Custom detection rules
- Email/notification alerts
- Advanced SOC dashboards

---

## 🗺️ Future SOC Architecture

```
             ┌───────────────┐
             │ Windows       │
             │ Endpoint      │
             └───────┬───────┘
                     │
                     │ Logs
                     ▼
             ┌───────────────┐
             │ Log Collector │
             └───────┬───────┘
                     │
                     ▼
             ┌───────────────┐
             │     SIEM      │
             └───────┬───────┘
                     │
          ┌──────────┴──────────┐
          ▼                     ▼
   ┌──────────────┐      ┌──────────────┐
   │ Detection    │      │ Dashboard    │
   │ & Alerts     │      │ Visualization│
   └──────┬───────┘      └──────────────┘
          │
          ▼
   ┌──────────────┐
   │ Investigation│
   └──────┬───────┘
          │
          ▼
   ┌──────────────┐
   │   Response   │
   └──────────────┘
```

---

## ⚠️ Disclaimer

SOCWatch is an educational cybersecurity project created for learning, defensive security practice, and controlled security testing.

All testing should be performed only on systems and networks that you own or have explicit authorization to test.

---

## 👩‍💻 Author

**Vanshika**
Cybersecurity Student | Aspiring SOC Analyst

**Areas of Interest**
- Blue Team
- SOC Operations
- Network Security
- Threat Detection
- Incident Response
- SIEM
- Defensive Security
- Cybersecurity Monitoring

---

## ⭐ Project Status

- **Status:** Completed ✅
- **Type:** Cybersecurity / SOC Lab
- **Focus:** Defensive Security / Blue Team
- **Environment:** Virtual Lab

---

## 📌 Key Takeaway

SOCWatch is a practical demonstration of how a SOC analyst can monitor system activity, analyze security events, investigate suspicious behavior, and use dashboards to maintain visibility over a monitored environment.
