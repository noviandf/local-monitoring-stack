# Local IT Infrastructure & Network Monitoring Stack

Docker-based monitoring infrastructure for local network environments, handling real-time availability tracking, SNMP metric collection, and hardware telemetry visualization.

## 🏗️ Architecture & Services

* **Uptime Kuma (Port 3001):** Real-time service uptime & ping monitor (VMs, Routers, PBX Softphone endpoints).
* **Grafana (Port 3000):** Visual analytics & dashboarding for network traffic, CPU/RAM utilization, and hardware telemetry.
* **Prometheus (Port 9090):** Time-series database acting as data scraper and metric storage.
* **SNMP Exporter (Port 9116):** Bridge for collecting SNMP v2/v3 data from MikroTik routers and switch gear.

## 🚀 Quick Start

1. Clone this repository:
   ```bash
   git clone [https://github.com/noviandf/local-monitoring-stack.git](https://github.com/noviandf/local-monitoring-stack.git)
   cd local-monitoring-stack
