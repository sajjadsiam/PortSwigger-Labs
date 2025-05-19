# 🔥 Bug Bounty Learning Plan with PortSwigger Labs

Welcome to your structured path toward mastering web application security and preparing for real-world bug bounty hunting. This roadmap is based on the labs from **[PortSwigger Web Security Academy](https://portswigger.net/web-security)** and tailored to help you grow from beginner to advanced practitioner.

---

## 🧭 PHASE 1: Core Server-Side Vulnerabilities

These are the foundation of 90% of real-world web app vulnerabilities.

| Vulnerability          | Labs Count | Start With  | Notes                                         |
|------------------------|------------|-------------|-----------------------------------------------|
| **SQL Injection**      | 18 labs    | Apprentice  | Easy to learn, but high impact                |
| **Authentication**     | 14 labs    | Apprentice  | Broken auth, 2FA bypass                       |
| **Path Traversal**     | 6 labs     | Apprentice  | File read → often leads to RCE                |
| **Command Injection**  | 5 labs     | Apprentice  | Think: shell commands                         |
| **Access Control**     | 13 labs    | Practitioner| IDOR & privilege escalation                   |
| **Information Disclosure** | 5 labs | Beginner    | Recon goldmine for chaining vulnerabilities   |

✅ **Goal:** Finish all *Apprentice-level* labs for these topics.  
📌 **Tip:** Use **Burp Suite Community Edition** while solving these labs.

---

## 🧠 PHASE 2: Client-Side Vulnerabilities

Learn XSS, CORS, CSRF, and other browser-based attacks.

| Vulnerability                 | Labs Count | Key Focus                              |
|------------------------------|------------|----------------------------------------|
| **Cross-Site Scripting (XSS)** | 30 labs   | Reflected, Stored, DOM                 |
| **CSRF**                     | 12 labs    | Exploiting trust                       |
| **Clickjacking**             | 5 labs     | UI redressing                          |
| **DOM-Based Vulnerabilities**| 7 labs     | Advanced JS injection                  |
| **WebSockets**               | 3 labs     | Realtime bug hunting                   |
| **CORS**                     | 3 labs     | Misconfigured cross-origin APIs        |

✅ **Goal:** Complete at least **50%** of XSS labs.  
🔍 Focus on the **differences between Reflected, Stored, and DOM-based XSS**.

---

## 🧪 PHASE 3: Advanced Topics

Only move here after you're confident in Phases 1 & 2.

| Vulnerability                     | Labs Count | Complexity   |
|----------------------------------|------------|--------------|
| **Insecure Deserialization**     | 10 labs    | Medium-High  |
| **JWT Attacks**                  | 8 labs     | Key cracking, `none` alg               |
| **SSTI (Server-Side Template Injection)** | 7 labs | High bounty |
| **HTTP Host Header Attacks**     | 7 labs     | Edge case bugs                         |
| **HTTP Request Smuggling**       | 21 labs    | High severity                          |
| **GraphQL, LLMs, SAML, OAuth**   | Mixed      | Modern hot topics                      |

✅ **Goal:** Solve **2–3 labs per week** from this list.

---

## 🧬 PHASE 4: Bug Bounty Simulation & Mystery Labs

Train your **bug bounty intuition** with randomized challenges.

| Feature              | Description                                       |
|----------------------|---------------------------------------------------|
| **Mystery Lab**      | Unknown vulnerability to discover & exploit       |
| **Practice Exam**    | Simulates Burp Suite Certified Practitioner test  |
| **Challenge Me Mode**| Random challenges from all categories             |

🎯 **Final Goal: Burp Suite Certified Practitioner**

| Requirement                            | What to Do                                       |
|----------------------------------------|--------------------------------------------------|
| **Complete Apprentice + Practitioner Labs** | Especially all core categories             |
| **Pass Practice Exam**                 | Mimics real 4-hour test                          |
| **Sit for Certification**             | Optional, ~$99, but valuable                     |

---

## 🛠️ Tools to Master Alongside

- **Burp Suite** (Community or Pro)
- **ffuf** – for fuzzing (endpoints, params, dirs)
- **httpx** / **nuclei** – recon automation
- **jq**, **curl**, **bash scripting** – custom scripts & parsing

---

## ✅ Useful Resources

- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [Burp Suite Community Edition](https://portswigger.net/burp/communitydownload)
- [ffuf GitHub](https://github.com/ffuf/ffuf)
- [httpx GitHub](https://github.com/projectdiscovery/httpx)
- [nuclei GitHub](https://github.com/projectdiscovery/nuclei)

---

> ✨ Stay consistent. Practice weekly. Take notes. Build intuition. And happy hacking!
