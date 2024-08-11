# Security-Dashboard
A custom built security dashboard.

## Planned Security and Access Controls
Implement:
- **Access Controls**: Ensure that users can only access data relevant to their role.
- **Data Encryption**: Encrypt data in transit and at rest.
- **Audit Trails**: Log access to the dashboard and track changes.

## Planned Visualization Tools
- **Graphs and Charts**: For trends over time, like number of attacks per month.
- **Heat Maps**: To show areas of higher risk or more frequent incidents.
- **Gauges and Dials**: For real-time monitoring of system health or network traffic.
- **Tables**: For detailed data breakdowns, like recent security incidents or patches applied.

## Design
Separate windows: **1. Technical, 2. Overview**

### Technical Window
Integrate and pull data from various sources across your security infrastructure, such as firewalls, intrusion detection systems, SIEM tools, and antivirus software
- **API Integrations**: For pulling data from different security tools.
- **Database Connections**: For historical data analysis.
- **Real-time Data Feeds**: For up-to-the-minute monitoring.
#### Key Metrics
- **Threat Intelligence**: Current active threats, sources of threats, types of malware detected.
- **System Health Metrics**: Status of critical systems, update and patch levels.

### Overview Window

#### Key Metrics
- Incident Response Metrics: Time to detect, time to respond, and time to resolve incidents.
- Compliance Metrics: Adherence to applicable regulatory frameworks.
- Risk Scores: Overall risk score, scores by department or system.