# Security Operations Center (SOC)

## 📌 Project Objective  
This project aims to create an automated SOC using open-source tools for security monitoring, threat detection, and incident response.  

## 🔧 Tools Used  
- **OPNsense**: Firewall and network protection  
- **Suricata**: Network Intrusion Detection System (IDS/IPS)  
- **Wazuh**: SIEM for log collection and correlation  
- **Elastic Stack (ELK)**: Log visualization with Kibana  
- **OpenCTI**: Threat Intelligence for threat analysis  
- **TheHive & Cortex**: Incident management and automation  
- **Icinga & Netdata**: Infrastructure and performance monitoring  
- **Volweb**: Forensic incident analysis  
- **Ansible, Docker, Kubernetes**: Infrastructure automation and orchestration  

## 🚀 Quick Deployment  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/jkiala2/soc.git
cd soc

### 2️⃣ Deploy with Docker
docker-compose up -d

### 3️⃣ Deploy with Kubernetes
kubectl apply -f k8s/

### 📖 Documentation
Find all documentation in /docs.



 

