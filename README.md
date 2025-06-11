# 🧪 RP HomeLab Configuration Repository

Welcome to the **RP HomeLab** repository!  
This repository hosts the **public-facing configuration files** and documentation for my personal homelab infrastructure, intended for learning, reference, and knowledge sharing.

---

## 🌐 Overview

My homelab setup is a self-hosted, production-like environment used for experimenting with tools, technologies, and service orchestration. It includes a mix of physical and virtual infrastructure, DNS, monitoring, automation, service deployment, and more.

This repository documents:
- Infrastructure layout
- Configuration templates
- Stack files
- Monitoring tools
- Dashboard definitions
- Publicly shareable automation scripts

> 🚫 **Note:** All sensitive, private, or security-related data/configs are excluded from this repo.

---

## 🧩 Components Covered

### 🖥️ Infrastructure
- Server naming conventions
- IP addressing scheme
- Network layout and topology

### 🧠 Core Services
- DNS (BIND9 zone files and config)
- DHCP & Static Reservations (template)
- NGINX Proxy Manager
- Home Assistant configurations (public parts)
- Mail server setup (Postfix, IMAP, etc.)
- Zabbix / Uptime Kuma monitoring
- Portainer stack templates

### ⚙️ Automation & Ops
- Jenkins CI job templates
- Rundeck job exports
- GitLab integration for GitOps workflows
- Custom scripts for deployment/maintenance

### 📈 Observability
- Zabbix templates (non-sensitive)
- Grafana dashboard exports
- SNMP monitoring examples

### 📦 Docker / Portainer
- Stack deployment YAMLs
- Compose templates for services

---

## 📂 Directory Structure

```

HomeLab
├── Homepage-Dashboard
│   └── compose
│       └── docker-compose.yml
├── LICENSE
└── README.md


```

---

## 🚀 Goals

- Document a reproducible and structured homelab setup
- Serve as a knowledge base for common homelab tools
- Share configurations with the open-source community
- Act as a reference for future upgrades and audits

---

## 🔒 What’s Not Included

To protect the security of the environment, the following are **not** included:
- Secrets / passwords / API keys
- Internal user credentials
- Private Git repositories or tokens
- Security-sensitive configuration details

---

## 📬 Contact

Maintained by **Rajesh Prashanth Anandavadivel**  
📧 [rajeshprasanth@rediffmail.com](mailto:rajeshprasanth@rediffmail.com)  
🌐 [rphomelab.in](http://rphomelab.in) (for internal access)

---

## 📜 License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.  
See the [LICENSE](./LICENSE) file for more details.

---

> ⭐ If you find this helpful or want to learn from a structured homelab setup, consider starring the repo!
```

---

Let me know if you'd like this automatically added to the repo or customized with any extra sections like badges, services map, or contributors.
