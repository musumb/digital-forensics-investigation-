# Digital Forensics Investigations & Comparative Research

## Overview
This repository contains digital forensics laboratory investigations, forensic data recovery case studies, and practical comparative research on mobile and computer evidence extraction methodologies.

---

## Projects Included

### 1. Android Data Extraction: Commercial vs. Open-Source Methodologies
* **Scope:** Comparative analysis of commercial vs. non-commercial mobile forensic acquisition techniques on rooted Android storage.
* **Tools Used:** Magnet AXIOM (ADB Unlocked) and Android Debug Bridge (ADB CLI).
* **Key Findings:**
  * **Magnet AXIOM:** Automated full file system acquisition, structured artifact parsing (Chrome/Firefox history, contacts, Bluetooth, Wi-Fi logs), automatic hash preservation, and courtroom-ready reporting.
  * **Manual ADB:** High flexibility and raw access to internal `/data/data/` app directories and SQLite databases, but lacks automated parsing, timeline generation, and standardized evidence logging.
* **Forensic Considerations:** Analysis of NAND flash memory mechanics (FTL wear-leveling), legal defensibility of device rooting, and adherence to NIST SP 800-101 Rev. 1 guidelines.
* **Report:** [Android Data Extraction Tools Report]

---

### 2. Digital Forensics Investigation: The National Art Gallery Case
* **Scope:** Forensic examination of an external hard drive image (`tracy-external-2012-07-16-final.E01`) in compliance with ACPO guidelines.
* **Tools Used:** Autopsy Forensic Browser on Windows.
* **Key Findings:** Recovery of encrypted insurance documentation ($260k total valuation), web history analysis, email header reconstruction, and security schedule extraction.
* **Report:** [Digital Forensics Final Report]
