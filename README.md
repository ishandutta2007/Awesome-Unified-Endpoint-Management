# Awesome-Unified-Endpoint-Management

## Top Unified Endpoint Management (UEM) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Device Management, MDM, Inventory, Policy Enforcement, Software Deployment, Remote Assistance & Cross-Platform Endpoint Security*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Unified Endpoint Management (UEM)**. These tools enable organizations to inventory, configure, secure, update, and remotely manage desktops, laptops, mobile devices, and other endpoints from a single console across Windows, macOS, Linux, iOS, Android, and more.



**Examples** include Microsoft Intune, VMware Workspace ONE (Omnissa), Ivanti Neurons, IBM MaaS360, Hexnode, Scalefusion, SOTI, ManageEngine Endpoint Central, Jamf, and Kandji (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted MDM/UEM, cross-platform agents, Apple-focused servers, inventory systems, and modern device management platforms — ideal for IT teams, MSPs, and organizations seeking full control, transparency, and freedom from per-device licensing.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Product | Description | Starting Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Microsoft Intune](https://www.microsoft.com/en-us/security/business/microsoft-intune)** | Cloud-native UEM platform tightly integrated with Microsoft 365, Entra ID, and Defender for managing Windows, macOS, iOS, Android, and Linux. | Starts at **$8.00/user/month** (Intune Plan 1, billed annually) | No permanent free tier; **30-day free trial** with up to **25 user licenses** |
| **[VMware Workspace ONE (Omnissa)](https://www.omnissa.com/)** | Comprehensive UEM solution for managing devices, applications, and access across diverse platforms with robust identity, compliance, and digital workspace features. | Starts at **~$3.78 – $5.00/device/month** (Mobile / UEM Essentials tier) | No permanent free tier; **30-day free trial** (up to **100 devices** via sales/partner evaluation) |
| **[Ivanti Neurons](https://www.ivanti.com/)** | AI-powered UEM platform focused on unified management of endpoints, automation, patching, and security for complex, multi-OS enterprise environments. | Starts at **~$7.50/device/month** (~$90/device/year or ~$25–$59/user/year) | No permanent free tier; **30-day evaluation / Proof-of-Concept (POC)** environment upon sales request |
| **[IBM MaaS360](https://www.ibm.com/products/maas360)** | AI-enhanced UEM solution supporting a wide range of devices with strong security, compliance, and industry-specific capabilities. | Starts at **$4.00/device/month** (Essentials Edition; Fast Start promos from $1.50/device/month) | No permanent free tier; **30-day free trial** with full feature access and unlimited test device enrollment |
| **[Hexnode](https://www.hexnode.com/)** | Modern UEM platform offering device management, kiosk mode, app management, and security features for Windows, macOS, iOS, Android, and more. | Starts at **$2.00/device/month** (Pro plan, billed annually; 15-device minimum) | No permanent free tier; **14-day free trial** with full Ultra tier features and **unlimited devices** (no credit card required) |
| **[Scalefusion](https://scalefusion.com/)** | Unified endpoint management solution strong in multi-platform support, kiosk deployments, content management, and remote troubleshooting. | Starts at **$2.00/device/month** (Essentials plan, billed annually; 10-device minimum) | No permanent free tier; **14-day free trial** with full Enterprise features and **unlimited devices** (no credit card required) |
| **[SOTI](https://www.soti.net/)** | Enterprise mobility and UEM platform specializing in rugged devices, IoT, and advanced mobile device management capabilities. | Starts at **~$4.00/device/month** (Cloud entry tier) | No permanent free tier; **30-day free trial** with full platform capabilities |
| **[ManageEngine Endpoint Central](https://www.manageengine.com/products/desktop-central/)** | On-premises and cloud UEM solution covering patch management, software deployment, remote control, and endpoint security for Windows, macOS, and Linux. | Starts at **~$795/year for 50 endpoints** (~$1.33/endpoint/month) | **Free forever plan** for up to **25 computers and 25 mobile devices**; also offers a **30-day fully functional free trial** |
| **[Jamf](https://www.jamf.com/)** | Leading Apple-focused device management platform (Jamf Pro, Jamf Now) for macOS, iOS, iPadOS, and tvOS with deep integration into Apple ecosystems. | Jamf Now starts at **$4.00/device/month**; Jamf Pro starts at **$5.75/mobile & $12.50/Mac/month** (25-device min) | **Free forever plan** on Jamf Now for up to **3 devices**; Jamf Pro offers a **14-day to 30-day free trial** via sales request |
| **[Kandji](https://www.kandji.io/)** | Modern, Apple-centric MDM/UEM platform emphasizing automation, compliance blueprints, and streamlined management for Mac and iOS fleets. | Starts at **~$3.20 – $4.00/device/month** (Core Apple MDM starting tier) | No permanent free tier; **14-day free trial** for core MDM/UEM features (no credit card required) |



## Open-Source GitHub Projects



- **[OpenUEM](https://github.com/open-uem)**  

  Fully open-source, self-hosted Unified Endpoint Manager with agents for Windows/Linux/macOS, inventory, software deployment (Winget/Flatpak/Homebrew), profiles, remote assistance (VNC/RDP), and a clean web console.



- **[Fleet](https://github.com/fleetdm/fleet)**  

  Leading open-source device management and security platform built on osquery. Supports macOS, Windows, Linux, and more with GitOps workflows, real-time visibility, and MDM capabilities.



- **[MicroMDM](https://github.com/micromdm/micromdm)**  

  Lightweight, open-source Apple MDM server focused on the core MDM protocol, SCEP, and API-driven management of iOS and macOS devices.



- **[NanoMDM](https://github.com/micromdm/nanomdm)**  

  Minimalist, modern open-source Apple MDM server designed for simplicity, multi-APNs support, and flexible storage backends.



- **[myMDM](https://github.com/mymdm/mymdm)**  

  Comprehensive open-source multi-platform MDM covering Apple, Windows, Android, Linux, ChromeOS with full policy engine, enrollment, app management, and identity federation.



- **[Commandment](https://github.com/cmdmnt/commandment)**  

  Open-source Apple MDM implemented in Python for managing iOS and macOS devices with support for profiles, commands, and community-driven development.



- **[Headwind MDM](https://h-mdm.com/)**  

  Open-source Android-focused MDM solution strong in kiosk mode, remote control, and on-premises management of Android fleets.



- **[osquery](https://github.com/osquery/osquery)**  

  Foundational open-source endpoint visibility agent that exposes operating system data as SQL tables — the core of many modern UEM and security platforms including Fleet.



- **[OCS Inventory NG](https://github.com/OCSInventory-NG)**  

  Mature open-source inventory and package deployment system supporting Windows, Linux, macOS, and other platforms with agent-based discovery.



### Additional Strong Open-Source Options



- **Apple-centric**: Additional community forks and tools around the Apple MDM protocol, ABM/ASM integrations, and profile management.

- **Cross-platform agents**: Various inventory and remote management agents that pair with custom consoles.

- **Patch & software deployment**: Chocolatey, Winget wrappers, and open package management tools that integrate with UEM workflows.

- **Remote assistance**: Open-source VNC/RDP/RustDesk integrations commonly used alongside self-hosted UEM.

- **Security & compliance**: Community projects for CIS benchmarking, vulnerability scanning, and policy-as-code on endpoints.

- Many emerging **Linux-first** and **multi-OS** management prototypes on GitHub.



**Frameworks for building custom systems**: Start with **Fleet** or **OpenUEM** for a full cross-platform experience, use **MicroMDM/NanoMDM** for deep Apple control, layer **osquery** for rich inventory and querying, and combine with configuration management (Ansible, Puppet) and remote tools for complete endpoint lifecycle management.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Unified Endpoint Management tools handle sensitive device and user data and must comply with privacy regulations, security standards, and organizational policies.

- Self-hosted open-source solutions require proper certificate management (especially for Apple MDM), secure agent communication, access controls, and ongoing maintenance for production reliability and compliance.



---



**Made for IT administrators, MSPs, security teams, and organizations seeking open, controllable endpoint management.**  

Let's make device management more transparent, flexible, and community-driven.
