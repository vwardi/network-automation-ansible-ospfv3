## Network Automation with Ansible - OSPFv3 - Lab

A hands-on network automation project using Ansible to manage and validate a Cisco OSPFv3 lab topology running IPv4 and IPv6.

The project is built in EVE-NG and is intended to develop practical skills in network automation, infrastructure as code, configuration management, validation, testing, and Git-based workflows.

Project status: Work in progress. Playbooks, documentation, and automated validations will be added progressively.

## Project Objectives

### The main objectives of this project are to:

Automate operational tasks on Cisco IOS routers.<br>
Organize network data using Ansible inventories and variables.<br>
Collect and process operational information from network devices.<br>
Create reusable and idempotent playbooks.<br>
Automate IPv4, IPv6, and OSPFv3 configurations.<br>
Validate the network state before and after changes.<br>
Generate backups, reports, and execution evidence.<br>
Apply Git, Pull Request, testing, and CI/CD practices to network automation.<br>

### The lab currently includes:

- Seven Cisco IOS routers: R1 through R7.<br>
- One Layer 2 switch connecting the OSPF backbone.<br>
- One Ubuntu Server acting as the Ansible control node.<br>
- EVE-NG as the network emulation platform.<br>
- OSPFv3 with IPv4 and IPv6 address families.<br>
- Multiple OSPF areas: 0, 20, 30, and 40.<br>
- Network Topology.<br>

### The OSPFv3 topology is divided into the following areas:

- Area Devices	Description<br>
- Area 0 R1, R2, R3 and R4 OSPF backbone.<br>
- Area 20	R3 and R7 Remote OSPF area.<br>
- Area 30	R1 and R5 Remote OSPF area.<br>
- Area 40	R2 and R6 Remote OSPF area<.<br>

> **Note:** The complete network diagram will be added to the docs/ directory.

### Technologies
- Ansible.<br>
- Cisco IOS.<br>
- OSPFv3.<br>
- IPv4 and IPv6.<br>
- YAML.<br>
- Jinja2.<br>
- Python.<br>
- Linux.<br>
- EVE-NG.<br>
- Git and GitHub.<br>
- GitHub Actions.<br>

---
