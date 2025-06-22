<div align="center">

# **Recommended Tools Collection**

[![Made With Markdown](https://img.shields.io/badge/Made%20With-Markdown-1f425f.svg)](https://commonmark.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Last Update](https://img.shields.io/badge/last%20update-June%202025-blue.svg)]()

</div>

This repository lists **recommended tools** across **networking**, **data analytics**, **NAS**, and **backup/restore** domains. The goal is to support **practical learning**, **experimentation**, and **professional deployment** of infrastructure solutions.

---

## Table of Contents

- [Network Related Tools](#-network-related-tools)
- [Database and Data Analytics Tools](#-database-and-data-analytics-tools)
- [NAS (Network-Attached Storage) Tools](#-nas-network-attached-storage-tools)
- [Backup and Restoration Tools](#-backup-and-restoration-tools)

---

##  **Network Related Tools**

### [**Cisco Packet Tracer**](https://www.netacad.com/courses/packet-tracer)
**Platforms:** Windows / MacOS / Ubuntu  \
A network configuration simulation tool. Helps hone networking configuration skills from your desktop. Great for experimenting while building, managing, and securing infrastructures.

### [**NMap / Zenmap**](https://nmap.org/zenmap/)
**Platforms:** Windows / MacOS / Linux (rpm) / BSD  \
Security scanner GUI. Powerful tool for network discovery and auditing.

### [**Wireshark**](https://www.wireshark.org/)
**Platforms:** Windows / MacOS  \
The de facto network protocol analyzer. Deep packet inspection and protocol dissection.

### **Additional Tools:**
- [**GNS3**](https://www.gns3.com/) – Network emulator for lab environments.  
- [**Netcat (nc)**](https://linux.die.net/man/1/nc) – Lightweight CLI-based networking tool.  
- [**IPerf3**](https://iperf.fr/) – Bandwidth and network performance measurement.  
- [**OpenWRT**](https://openwrt.org/) / [**pfSense**](https://www.pfsense.org/) – Router/firewall platforms for simulation or live routing labs.

---

##  **Database and Data Analytics Tools**

### [**SQL Tutorial – w3schools**](https://www.w3schools.com/sql/)
**Platform:** Web-based  \
Interactive SQL practice and tutorials.

### [**Tableau Public**](https://public.tableau.com/)
**Platform:** Web-based / Windows  \
Explore, create, and share data visualizations online.

### [**Power Apps**](https://learn.microsoft.com/en-us/power-apps/)
**Platform:** Microsoft Power Platform  \
Low-code app platform for building custom business apps connected to your data.

### **Additional Tools:**
- [**Power BI**](https://powerbi.microsoft.com/) – Microsoft’s data analytics and reporting tool.  
- [**DBeaver**](https://dbeaver.io/) – Universal SQL client with GUI support.  
- [**Metabase**](https://www.metabase.com/) – Self-hosted BI dashboard for easy visualizations.  
- [**Apache Superset**](https://superset.apache.org/) – Enterprise-grade open-source BI platform.  
- [**DB Browser for SQLite**](https://sqlitebrowser.org/) – Lightweight GUI SQL browser.

---

##  **NAS (Network-Attached Storage) Tools**

### [**Unraid**](https://unraid.net/)
Flexible NAS solution ideal for media servers and virtualization.

### [**Nextcloud**](https://nextcloud.com/)
Scalable, self-hosted cloud and NAS suite with calendar, contacts, and file sync.

### [**OpenMediaVault**](https://www.openmediavault.org/)
Debian-based easy-to-use NAS distribution.

### [**TrueNAS (formerly FreeNAS)**](https://www.truenas.com/)
Enterprise-grade NAS with ZFS, plugins, snapshot support.

### [**Ubuntu Server with Webmin**](https://www.webmin.com/deb.html)
Customizable and secure server-based NAS used with Webmin (10+ years in production).

### **Kubernetes & Distro Support:**
- **Unraid:** [GitHub community Docker/K8s plugins](https://forums.unraid.net/forum/47-docker-containers/)  
- **Nextcloud:** [Official Helm charts](https://github.com/nextcloud/helm) & Docker images  
- **TrueNAS:** [K3s + Docker support](https://www.truenas.com/docs/scale/)  
- **Ubuntu:** Native K8s via [`kubeadm`](https://kubernetes.io/docs/setup/) or [`microk8s`](https://microk8s.io/)

### **Additional Tools:**
- [**Proxmox VE**](https://www.proxmox.com/en/proxmox-ve) – NAS + VM hypervisor with ZFS and backup integration.  
- [**Syncthing**](https://syncthing.net/) – Encrypted P2P syncing system.  
- [**Seafile**](https://www.seafile.com/) – Lightweight alternative to Nextcloud.

---

##  **Backup and Restoration Tools**

### [**Restic**](https://restic.net/)
Fast, encrypted, deduplicated backup solution.

### [**Duplicati**](https://www.duplicati.com/)
Web-based, encrypted backup to cloud and local storage.

### [**BorgBackup**](https://www.borgbackup.org/)
Deduplicating backup with compression and security.

### [**Timeshift**](https://github.com/teejee2008/timeshift)
Linux-only system restore tool (like Windows restore point).

### [**Veeam Backup & Replication (Community Edition)**](https://www.veeam.com/virtual-machine-backup-solution-free.html)
Powerful Windows backup system for VMs and bare-metal recovery.

### [**Rclone**](https://rclone.org/)
CLI tool to sync files with over 40+ cloud providers.

### [**UrBackup**](https://www.urbackup.org/)
Client-server backup for both file and image-based systems.

---

>  **Feel free to contribute** tools or tutorials via pull requests. This list evolves with technology and use cases.

