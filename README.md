# PC Wizards Inc. Website (`pcwizardsinc.com`)
Welcome to the official repository for **PC Wizards Inc.** ([www.pcwizardsinc.com](https://www.pcwizardsinc.com)), also known as **Pacific Computer Wizards**. 

This repository powers the static website hosted via **Cloudflare Pages**. It serves as a personal digital scratchpad, open-source tech repository, cyber threat intelligence distribution node, and custom engineering notebook.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Website Sections & Content](#-website-sections--content)
  - [1. Computer Stuff & Knowledge Base (`/services`)](#1-computer-stuff--knowledge-base-services)
  - [2. The Garage & Motorcycle Technical Guides (`/motorcycles`)](#2-the-garage--motorcycle-technical-guides-motorcycles)
  - [3. UAS & Drone Flight Operations (`/drones`)](#3-uas--drone-flight-operations-drones)


---

## 🌐 Overview

**PC Wizards Inc.** was created by a Pacific Northwest technologist and hobbyist as a curated space for sharing field notes, technical guides, custom software, and outdoor project documentation. 

Originally hosted on Google Sites (`chadick.org`), the platform was migrated to a custom static site architecture hosted on Cloudflare Pages for improved performance, security, and version control.

---

## 📚 Website Sections & Content

### 1. Computer Stuff & Knowledge Base (`/services`)
Also known as **"Wizard's Memory"**, this section contains Linux guides, cybersecurity tools, and system administration scripts:

* 📱 **Android RF Survey & Scanner App:**
  * Single-screen diagnostic tool designed for hardware-level RF spectrum auditing.
  * Optimized for modern flagships (e.g., Samsung Galaxy S2x Ultra) running Android 12+ (API 31+).
  * Audits **Dual-Band L1+L5 GNSS**, **Bluetooth 5.x LE Coded PHY**, **Wi-Fi 6E/7 (2.4/5/6 GHz)**, and **NFC**.
  * Features spatial mapping export (`.kml`, `.geojson`), meter-scale ranging (802.11mc FTM), and raw telemetry logging.
* 🛡️ **Law Enforcement & Government Cyber Threat Feed:**
  * Public-sector CTI aggregated DNS blocklist stripping raw IPs for clean domain filtering.
  * Compatible with **Pi-hole**, **AdGuard Home**, and enterprise DNS sinkholes via raw GitHub updates.
* 🐧 **Fedora 44 Post-Install Automation Utility:**
  * Interactive Bash script automating post-installation tasks: RPM Fusion, Flathub, media codecs, and NVIDIA driver setup.
  * Native handling for **Secure Boot** via `mokutil` and Machine Owner Key (MOK) generation.
* 🔊 **Apple iMac Intel Cirrus Audio Driver Patch:**
  * Step-by-step setup script (`snd_hda_macbookpro`) to enable audio output on Apple iMac 18,3 running Fedora 43/44 Workstation.

---

### 2. The Garage & Motorcycle Technical Guides (`/motorcycles`)
A comprehensive operational manual and mechanics journal for a **2008 Honda Goldwing** retrofitted with a **Tilting Motor Works (TMW) TRIO** reverse-trike conversion and **Tilt-Lock** system:

* **Riding Dynamics & Safety:** Detailed analysis of the counter-steering vs. trike handling modes, navigating the critical **6–8 MPH transition zone**, and muscle memory rules for rider safety.
* **Service & Maintenance:** Guidance on special tooling (TMW center lug wrench), custom brake rotor sourcing, hydraulic fluid maintenance, and front shock alignment (12-thread baseline).
* **Fault Diagnostics:** Quick-reference troubleshooting guide for electronic/hydraulic Tilt-Lock fault codes (solid red light indicator, quadrature sensor errors, solenoid faults).

---

### 3. UAS & Drone Flight Operations (`/drones`)
A collection of aerial video logs, custom ground station builds, and flight testing across the Pacific Northwest:

* **DJI Avata 360:** Trail runs, tight tunnel passes, and 360-degree fireworks capture setup connected to a mobile Lenovo laptop station.
* **DJI Mini 2 Operations:** Night strobe flights, winter snow sweeps (Tipsy Canyon Winery, Bradley Lake), and sidecar tracking runs.

---

## 📂 Repository Structure

```text
pcwizards-website/
├── index.html            # Main landing page & digital scratchpad overview
├── services.html         # Computer Stuff / Wizard's Memory Knowledge Base
├── drones.html           # UAS & Drone project log & embedded video showcase
├── motorcycles.html      # TMW TRIO Honda Goldwing operational guide
├── css/                  # Main stylesheet files
├── js/                   # Lightweight site interactivity scripts
├── images/               # High-resolution project photos & asset gallery
│   ├── trio-goldwing/    # Images of Tilting Motor Works builds
│   ├── drones/           # Drone setups and aerial photos
│   └── sidecars/         # Sidecar adventure imagery
├── domain_blocklist.txt  # DNS blocklist feed for Pi-hole/AdGuard Home
└── README.md             # Repository documentation
