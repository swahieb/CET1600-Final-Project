# CET1600 Final Project – Subnetting & Router Configuration

This is my final project for CET1600 (Fall 2024), completed in Cisco Packet Tracer. It demonstrates IP subnetting, router interface setup, PC configuration, and connectivity testing. All instructions were followed exactly as outlined in the final exam directions.

---

## Project Instructions (from Final Exam)

> **Objective:**  
> Subnet the network `192.168.166.0/24` into two subnets:
>
> - One subnet for **79 hosts** (connected to Router interface **Fa0/0**)  
> - One subnet for **102 hosts** (connected to Router interface **Fa0/1**)  
>
> Assign:
> - The **first valid host IP** of each subnet to the router interface  
> - The **next available host IPs** to the PCs  
>
> Verify connectivity by pinging from each PC to the router, and between PCs.

---

## Project Summary

- Subnetted `192.168.166.0/24` into two `/25` subnets
  - **Subnet A (79 hosts):** 192.168.166.0/25
    - Router Fa0/0: `192.168.166.1`
    - PC0: `192.168.166.2`
  - **Subnet B (102 hosts):** 192.168.166.128/25
    - Router Fa0/1: `192.168.166.129`
    - PC1: `192.168.166.130`
- Manually configured:
  - PC IPs
  - Router interfaces (using CLI)
- Verified successful ping connectivity between devices

---

## 📁 Files Included

- `CET1600-Samaa-Wahieb.pkt` – Main Cisco Packet Tracer project file
- `CET1600_Final_Report_Samaa_Wahieb.pdf` – PDF with screenshots and documentation
- `.jpeg` screenshots – Router configs, PC IP settings, CLI, and topology

---

##  Tools Used

- Cisco Packet Tracer 8.x
- Static IP addressing
- Router CLI configuration
- PC interface setup
- Ping testing across subnets

---

## Author

**Samaa Wahieb**  
CET1600 – Fall 2024  
Instructor: Miguel Ciena
