<h1 align="center">Hi, I'm Victor Bărbuță 👋</h1>

<p align="center">
  <strong>Information Security student at UTM · I build security tools that catch real attacks</strong><br>
  Looking for a <strong>SOC / Blue Team internship</strong> · Chișinău, Moldova · on-site, hybrid or remote
</p>

<p align="center">
  <a href="https://victor-barbuta.vercel.app"><img src="https://img.shields.io/badge/CV-victor--barbuta.vercel.app-5ce1e6?style=for-the-badge&logo=googlechrome&logoColor=black" alt="My CV website"></a>
  <a href="mailto:victor.barbuta@outlook.com"><img src="https://img.shields.io/badge/Email-victor.barbuta%40outlook.com-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email me"></a>
  <a href="https://tryhackme.com/p/vicuvi1"><img src="https://img.shields.io/badge/TryHackMe-Top%203%25-212C42?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe: top 3%"></a>
</p>

<p align="center">
  <a href="https://tryhackme.com/p/vicuvi1"><img src="https://tryhackme-badges.s3.amazonaws.com/vicuvi1.png" alt="TryHackMe badge" height="88"></a>
</p>

---

## 🛡️ Security tools I built

Every tool below works today, has tests and CI, and three of them run live in your browser.

<table>
<tr>
<td width="50%" valign="top">

### [🎣 PhishLens](https://github.com/vicuvi1/phishlens)
**Phishing email analyzer.** Drop a suspicious email and see in one second *why* it's phishing: SPF/DKIM/DMARC, look-alike domains, QR-code phishing, macros, HTML smuggling, mapped to MITRE ATT&CK. Runs 100% in the browser.

<a href="https://vicuvi1.github.io/phishlens/"><img src="https://raw.githubusercontent.com/vicuvi1/phishlens/main/docs/demo.gif" alt="PhishLens demo"></a>

**[▶ Live demo](https://vicuvi1.github.io/phishlens/)** · JavaScript · zero dependencies · 24 tests

</td>
<td width="50%" valign="top">

### [🪟 WinTrace](https://github.com/vicuvi1/wintrace)
**Windows event log attack hunter.** My own EVTX parser plus 30+ detections: brute force, Kerberoasting, pass-the-hash, Mimikatz, DCSync, log clearing, turned into a plain-English attack story.

<a href="https://vicuvi1.github.io/wintrace/"><img src="https://raw.githubusercontent.com/vicuvi1/wintrace/main/docs/demo.gif" alt="WinTrace demo"></a>

**[▶ Live demo](https://vicuvi1.github.io/wintrace/)** · JavaScript · EVTX · Active Directory · 17 tests

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [🔎 SiteSentry](https://github.com/vicuvi1/SiteSentry)
**Passive website security scanner.** Grades HTTPS, TLS, headers, cookies, CORS and SPF/DMARC from A+ to F and writes the fix. I used it on 100 popular websites: **only 31% earn an A**.

<a href="https://vicuvi1.github.io/SiteSentry/"><img src="https://raw.githubusercontent.com/vicuvi1/SiteSentry/main/docs/img/report-dark.png" alt="SiteSentry report"></a>

**[▶ Project page & research](https://vicuvi1.github.io/SiteSentry/)** · Python · 103 tests · CI gate

</td>
<td width="50%" valign="top">

### [🍯 HiveWatch SOC](https://github.com/vicuvi1/hivewatch-soc)
**Honeypot-driven mini SOC.** SSH, Telnet, HTTP and TCP honeypots, 11 streaming detection rules, 25 ATT&CK techniques, threat-actor profiles that replay captured shell sessions, all on a live 3D attack map.

<a href="https://github.com/vicuvi1/hivewatch-soc"><img src="https://raw.githubusercontent.com/vicuvi1/hivewatch-soc/main/docs/demo.gif" alt="HiveWatch demo (demo mode, simulated attacks)"></a>

Python · FastAPI · Docker · 26 tests

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### [📜 SOC Log & Traffic Analyzer](https://github.com/vicuvi1/analyzing-logs-traffic-Defensive-SOC-)
**Log triage platform.** Apache/Nginx, syslog and PCAP → Sigma-style YAML detections mapped to ATT&CK → AbuseIPDB enrichment → SOAR containment playbooks (generated, never auto-run) and case management. Python · Streamlit.

</td>
</tr>
</table>

## 🏆 Highlights

- **TryHackMe top 3% worldwide**, 140+ rooms, SOC Level 1 path completed
- **4th of 12 teams** at HackTrone, an international cybersecurity competition (team NAVI, Sep 2026)
- **GigaHack 2026** red-team CTF: our team went from one web host to five domains; I kept the notes and timeline that became the report
- **Registru Digital**: replaced a paper library register with a web app my mother uses every day
- Off the keyboard: 3× national checkers champion of Moldova, black belt in Taekwondo

## 💻 Tools & languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-8A6D00?style=flat-square&logo=javascript&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square) ![Linux](https://img.shields.io/badge/Linux-333333?style=flat-square&logo=linux&logoColor=white) ![Kali Linux](https://img.shields.io/badge/Kali-557C94?style=flat-square&logo=kalilinux&logoColor=white) ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![MITRE ATT&CK](https://img.shields.io/badge/MITRE-ATT%26CK-red?style=flat-square) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

<details>
<summary><strong>Other things I've built</strong></summary>

<br>

- [Registru Digital](https://github.com/vicuvi1/mother_app_registru): library register web app with login, history and offline-safe saving
- [Interview Scheduler Pro](https://github.com/vicuvi1/interview_manager): candidate/admin workspaces, timezone-aware booking, calendar integrations
- [Life OS](https://github.com/vicuvi1/life_os): goals, tasks and habits dashboard (Next.js, TypeScript, Firebase)

</details>

## 🤝 Connect

[![CV](https://img.shields.io/badge/CV-victor--barbuta.vercel.app-5ce1e6?style=flat-square)](https://victor-barbuta.vercel.app)
[![Outlook](https://img.shields.io/badge/Outlook-0078D4?style=flat-square)](mailto:victor.barbuta@outlook.com)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:victorbarbuta27@gmail.com)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/vicuvi1)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/tk_victorb)
[![CodePen](https://img.shields.io/badge/CodePen-181717?style=flat-square&logo=codepen&logoColor=white)](https://codepen.io/vicuvi1)
