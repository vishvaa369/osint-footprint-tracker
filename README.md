# 🔍 OSINT Digital Footprint Tracker

> A browser-based open-source intelligence tool for mapping personal digital exposure, generating structured threat models, and producing professional remediation reports.

Built as a **cybersecurity portfolio project** demonstrating practical skills in:
- Open-Source Intelligence (OSINT) methodology
- Cyber threat intelligence & threat modelling
- Privacy risk analysis & attack surface mapping
- Responsible disclosure and ethical hacking practices

---

## 🖥️ Live Demo

Open `index.html` in any browser — no server or installation required.

---

## 📸 Features

| Feature | Description |
|---|---|
| **Threat Model Dashboard** | Interactive risk overview with severity ratings |
| **8 Risk Vectors** | Scored and categorised exposure categories |
| **14 Platform Assessment** | Social media, breach DBs, data brokers |
| **OSINT Dork Generator** | Pre-built Google dork queries for your identifiers |
| **Remediation Checklist** | Prioritised, interactive to-do list with persistence |
| **Professional Report** | Exportable `.txt` threat model report (copy / download / print) |
| **Zero Dependencies** | Pure HTML, CSS, and vanilla JS — no npm, no build tools |

---

## 🚀 Quick Start

```bash
git clone https://github.com/vishvaavish369/osint-footprint-tracker.git
cd osint-footprint-tracker
open index.html   # macOS
# or just double-click index.html in Windows/Linux
```

No build step. No server required. Works fully offline.

---

## 📁 Project Structure

```
osint-footprint-tracker/
├── index.html          # Main application shell
├── assets/
│   └── style.css       # Terminal-aesthetic stylesheet
├── src/
│   └── app.js          # Core analysis logic & data
├── docs/
│   ├── threat-model.md # Sample threat model writeup
│   └── methodology.md  # OSINT methodology documentation
└── README.md
```

---

## 🔬 Methodology

This tool simulates the **passive reconnaissance** phase of a security assessment:

### Phase 1 — Identifier Analysis
- Extract username patterns and numeric suffixes
- Identify cross-platform fingerprinting potential
- Map email address variants and domain metadata

### Phase 2 — Exposure Vector Scoring
Each vector is scored 0–100 based on:
- **Reachability** — how easily an adversary can exploit it
- **Impact** — what data/access is exposed
- **Prevalence** — how common this vector is

### Phase 3 — Platform Enumeration
Platforms are rated by exposure level:
- 🔴 **Critical** — known high-exposure surfaces (data brokers, breach DBs)
- 🟠 **High** — likely account presence with enumerable data
- 🟢 **Low** — platforms with limited public exposure

### Phase 4 — Threat Model Report
A structured report following CTI (Cyber Threat Intelligence) conventions:
- Executive summary with risk level
- Detailed vector analysis
- OSINT queries for verification
- Prioritised remediation roadmap

---

## 🛠️ OSINT Tools Referenced

| Tool | Purpose |
|---|---|
| [Sherlock](https://github.com/sherlock-project/sherlock) | Username enumeration across 300+ platforms |
| [Maigret](https://github.com/soxoj/maigret) | Advanced username OSINT |
| [theHarvester](https://github.com/laramies/theHarvester) | Email & domain recon |
| [GHunt](https://github.com/mxrch/GHunt) | Google account OSINT |
| [HaveIBeenPwned](https://haveibeenpwned.com) | Breach database lookup |
| [SpiderFoot](https://github.com/smicallef/spiderfoot) | Automated OSINT collection |
| [Maltego](https://maltego.com) | Visual link analysis |
| [ExifTool](https://exiftool.org) | File metadata extraction |

---

## ⚖️ Legal & Ethical Notice

> **This tool is for educational purposes and authorised security assessments only.**

- Only analyse accounts and identifiers you **own** or have **explicit written authorisation** to investigate
- Passive OSINT does not replace professional penetration testing
- Unauthorised OSINT investigations may violate laws including the Computer Fraud and Abuse Act (CFAA), GDPR, and equivalents in your jurisdiction
- The author assumes no liability for misuse

---

## 📚 Learning Resources

- [OSINT Framework](https://osintframework.com) — curated OSINT tool directory
- [Privacy Guides](https://www.privacyguides.org) — practical privacy hardening
- [Bellingcat OSINT Guide](https://www.bellingcat.com/category/resources/how-tos/) — investigative OSINT techniques
- [TCM Security OSINT Course](https://academy.tcm-sec.com) — structured learning path
- [PTES Technical Guidelines](http://www.pentest-standard.org) — penetration testing standard

---

## 👤 Author

**vishvaavish369**
- GitHub: [@vishvaavish369](https://github.com/vishvaavish369)
- Email: vishvaavish369@gmail.com

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

*Built as part of a cybersecurity portfolio demonstrating practical OSINT and threat intelligence skills.*
