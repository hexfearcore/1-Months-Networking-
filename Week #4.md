# 🛡️ Month 1 - Week 4 Extended Plan (Refined): DPI, Firewalls, IDS/IPS, Network Threats, BIOS Security

This week is a **refined extension** based *strictly* on the original Week 4 topics. It includes deeper breakdowns on **DPI**, **firewall/IDS/IPS tech**, **threat prevention**, and **firmware-level protections**.

---

## 📅 Week 4: Refined Breakdown

---

### 📌 Day 1: Deep Packet Inspection (DPI)
- What is DPI? How it differs from basic packet inspection
- DPI layers: Header, Payload, Application-level metadata
- Real-world usage: ISP traffic shaping, malware filtering, censorship
- DPI engines: OpenDPI, nDPI
- DPI evasion techniques:
  - Fragmentation
  - Encryption (HTTPS, VPN)
  - Traffic obfuscation

---

### 📌 Day 2: Firewalls – Types & Internal Mechanics
- What is a firewall? Placement in network topology
- Types of firewalls:
  - Packet-filtering
  - Stateful inspection
  - Proxy-based
  - NGFW (Next-Generation Firewalls)
- Rule construction (source, destination, port, protocol)
- Example: iptables logic breakdown

---

### 📌 Day 3: IDS & IPS – Detection vs. Prevention
- IDS vs. IPS: Core differences
- Host-based IDS (HIDS) vs. Network-based IDS (NIDS)
- Signature-based vs. anomaly-based
- Overview of tools:
  - Snort
  - Suricata
  - OSSEC
- Placement in networks (inline vs. passive)

---

### 📌 Day 4: Bypassing Firewalls, IDS, and IPS
- Techniques to bypass firewalls:
  - Port knocking
  - Tunneling (ICMP, DNS)
  - Traffic fragmentation
- IDS evasion strategies:
  - Polymorphic shellcode
  - Protocol manipulation
  - Fragmentation & TTL manipulation

---

### 📌 Day 5: Network Threats & Security Protections
- Threats:
  - DoS/DDoS
  - MITM
  - DNS Spoofing
  - IP/MAC spoofing
  - VLAN hopping
- Protections:
  - ARP inspection
  - DHCP snooping
  - ACLs
  - Port security

---

### 📌 Day 6: BIOS & Firmware Security
- BIOS vs. UEFI – Roles and architecture
- Common attacks:
  - BIOS password reset
  - Evil Maid attack
  - Firmware rootkits
- Secure Boot explained
- TPM (Trusted Platform Module)
- Firmware update risks

---

### 📌 Day 7: Review & Real-world Scenarios
- Recap of:
  - DPI vs. traditional packet inspection
  - Firewalls & IPS: Role & limitations
  - Bypass techniques and how attackers sneak in
  - BIOS/UEFI protections
- Case study examples (APT attack with firmware persistence)

---

## ✅ Outcome:
By the end of Week 4, you'll have mastered:
- How DPI works and how to evade it
- Functioning of firewalls, IDS, IPS, and how to bypass them
- Core network security threats and how to prevent them
- Firmware-level threats and BIOS/UEFI protection mechanisms