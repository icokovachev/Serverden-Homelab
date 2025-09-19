# 🏡 My Homelab  

Welcome to my personal **homelab repository** — a place where I experiment, learn, and document my journey of building and managing a home datacenter.  
This repo contains **notes, configurations, and automation scripts** that keep my lab running smoothly.  

---

## 🌐 Networking  

| Device | Role |
|--------|------|
| **TP-LINK AX53** | Temporary router *(ISP restrictions prevent upgrade for now)* |
| **Cisco SG200-50** | Gigabit Smart Switch — provides connectivity for servers and workstations |

---

## 🖥️ Hardware  

| Server | Specs | Storage | Services |
|--------|-------|---------|----------|
| **🔹 Alpha** | Intel Xeon **E3-1270 v6** (4c/8t) <br> 32GB DDR4 <br> ASRock Rack E3C236D4M-4L | 250GB SATA SSD *(boot)* <br> 2×500GB HDD *(RAID 1 work disk)* <br> 1TB HDD *(ISOs / templates / general storage)* | 🧪 Work projects & experiments <br> 🗄️ Databases for testing |
| **🔹 Beta** | Intel Core **i5-12400F** (6c/12t) <br> 64GB DDR4 <br> Gigabyte B660 DS3H AX DDR4 <br> Nvidia Quadro P620 | 500GB NVMe SSD *(boot)* <br> 2×16TB Seagate IronWolf Pro *(mass storage)* | 🌐 Cloudflared tunnel <br> 🔐 WireGuard VPN <br> 🎬 Servarr stack <br> 📺 Jellyfin *(GPU passthrough)* <br> 📦 Samba (LXC storage provider) |
| **🔹 Gamma** | HP DL360 G7 <br> 2× Intel Xeon **X5670** (12c/24t total) <br> 96GB DDR3 | 250GB SSD *(boot)* | ⚡ Non-functional tests (stress, load, spike) <br> 🧪 QA / automation testing |

---

## 🎯 Goals  

- Build a **resilient, production-like environment** at home  
- Learn and apply **DevOps & SRE practices** hands-on  
- Gain expertise in **Infrastructure as Code (IaC)**  
- Automate everything possible — from provisioning to monitoring  
- Share configs and notes to help others build homelabs  
- And most importantly → **have fun!** 🎉  

---

## 🚀 Roadmap  

- [ ] Implement Kubernetes for container orchestration  
- [ ] Expand monitoring stack with Loki & Mimir  
- [ ] Full integration of Terraform + Ansible workflows  
- [ ] Improve CI/CD pipelines for service deployments  
- [ ] Document disaster recovery & backup strategy  

---

## 📚 Inspiration  

This repo is both my **personal logbook** and a **resource for homelab enthusiasts**.  
Contributions, feedback, and ideas are always welcome!  

---
