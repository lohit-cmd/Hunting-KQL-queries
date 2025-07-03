Hunting-KQL-Queries
A curated collection of advanced Kusto Query Language (KQL) hunting queries for Microsoft Defender XDR, Sentinel, and Azure environments. This repository empowers security analysts and threat hunters to proactively detect, investigate, and respond to sophisticated threats across endpoint, cloud, identity, and email workloads.

🚩 Purpose
Enable proactive threat hunting using real-world attack patterns, TTPs (Tactics, Techniques, and Procedures), and emerging threats.

Share tested queries mapped to MITRE ATT&CK, ransomware, APTs, living-off-the-land, cloud abuse, and more.

Facilitate collaboration, continuous improvement, and knowledge sharing within the blue team and threat hunting community.

🔍 What’s Inside
KQL queries for hunting lateral movement, privilege escalation, credential access, persistence, exfiltration, cloud abuse, and more.

Ready-to-use queries for Defender XDR, Sentinel, and custom Azure Data Explorer environments.

MITRE ATT&CK mapping, recommended use cases, and detection context for each query.

Example outputs, result interpretation, and analyst tips.

📖 Usage

Copy-paste queries into the Microsoft Defender Advanced Hunting portal, Azure Sentinel Logs, or Azure Data Explorer.

Tune queries as needed for your environment (e.g., whitelisting admin tools, changing thresholds, adding allowlists).

Correlate results with SIEM incidents, alerts, and additional telemetry for effective investigations.

Contribute: Submit improvements, new queries, or mapped techniques via Pull Requests!

🛡️ Best Practices
Always review and adapt queries to fit your organization’s environment.

Use join, summarize, and project operators for advanced correlations and context enrichment.

Test new queries in a lab or non-production environment before wide deployment.

Stay current: Regularly check for new threats and update your hunting logic.


👥 Who Should Use This Repo?
Threat Hunters & SOC Analysts

Incident Responders

Security Engineers & Blue Teams

Red Teamers (for detection engineering validation)

📬 Feedback & Contributions
Feel free to open Issues for improvements, feature requests, or to report bugs.
