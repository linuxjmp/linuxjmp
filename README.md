# Hi, I'm Jaric

Linux Systems / Infrastructure Engineering portfolio focused on building repeatable, secure, and observable Linux environments.

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![RHEL](https://img.shields.io/badge/RHEL-EE0000?style=flat&logo=redhat&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

## Core Focus Areas

- RHEL-compatible Linux administration
- Ansible automation
- Baseline hardening
- Patch and rollback workflows
- Monitoring with Prometheus and Grafana
- Incident response and validation
- firewalld, SELinux, auditd, systemd, rsyslog
- Virtualized lab environments on Proxmox/KVM
- Practical cloud infrastructure foundations

## Featured Infrastructure Labs

### 1. RHEL OE Build Lab
**[rhel-oe-build-lab](https://github.com/linuxjmp/rhel-oe-build-lab)** — An Ansible-driven operating-environment lab that takes a base RHEL-compatible host to a hardened, patched, validated baseline. It covers the full operational loop: baseline hardening (SELinux, firewalld, auditd, chrony, sudo/admin users), quarterly patching with rollback planning, post-change validation reports, and change-control records. Built with reusable Ansible roles and playbooks so the same operating environment is reproducible across hosts.

### 2. Linux Monitoring & Incident Response Lab
**[linux-monitoring-ir-lab](https://github.com/linuxjmp/linux-monitoring-ir-lab)** — A monitoring and incident-response lab using Prometheus, Grafana, and node_exporter, with the stack delivered as Podman Quadlet units under systemd. It demonstrates operational health checks, service troubleshooting, and a practical incident-response workflow: detect from metrics, review logs, isolate the failing service, and confirm recovery.

### 3. Virtualized Mission Network Lab
**[virtualized-mission-network-lab](https://github.com/linuxjmp/virtualized-mission-network-lab)** — A multi-host Linux infrastructure lab that builds a segmented network of services on KVM. It covers firewalld zone design, an nginx application tier, centralized logging with rsyslog, and Ansible-based deployment across hosts — with validation and change management to keep the environment repeatable.

### 4. RHEL9 Server Hardening
**[rhel9-server-hardening](https://github.com/linuxjmp/rhel9-server-hardening)** — A foundational RHEL 9 hardening lab focused on practical, RHCSA-aligned server security: SSH hardening, firewalld, SELinux, fail2ban, a dnf update workflow, and audit scripts that confirm the baseline holds.

### 5. Azure SIEM Live Attack
**[azuresiemliveattack](https://github.com/linuxjmp/azuresiemliveattack)** — A supporting security-awareness project demonstrating SIEM exposure, log analysis, and attack-visibility concepts with Azure Sentinel. Included to round out my security awareness; the core of this portfolio is Linux infrastructure engineering.

## Infrastructure Problems I Can Help With

- Turn manual Linux setup steps into repeatable Ansible workflows
- Create baseline hardening checklists for Linux servers
- Build patching and validation workflows
- Set up basic Linux monitoring with Prometheus and Grafana
- Troubleshoot systemd services, firewall rules, SELinux issues, and logs
- Write clear operational documentation and runbooks

## How I Build Labs

Each lab is designed around:

1. Problem
2. Architecture
3. Implementation
4. Validation
5. Failure modes
6. Security considerations
7. Screenshots or command evidence
8. Lessons learned

## Current Build Direction

I build practical Linux infrastructure labs that show how I think through production-style operations:

- Automate the baseline
- Validate the result
- Document the change
- Identify failure modes
- Make the environment repeatable

Next, I am expanding the portfolio with a cloud infrastructure foundation lab that connects Linux administration, Terraform/OpenTofu, Ansible, monitoring, and secure remote access.

## Connect

[LinkedIn](https://www.linkedin.com/in/jaric-poinsette-178217230/)
