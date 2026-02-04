<a id="top"></a>

<p align="center">
  <img src="images/ensight-logo.png" width="180" alt="ENSight Logo" />
</p>

<h1 align="center">ENSight</h1>

<p align="center">
  A real-time perception, safety, and context layer for Ethereum — making Web3 interactions human-readable, explainable, and secure.
</p>

<p align="center">
  <a href="https://ethglobal.com">
    <img src="https://img.shields.io/badge/Community-ETHGlobal-blue" />
  </a>
  <a href="https://ethglobal.com/events/hackmoney2026/">
    <img src="https://img.shields.io/badge/Built%20at-HackMoney%202026-purple" />
  </a>
  <img src="https://img.shields.io/badge/Ecosystem-Ethereum-black" />
</p>

---

## 📚 Table of Contents

- [What is ENSight?](#what-is-ensight)
- [System Overview](#system-overview)
- [Repositories](#repositories)
- [Core Flows](#core-flows)
- [Why ENSight Matters](#why-ensight-matters)
- [Contributing](#contributing)
- [Roadmap](#roadmap)

---

<a id="what-is-ensight"></a>
## 👁️ What is ENSight?

ENSight is a **real-time perception layer for Ethereum** that sits between users and dApps to:

- Explain wallet actions before signing  
- Surface risk and abnormal behavior  
- Add human-readable context to on-chain interactions  
- Turn opaque transactions into understandable intent  

Instead of blindly approving wallet popups, users see:

**what’s happening, why it matters, and whether it’s safe.**

[⬆ Back to top](#top)

---

<a id="system-overview"></a>
## 🧱 System Overview

```
User Browser
↓
ENSight Extension (Interceptor + UI)
↓
ENSight Backend (Intent + Risk Engine)
↓
ENSight Web (Onboarding, demos, dApp layer)
↓
Ethereum + ENS + On-chain data
```



ENSight blends:

- Client-side interception  
- Off-chain explainability & risk  
- On-chain context & identity  

[⬆ Back to top](#top)

---

<a id="repositories"></a>
## 📦 Repositories

### 🧩 ENSight Extension  
👉 https://github.com/eth-ensight/ensight-extension  

**Real-time interception + side panel UX**

- Hooks into wallet runtime  
- Captures `ethereum.request()` calls  
- Displays intent, risk, and context instantly  

![Extension Flow](images/diagram-extension-flow.png)

---

### 🌐 ENSight Web  
👉 https://github.com/eth-ensight/ensight-web  

**Landing page + dApp layer**

- Project onboarding  
- Demo experiences  
- Future on-chain interactions  

---

### ⚙️ ENSight Backend  
👉 https://github.com/eth-ensight/ensight-backend  

**Intent parsing + risk + explanation engine**

- Transaction decoding  
- Risk heuristics  
- Context enrichment  
- (Optional) AI explainability layer  

---

Each repo is modular, production-ready, and contributor-friendly.

[⬆ Back to top](#top)

---

<a id="core-flows"></a>
## 🔄 Core Flow (High Level)

1. User visits a dApp  
2. Wallet is injected (`window.ethereum`)  
3. ENSight hooks into runtime  
4. dApp triggers wallet action  
5. ENSight intercepts intent  
6. Backend analyzes risk + meaning  
7. ENSight displays explanation in real time  

No friction. No blind signing.

[⬆ Back to top](#top)

---

<a id="why-ensight-matters"></a>
## 🚀 Why ENSight Matters

Web3 today is:

❌ opaque  
❌ risky for newcomers  
❌ easy to exploit  
❌ hard to understand  

ENSight makes Ethereum:

✅ human-readable  
✅ safer by default  
✅ explainable  
✅ trust-aware  

Use cases include:

- Scam prevention  
- Transaction previews  
- Reputation & trust layers  
- Social context with ENS  
- Safer onboarding into crypto  

[⬆ Back to top](#top)

---

<a id="contributing"></a>
## 🤝 Contributing

ENSight is built as an **open modular Web3 infrastructure project**.

Contributions welcome for:

- Extension UX & interception logic  
- Risk detection heuristics  
- On-chain data enrichment  
- Explanation engines  
- Web experiences  

Each repo includes setup + contribution guides.

[⬆ Back to top](#top)

---

<a id="roadmap"></a>
## 🗺 Roadmap

- Advanced scam detection  
- Transaction simulation previews  
- ENS-based social trust graphs  
- Community-sourced warnings  
- Developer APIs for dApps  
- On-chain reputation signals  

[⬆ Back to top](#top)

---

<a id="team"></a>
## 👨‍💻 The Team

ENSight is built by Canadian builders pushing forward open Web3 safety and explainability infrastructure. 🇨🇦

<table>
  <tr>
    <td width="80" valign="top">
      <img src="images/shernan-javier.jpeg" width="64" height="64" alt="Shernan Javier" />
    </td>
    <td valign="top">
      <b>Shernan Javier ✦</b><br/>
      <i>Toronto, Canada</i><br/>
      <a href="https://github.com/ShernanJ">GitHub</a> ·
      <a href="https://www.linkedin.com/in/shernanjavier/">LinkedIn</a> ·
      <a href="https://x.com/shernanjavier">X</a>
    </td>
  </tr>

  <tr>
    <td width="80" valign="top">
      <img src="images/mccauley-armishaw.jpeg" width="64" height="64" alt="McCauley Armishaw" />
    </td>
    <td valign="top">
      <b>McCauley Armishaw 🔨</b><br/>
      <i>Winnipeg, Canada</i><br/>
      <a href="https://github.com/marmishaw14">GitHub</a> ·
      <a href="https://www.linkedin.com/in/mccauley-armishaw/">LinkedIn</a> ·
      <a href="https://x.com/mccauleycodes">X</a>
    </td>
  </tr>

  <tr>
    <td width="80" valign="top">
      <img src="images/igo-domingo.jpeg" width="64" height="64" alt="Igo Domingo" />
    </td>
    <td valign="top">
      <b>Igo Domingo ⚙️</b><br/>
      <i>Toronto, Canada</i><br/>
      <a href="https://github.com/igoigloo">GitHub</a> ·
      <a href="https://www.linkedin.com/in/igo-domingo-98b304153/">LinkedIn</a>
    </td>
  </tr>
</table>

<p align="right"><a href="#top">⬆ Back to top</a></p>




Built at HackMoney 2026 • Powered by Ethereum
