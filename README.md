# 🌐 Cisco Switch VLAN Configuration

<p align="center">
  <b>Segmenting networks using Virtual LANs on Cisco IOS.</b>
</p>

<p align="center">
  <em>"A hands-on lab log demonstrating the creation of VLANs (HR and IT) and assigning access ports on a Cisco 2960 Switch."</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red" alt="Made with Love">
  <img src="https://img.shields.io/badge/Tool-Cisco%20Packet%20Tracer-blue" alt="Tool">
  <img src="https://img.shields.io/badge/Topic-VLAN-green" alt="Topic">
  <img src="https://img.shields.io/badge/Status-Complete-success" alt="Status">
</p>

---

## 📋 Overview

This repository contains a text-based log (`VLAN.txt`) of a Cisco 2960 Switch configuration. It demonstrates the step-by-step process of booting the switch, accessing the CLI, and configuring VLANs to separate network traffic.

---

## ✨ Key Configurations Shown

* **Switch Boot Process:** The initial hardware POST and IOS loading sequence.
* **VLAN Creation:** Creating `VLAN 10` (named HR) and `VLAN 20` (named IT).
* **Port Assignment:** Assigning specific interfaces (FastEthernet 0/1-2 to HR, 0/3-4 to IT) to their respective VLANs.
* **Troubleshooting:** Shows common CLI errors (like typos in commands) and how to correct them.

---

## 📂 File Structure

```text
cisco-switch-vlan-configuration/
│
├── 📄 VLAN.txt      # Router/Switch configuration log
└── 📄 README.md     # This file
```

---

## 🚀 How to Use

1. **Open Cisco Packet Tracer:** Launch the application.
2. **Add a Switch:** Drag and drop a **Cisco 2960** switch.
3. **Access the CLI:** Click the switch, go to the **CLI** tab, and press Enter.
4. **Apply the Commands:**
   Copy the commands from the `.txt` file and paste them into the CLI.
   ```bash
   enable
   configure terminal
   vlan 10
   name HR
   ```

---

## 🎯 Key Takeaways

* **Network Segmentation:** VLANs logically divide a physical switch into multiple separate networks.
* **Security & Performance:** Reduces broadcast traffic and improves security by isolating departments (HR vs IT).
* **IOS Navigation:** Practice moving between User EXEC, Privileged EXEC, Global Configuration, and Interface Configuration modes.

---

## 👩‍💻 Author

**Iqra Maqsood Mughal**

*Software Engineer · Full-Stack Developer · Code Craftsman · Android App Developer · Problem Solver 🚀*

```javascript
const codeIsLife = "Code is life";
while (true) { learn(); build(); innovate(); }
```

---

## 📅 Date

October 26, 2026

---

## 📄 License

This material is intended for educational and personal study purposes.
