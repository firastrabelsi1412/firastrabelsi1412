# Hi, I'm Firas Trabelsi 👋

**Cybersecurity & Networking engineering student** at the International Institute of Technology (IIT), Sfax, Tunisia. I'm in the ARSI program (Security track), graduating in 2027.

I work where **machine learning meets network defense**: firewalls that learn their own policies, and security audits of real applications.

🎯 **Looking for:** an end-of-studies internship (PFE, 2027) in cybersecurity. I'm especially interested in **Japan**, and also open to remote.

---

## 🔐 Featured projects

### [RL Adaptive Firewall](https://github.com/firastrabelsi1412/rl-adaptive-firewall)
An adaptive firewall that combines a **hybrid LSTM-CNN traffic classifier** with a **PPO reinforcement-learning agent**. The agent decides for each flow whether to ALLOW, BLOCK, RATE-LIMIT or LOG it.
- Trained on NSL-KDD across 5 classes: Normal, DoS, Probe, R2L, U2R. Macro ROC-AUC is 0.90.
- The PPO agent reached a **5.3% false-positive rate vs 9.4%** for the best baseline (44% lower), at the cost of a lower detection rate (62.6% vs 73.6%).
- 🚧 *In progress:* live enforcement through iptables rules on a Mininet gateway.

`Python` `PyTorch` `Stable-Baselines3` `Gymnasium` `iptables` `Mininet`

### [CryptoVault: Mobile Security Audit](https://github.com/firastrabelsi1412/cryptovault-mobile-audit)
A full security audit of a deliberately vulnerable Flutter crypto-wallet app. I found **10 vulnerabilities (16 sub-findings)**, mapped them to OWASP, then fixed them by rewriting the backend with Express, RS256 JWT and HTTPS.
- The MobSF security score rose from **24/100 to 61/100**.
- The repo includes the audit report, evidence, and the fix code for each vulnerability.

`Flutter` `Android` `MobSF` `Burp Suite` `ADB` `Node.js / Express` `JWT`

### [IoT Room Monitoring](https://github.com/firastrabelsi1412/iot-room-monitoring)
A room-monitoring system that sends sensor data from an **ESP32** over **MQTT** to a **PyQt6** desktop dashboard.

`ESP32` `MQTT` `Python` `PyQt6`

---

## 🛠️ Skills

**Security:** network security, firewalls (iptables), mobile application security (OWASP), vulnerability assessment
**Networking:** network simulation (Mininet), virtual labs (EVE-NG)
**ML / AI:** deep learning (PyTorch), reinforcement learning (PPO)
**Languages:** Python, C
**Tools:** Linux, Git, MobSF, Burp Suite, Android Studio

## 🌍 Languages
Arabic (native) · French · English

---

## 📫 Contact
[LinkedIn](https://www.linkedin.com/in/firastrabelsi) · Open to collaboration and internship opportunities
