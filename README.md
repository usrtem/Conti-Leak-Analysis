# 🧨 Conti Ransomware Leak Analysis

This repository presents a deep-dive analysis of the Conti ransomware gang, based on the leaked internal Jabber chat logs from early 2022. The report outlines the group’s internal structure, operational tools, communications, and monetization strategies. It demonstrates how Conti functioned more like a structured criminal enterprise than a loose hacker collective.

## 📄 Included

- [ContiRansomwareLeak_MichaelTwining.pdf](https://github.com/user-attachments/files/20797911/ContiRansomwareLeak_MichaelTwining.pdf) – Full analysis of the Conti group based on primary-source leaked communications

## 🕴️ Organizational Breakdown

Conti employed a layered organizational model with clear operational silos. Key members such as **Stern**, **Bentley**, **Mango**, and **Target** oversaw development, infrastructure, affiliate coordination, and OSINT-driven extortion targeting. Their structure included:
- Coders, crypters, and testers
- OSINT analysts for victim profiling
- Admins for system and comms maintenance
- Dedicated ransomware negotiators

## 🛠 Tools & Techniques

Analysis of chat logs and related findings revealed the use of:
- **Cobalt Strike** for post-exploitation and lateral movement
- **Google Dorking** for reconnaissance
- Native Windows tools like `net.exe`, `nltest.exe`, `tasklist`, and `sc`
- Credential dumping via Mimikatz and custom scripts
- Exploitation of accessibility features and scheduled tasks for persistence

## 💰 Extortion Strategy

Conti's approach to victim engagement blended OSINT profiling with social engineering. Tactics included:
- Proof-of-life samples to pressure victims
- Timed leaks and staged releases
- Monitoring for cyber insurance or financial capacity
- Multi-tier ransom pricing depending on perceived organization wealth

## 🔄 Threat Landscape Relevance

The Conti leak has become a goldmine for understanding the business operations behind ransomware-as-a-service (RaaS). This report draws parallels between Conti and traditional enterprises—highlighting HR practices, recruitment, developer task tracking, and internal politics.

## 👤 Author

**Michael Twining**  
Cybersecurity Researcher | Malware & Threat Intelligence | GitHub: [@usrtem](https://github.com/usrtem)  
📫 Contact: michael.twining@outlook.com  
🌐 Portfolio: [LinkedIn](https://www.linkedin.com/in/michael-twining) | [YouTube](https://www.youtube.com/@cybergeek-mt)

## 🔐 License

This project is released under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
