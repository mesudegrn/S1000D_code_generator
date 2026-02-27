S100D Data Module Code Generator for UAV Systems
🚀 Overview
This project is a specialized VBA-powered Excel tool developed for UAV (Unmanned Aerial Vehicle) System Engineers. It automates the generation of S100D compliant Data Module Codes (DMC) through an intuitive, selection-based interface.

By utilizing dynamic dropdowns and automated logic, the tool eliminates manual entry errors and ensures that technical documentation aligns perfectly with international aerospace standards (ASD S100D).
<img width="1865" height="616" alt="Ekran görüntüsü 2026-02-27 143219" src="https://github.com/user-attachments/assets/83bda22e-6a17-43a1-8356-ee8453b017e4" />

✨ Key Features
Dropdown-Driven Logic: Generate complex codes by simply selecting system parameters from pre-defined menus.

UAV SNS Mapping: Integrated with Standard Numbering System (SNS) structures specific to Unmanned Aerial Systems.

One-Click Generation: A dedicated VBA engine that processes selections and outputs standardized strings instantly.

Data Export Functionality: Seamlessly transfer generated codes to master lists or external databases with the built-in export button.

Zero-Footprint Deployment: No installation required—runs entirely within Microsoft Excel, the primary workspace for most systems engineers.

📋 How It Works
The tool is designed with a "Single Source of Truth" approach. Users follow a guided workflow on the main dashboard:

Selection Phase:

Category (Kategori): Select the high-level domain (e.g., Ground Systems).

System (Sistem Adı): Choose the major functional system (e.g., Equipment/Furnishings).

Sub-system (Altsistem Adı): Define the secondary technical layer.

Sub-category (Alt Kategori): Drill down to the specific assembly or component level.

Code Generation: * Click the "Kod Üretmek İçin Tıklayınız" (Click to Generate Code) button.

The macro concatenates the relevant indices to create the final S100D code (e.g., 125.31.001).

Export:

Click the "Output Verilerini Aktarmak İçin Tıklayınız" (Click to Export Output Data) button to save or transfer the result for use in Technical Publications (IETM/IETP).

🛠 Technical Specifications
Language: VBA (Visual Basic for Applications)

Environment: Microsoft Excel (Macro-Enabled .xlsm)

Standard: ASD S100D Compliance

💡 Motivation
"System engineering is about precision. Manual coding of S100D modules is a relic of the past. This tool was created to let engineers focus on design while the macro handles the documentation compliance."

🚀 Getting Started
Download the .xlsm file from the repository.

Open Excel and Enable Macros when prompted.

Use the dashboard to start generating your UAV system codes.
