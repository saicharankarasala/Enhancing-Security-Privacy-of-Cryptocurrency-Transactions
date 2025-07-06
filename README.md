# 🔐 Enhancing Security & Privacy of Cryptocurrency Transactions

**📅 Duration:** January 2023 – May 2023  
**🎓 Type:** Graduate Research Project  
**👨‍💻 Role:** Java Developer & Security Analyst  
**🧠 Focus:** Cryptographic Security, Transaction Integrity, Threat Simulation

---

## 📌 Project Summary

This project explores how **advanced encryption** and **custom transaction validation logic** can be applied to improve the **security and privacy of cryptocurrency transactions**. The goal was to simulate a transaction flow similar to modern blockchain platforms and protect user data using **AES encryption** and proper validation rules.

We tested for common vulnerabilities like **replay attacks**, **data tampering**, and **unauthorized access**, and documented improvements to strengthen the system.


## 🔐 Key Features

### 🧬 AES Encryption for Wallet Data
- Wallet data (private keys, user info) is encrypted using **AES-256** with securely generated keys.
- Prevents raw access to sensitive information, even if breached.

### 🔍 Custom Transaction Validation
- Transactions undergo checks for **duplicate IDs**, **tampered amounts**, and **invalid signatures**.
- Logic simulates behavior of real blockchain platforms and ensures **integrity**.

### ⚔️ Attack Simulations
- Conducted manual simulations of:
  - **Replay attacks** (re-sending valid transactions maliciously)
  - **Tampering attacks** (modifying values post-signing)
- Verified that only valid, untampered transactions proceed.

### 📉 Performance Awareness
- Designed encryption and validation modules to minimize processing time.
- Prioritized a balance between **security and system responsiveness**.

---

## 🛠️ Tools & Technologies

| Area             | Tools/Technologies Used                     |
|------------------|----------------------------------------------|
| Programming      | **Java 17**, **Java Cryptography Extension** |
| Encryption       | **AES-256**, **SecureRandom**, **SHA-256**  |
| Validation       | Custom Java classes                         |
| Simulation       | Manual test cases, edge case modeling        |
| Documentation    | **Notion**, **Lucidchart**, **Google Docs**  |
| Collaboration    | GitHub, shared docs, group reviews           |

---

## 📷 Flowchart – Encryption & Validation Flow

![Crypto Security Flowchart](https://github.com/saicharankarasala/Enhancing-Security-Privacy-of-Cryptocurrency-Transactions/blob/main/flowchart.jpg?raw=true)

> _Illustration: Flowchart showing wallet encryption, transaction validation, and handling logic._

---

## 🤝 Collaboration

This was a **team-based project**:
- I led the implementation of the **Java encryption modules**
- Worked on **risk analysis and threat modeling**
- Contributed to final presentation and documentation

We used a sprint-based approach, tracked progress in Notion, and conducted weekly code reviews using GitHub.

---

## 📈 Outcomes

- ✅ Created a working simulation of a secure crypto transaction system.
- ✅ Identified 4 major vulnerabilities during threat modeling and mitigated them.
- ✅ Delivered a final presentation and report outlining encryption strategies and results.
- ✅ Gained hands-on skills in **cryptography**, **secure development**, and **collaborative security planning**.

---

## 🧠 Learnings

- How to apply **cryptographic principles** like AES and hashing in real projects.
- Designing and writing **modular, testable Java code** for sensitive applications.
- Approaching development from a **security-first mindset**, including testing against misuse.

---

## 🔮 Future Improvements

- 🔁 Upgrade to **asymmetric encryption (RSA or ECC)** for secure key exchange.
- 🌐 Connect to Ethereum testnets like **Goerli** to simulate real-world blockchain behavior.
- 📊 Add dashboards for transaction logging and threat detection using **Grafana** or **Prometheus**.
- 🔐 Use secret vaults like **HashiCorp Vault** or **AWS KMS** to securely store encryption keys.

---

## 📬 Contact

**Venkata Sai Charan Karasala**  
📧 kvscharan11@gmail.com  
🌐 [LinkedIn](https://linkedin.com/in/sai-charan-k-v)  
💻 [GitHub](https://github.com/saicharankarasala)

---

> ⚠️ Disclaimer: This project was built for academic and learning purposes and is not meant for production-level use in real cryptocurrency systems.
