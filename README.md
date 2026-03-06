# FirewallSim Pro 🛡️
**Rule Simulation, Logical Audit, and Regulatory Compliance Platform**

FirewallSim Pro is a high-performance, browser-based simulator designed for Network Security Engineers and Auditors. It allows users to validate complex firewall rulebases, detect logical redundancies (shadowing), and generate audit-ready reports without requiring Python, Java, or any backend infrastructure.



## 🚀 The "Zero-Install" Advantage
In many enterprise and government environments, installing scripting languages like Python is restricted. FirewallSim Pro bypasses these hurdles by leveraging:
- **Pure JavaScript/HTML5**: Runs in any modern browser.
- **Client-Side Processing**: Data never leaves your machine, ensuring security and privacy.
- **Portable Architecture**: Single-file deployment—perfect for offline audit workstations.

## ✨ Key Features
* **Shadow Rule Detection**: Automatically identifies redundant rules that are logically obscured by higher-priority entries.
* **Packet-Level Simulation**: Test specific IP/Port/Protocol combinations against your rulebase to verify "Allow/Deny" verdicts.
* **Regulatory Mapping**: Built-in alignment with **ISO 27001**, **PCI-DSS**, and **MAS TRM** frameworks.
* **Bulk Import/Export**: Supports CSV and Excel (XLSX) rule exports from major vendors (CheckPoint, Cisco, Palo Alto, Fortinet).
* **Executive & Technical Reporting**: Generate instant text-based audit evidence for management and governance teams.



## 🛠️ Tech Stack
- **Frontend**: HTML5, CSS3 (Cyberpunk/Dark UI), Vanilla JS
- **Data Parsing**: [PapaParse](https://www.papaparse.com/) (CSV), [SheetJS](https://sheetjs.com/) (Excel)
- **Visuals**: [Chart.js](https://www.chartjs.org/) for security metrics

## 📖 How to Use
1.  **Clone the Repo**: `git clone https://github.com/your-username/FirewallSimPro.git`
2.  **Open**: Simply double-click `firewall-simulator.html` in your browser.
3.  **Import**: Upload your current rulebase export.
4.  **Audit**: Check the "Rules" tab for yellow highlights (Shadowed Rules).
5.  **Simulate**: Run "Packet Tests" to validate connectivity requests.
6.  **Report**: Go to the "Reports" tab to download your audit evidence.

## ⚖️ Governance & Compliance
This tool specifically helps satisfy:
- **PCI-DSS Requirement 1.2.1**: Justifying and validating network traffic and services.
- **ISO 27001 Control A.13.1.1**: Network management and security control.

---
*Created with focus and precision. Keep your logic sharp and your rules cleaner.*
