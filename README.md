# Web-Attack-Detection-Custom-Rule-Engineering-Wazuh-SIEM-DVWA-
Implementing a SIEM-based detection environment using Wazuh to monitor and alert on web vulnerabilities within DVWA through custom rule engineering

🏗️ Lab Architecture

The infrastructure is hosted within an isolated VirtualBox Internal Network to ensure a secure environment for attack simulation:

Target Server: Ubuntu Server hosting DVWA (Apache2, PHP, MySQL).

SIEM Platform: Ubuntu Server running Wazuh Manager for centralized log collection and analysis.

Attacker Machine: Kali Linux used to execute various web-based attack vectors.

Network: Fully isolated environment to prevent external traffic interference.

🛠️ Key Technical Implementations

Log Ingestion: Integrated Apache2 web server logs into the Wazuh Manager via the Wazuh Agent for centralized visibility.

Detection Engineering: Developed custom XML decoders and rules specifically tailored to detect SQL Injection (SQLi), Cross-Site Scripting (XSS), and Brute Force attacks.

Incident Analysis: Configured the Wazuh Dashboard for real-time alerting and incident visualization to facilitate rapid response.

📁 Repository Structure

/rules: Contains the customized XML rulesets and decoders developed during the project.

/docs: Includes the network topology diagrams and screenshots of the Wazuh alerts triggered during simulations.
