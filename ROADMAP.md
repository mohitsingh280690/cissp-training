# CISSP Certification Training Roadmap

## Overview

| Item | Detail |
|------|--------|
| **Exam** | (ISC)² Certified Information Systems Security Professional |
| **Total Days** | 140 days |
| **Structure** | Theory + 10 MCQs per day |
| **Start Date** | TBD (set when Day 1 begins) |
| **Domains** | 8 |
| **Exam Questions** | 125-175 (CAT format) |
| **Passing Score** | 700 / 1000 |

## Folder Structure

```
e:\cissp\
├── ROADMAP.md              ← This file (master reference)
├── PROGRESS.md             ← Tracks daily completion status
├── exercises\              ← Active day exercises (theory + MCQ HTML)
│   ├── day-XXX-theory.html
│   └── day-XXX-mcq.html
└── completed\              ← Finished exercises moved here after review
    ├── day-XXX-theory.html
    └── day-XXX-mcq.html
```

## How It Works

1. **Request a day**: Ask me to prepare the next day's exercise
2. **I create**: A `theory.html` + interactive `mcq.html` in `exercises\`
3. **You study**: Read the theory, then attempt the MCQ
4. **Submit answers**: Tell me your answers or score
5. **I review**: Check your answers, explain mistakes, move files to `completed\`
6. **Repeat**: Ask for the next day

---

## Domain Breakdown & Exam Weights

| # | Domain | Weight | Days | Day Range |
|---|--------|--------|------|-----------|
| 1 | Security and Risk Management | 15% | 20 | 1–20 |
| 2 | Asset Security | 10% | 13 | 21–33 |
| 3 | Security Architecture and Engineering | 13% | 19 | 34–52 |
| 4 | Communication and Network Security | 13% | 17 | 53–69 |
| 5 | Identity and Access Management (IAM) | 13% | 16 | 70–85 |
| 6 | Security Assessment and Testing | 12% | 14 | 86–99 |
| 7 | Security Operations | 13% | 18 | 100–117 |
| 8 | Software Development Security | 11% | 13 | 118–130 |
| — | Final Review & Mock Exams | — | 10 | 131–140 |

---

## Detailed Day-by-Day Plan

---

### DOMAIN 1: Security and Risk Management (15%) — Days 1–20

| Day | Topic | Sub-Topics | Difficulty |
|-----|-------|------------|------------|
| 1 | CISSP Overview & Foundations | Exam format, CAT overview, study strategies; CIA Triad (Confidentiality, Integrity, Availability); DAD Triad (Disclosure, Alteration, Destruction); Defense in Depth concept | Beginner |
| 2 | Security Governance Principles | Organizational security role; Alignment of security with business strategy; Organizational processes (acquisitions, divestitures, governance committees); Security roles & responsibilities (CISO, CSO, Security Analyst) | Beginner |
| 3 | Compliance & Regulatory Issues | Compliance vs. regulation vs. legislation; Industry standards (PCI-DSS, SOX, HIPAA, GLBA); Contractual, legal, and regulatory requirements; Compliance monitoring and reporting | Beginner |
| 4 | Legal Systems & Law Types | Civil law vs. common law vs. religious law vs. customary law; Criminal law, civil law (tort), administrative/regulatory law; Liability and due care/due diligence; Jurisdiction issues in cybersecurity | Intermediate |
| 5 | Intellectual Property | Copyright (automatic, Berne Convention, duration); Trademarks (™ vs ®, Lanham Act); Patents (utility, design, 20 years); Trade Secrets (NDA, Economic Espionage Act); Software licensing (open source, proprietary, EULA) | Intermediate |
| 6 | Privacy Laws & Regulations | GDPR (principles, data subject rights, DPO, breach notification); HIPAA (PHI, covered entities, business associates); CCPA/CPRA; Privacy Shield (invalidated), SCCs; OECD Privacy Guidelines; Trans-border data flow | Intermediate |
| 7 | Professional Ethics | (ISC)² Code of Professional Ethics (4 canons); Computer Ethics Institute – Ten Commandments; Organizational code of ethics; Ethical decision-making frameworks; RFC 1087 – Ethics and the Internet | Beginner |
| 8 | Security Policies & Frameworks | Policies vs. Standards vs. Procedures vs. Baselines vs. Guidelines; Types of policies (Regulatory, Advisory, Informative); NIST CSF (Identify, Protect, Detect, Respond, Recover); ISO 27001/27002; COBIT | Intermediate |
| 9 | Risk Management Concepts | Risk terminology (threat, vulnerability, asset, exposure, safeguard); Risk = Threat × Vulnerability × Impact; Risk appetite, risk tolerance, risk capacity; Risk frameworks (NIST RMF, ISO 31000, OCTAVE, FAIR) | Intermediate |
| 10 | Quantitative Risk Analysis | Asset Value (AV); Exposure Factor (EF); Single Loss Expectancy (SLE = AV × EF); Annualized Rate of Occurrence (ARO); Annualized Loss Expectancy (ALE = SLE × ARO); Cost-Benefit Analysis (CBA); ROSI | Intermediate |
| 11 | Qualitative Risk Analysis | Qualitative methods (Delphi technique, brainstorming, interviews); Risk matrices (likelihood × impact); Scenarios and ranking; Hybrid approaches; Comparison: qualitative vs. quantitative | Intermediate |
| 12 | Risk Response Strategies | Risk Mitigation/Reduction; Risk Transfer/Sharing (insurance, outsourcing); Risk Acceptance (residual risk); Risk Avoidance; Risk Register documentation; Control selection and implementation | Intermediate |
| 13 | Threat Modeling | STRIDE (Spoofing, Tampering, Repudiation, Info Disclosure, DoS, Elevation of Privilege); DREAD (Damage, Reproducibility, Exploitability, Affected Users, Discoverability); PASTA (7-stage); Attack trees; Threat libraries (MITRE ATT&CK) | Advanced |
| 14 | Supply Chain Risk Management | Third-party risk assessment; Vendor due diligence; SLAs and security requirements; Minimum security requirements; Hardware/software supply chain threats (SolarWinds case); SCRM best practices | Intermediate |
| 15 | Business Continuity Planning – Overview | BCP vs. DRP; BCP lifecycle (project scope, BIA, strategy, plan development, testing, maintenance); BCP team roles; Senior management role and support; Standards (ISO 22301, NIST SP 800-34) | Intermediate |
| 16 | Business Impact Analysis (BIA) | Identifying critical business functions; Maximum Tolerable Downtime (MTD); Recovery Time Objective (RTO); Recovery Point Objective (RPO); Work Recovery Time (WRT); Mean Time Between Failures (MTBF); Mean Time To Repair (MTTR) | Advanced |
| 17 | BCP Strategy & Plan Development | Preventive controls; Recovery strategies; Plan documentation; Vital records program; Crisis communication plan; Emergency response procedures | Intermediate |
| 18 | Personnel Security Policies | Employment candidate screening; Background checks; Employment agreements (NDA, NCA, AUP); Onboarding and offboarding; Separation of duties (SoD); Job rotation; Mandatory vacations; Least privilege | Intermediate |
| 19 | Security Awareness & Training | Awareness vs. training vs. education; Role-based training; Social engineering awareness; Phishing simulations; Measuring awareness effectiveness; Continuous improvement | Beginner |
| 20 | **Domain 1 Review** | Comprehensive review of all Domain 1 topics; 20 MCQs covering entire domain; Identify weak areas; Key formulas and concepts summary | Review |

---

### DOMAIN 2: Asset Security (10%) — Days 21–33

| Day | Topic | Sub-Topics | Difficulty |
|-----|-------|------------|------------|
| 21 | Information & Asset Classification | Why classify assets; Classification process; Criteria for classification; Declassification and reclassification; Asset inventory and management | Beginner |
| 22 | Data Classification Levels | Government: Top Secret, Secret, Confidential, Sensitive But Unclassified, Unclassified; Commercial: Confidential, Private, Sensitive, Public; Mapping between systems; Marking and labeling | Beginner |
| 23 | Asset Ownership & Roles | Data Owner (senior management); Data Custodian (IT operations); Data Steward (data quality); System Owner; Data Processor vs. Data Controller (GDPR); User/Subject responsibilities | Intermediate |
| 24 | Data Lifecycle | Create/Collect; Store; Use; Share/Transmit; Archive; Destroy; Security controls at each stage; Data flow mapping | Intermediate |
| 25 | Data Handling Requirements | Marking and labeling standards; Handling procedures per classification; Shipping and transport security; Storage requirements (physical and digital); Media management | Intermediate |
| 26 | Privacy Protection | Personally Identifiable Information (PII); Protected Health Information (PHI); Sensitive Personal Information (SPI); Data anonymization; Pseudonymization; Data masking; Tokenization | Intermediate |
| 27 | Data Retention & Destruction | Retention policies and schedules; Legal and regulatory retention requirements; Records management; Litigation hold / legal hold; Destruction methods (logical vs. physical); Certificate of destruction | Intermediate |
| 28 | Data Security Controls | Encryption (at rest, in transit, in use); Access controls; DRM (Digital Rights Management); Watermarking; Database security controls; Cloud data security | Intermediate |
| 29 | Data States | Data at Rest (encryption: AES, BitLocker, FileVault); Data in Transit (TLS, IPSec, VPN); Data in Use (homomorphic encryption, secure enclaves, TEE); Protecting data in each state | Intermediate |
| 30 | Data Remanence & Sanitization | Data remanence concepts; Clearing (overwriting); Purging (degaussing, cryptographic erasure); Destruction (shredding, incineration, disintegration); NIST SP 800-88 Guidelines for Media Sanitization | Advanced |
| 31 | Data Loss Prevention (DLP) | DLP types (Network, Endpoint, Cloud); Content inspection techniques; DLP policies and rules; False positives management; DLP deployment strategies; Integration with CASB | Intermediate |
| 32 | Data Roles Under GDPR | Data Subject; Data Controller; Data Processor; Data Protection Officer (DPO); Supervisory Authority; Data Processing Agreements; Cross-border data transfer mechanisms | Intermediate |
| 33 | **Domain 2 Review** | Comprehensive review of all Domain 2 topics; 20 MCQs covering entire domain; Key roles and classifications summary; Data lifecycle controls summary | Review |

---

### DOMAIN 3: Security Architecture and Engineering (13%) — Days 34–52

| Day | Topic | Sub-Topics | Difficulty |
|-----|-------|------------|------------|
| 34 | Security Engineering Principles | Saltzer & Schroeder's principles; Least privilege; Fail-safe defaults; Economy of mechanism; Complete mediation; Open design; Separation of privilege; Least common mechanism; Psychological acceptability | Intermediate |
| 35 | Security Models – Bell-LaPadula | State machine model; Confidentiality model; Simple Security Property (no read up); Star (*) Property (no write down); Strong Star Property; Tranquility principle; Limitations | Advanced |
| 36 | Security Models – Biba & Clark-Wilson | Biba: Integrity model; Simple Integrity Property (no read down); Star Integrity Property (no write up); Clark-Wilson: Well-formed transactions; Constrained Data Items (CDI); Unconstrained Data Items (UDI); Integrity Verification Procedures (IVP); Transformation Procedures (TP) | Advanced |
| 37 | Security Models – Others | Brewer-Nash (Chinese Wall) – conflict of interest; Graham-Denning – object creation/deletion rules; Harrison-Ruzzo-Ullman (HRU) – access rights; Lipner Model (combines BLP + Biba); Take-Grant Model | Advanced |
| 38 | Security Architecture Frameworks | Zachman Framework; TOGAF; SABSA (Sherwood Applied Business Security Architecture); ITIL; NIST Enterprise Architecture; DoDAF; MODAF | Intermediate |
| 39 | Evaluation Criteria | TCSEC (Orange Book) – A, B, C, D levels; ITSEC – E0 to E6; Common Criteria (ISO 15408) – EAL 1-7; Protection Profiles; Security Targets; TOE (Target of Evaluation) | Advanced |
| 40 | System Security Architecture | Trusted Computing Base (TCB); Security perimeter; Reference monitor concept; Security kernel; Trusted Platform Module (TPM); Hardware Security Module (HSM); Trusted paths | Advanced |
| 41 | CPU Architecture & Memory Protection | CPU rings (Ring 0-3); Process isolation; Memory protection (segmentation, paging); ASLR; DEP/NX bit; Virtual memory; Swapping and paging security; Buffer overflow prevention | Advanced |
| 42 | Operating System Security | OS hardening; Patch management; Trusted OS concepts; Security modes (dedicated, system high, compartmented, multilevel); Process isolation and sandboxing; Mandatory vs. discretionary access | Intermediate |
| 43 | Virtualization Security | Type 1 vs. Type 2 hypervisors; VM escape; VM sprawl; Hypervisor security; Container security (Docker, Kubernetes); Serverless security; Microservices architecture | Intermediate |
| 44 | Cloud Security | Cloud service models (IaaS, PaaS, SaaS); Cloud deployment models (public, private, hybrid, community); Shared responsibility model; Cloud security challenges; CSA CCM; CASB; Cloud-native security | Intermediate |
| 45 | IoT & Embedded Systems Security | IoT architecture; Constrained devices; SCADA/ICS security; CPS (Cyber-Physical Systems); Edge computing security; IoT protocols (MQTT, CoAP, Zigbee); Firmware security | Intermediate |
| 46 | Cryptography Fundamentals | History of cryptography; Cryptographic goals (CIANA); Cipher types (substitution, transposition); Stream vs. block ciphers; Kerckhoffs' principle; Key space and key length; XOR operations; Confusion and diffusion | Intermediate |
| 47 | Symmetric Encryption | DES (64-bit block, 56-bit key, Feistel); 3DES (keying options); AES (128/192/256-bit keys, Rijndael); Blowfish; Twofish; RC4, RC5, RC6; IDEA; Block cipher modes (ECB, CBC, CFB, OFB, CTR, GCM) | Advanced |
| 48 | Asymmetric Encryption | RSA (factoring large primes); Diffie-Hellman Key Exchange (discrete logarithm); ElGamal; ECC (Elliptic Curve Cryptography); Key exchange protocols; Performance comparison with symmetric; Hybrid cryptosystems | Advanced |
| 49 | Hashing & Digital Signatures | Hash functions (MD5, SHA-1, SHA-2, SHA-3); Properties (collision resistance, preimage resistance); HMAC; Digital Signatures (creation, verification); DSA; Non-repudiation; Birthday attack; Rainbow tables; Salting | Advanced |
| 50 | PKI & Certificate Management | PKI components (CA, RA, CRL, OCSP); Certificate lifecycle; X.509 certificates; Certificate chaining; Certificate pinning; Key escrow; Key recovery; PGP Web of Trust vs. hierarchical PKI | Advanced |
| 51 | Cryptographic Attacks & Key Management | Brute force; Frequency analysis; Known plaintext; Chosen plaintext; Chosen ciphertext; Side-channel attacks; Rubber-hose attack; Key management lifecycle; Key stretching (PBKDF2, bcrypt, scrypt) | Advanced |
| 52 | **Domain 3 Review** | Comprehensive review of all Domain 3 topics; 20 MCQs covering entire domain; Security models comparison table; Cryptography algorithms summary | Review |

---

### DOMAIN 4: Communication and Network Security (13%) — Days 53–69

| Day | Topic | Sub-Topics | Difficulty |
|-----|-------|------------|------------|
| 53 | OSI Model – Layers 1-4 | Layer 1 Physical (cables, hubs, repeaters); Layer 2 Data Link (switches, MAC, ARP, frames); Layer 3 Network (routers, IP, ICMP, packets); Layer 4 Transport (TCP, UDP, segments/datagrams, ports); PDU at each layer | Beginner |
| 54 | OSI Model – Layers 5-7 & TCP/IP | Layer 5 Session (NetBIOS, RPC, simplex/duplex); Layer 6 Presentation (encryption, compression, MIME, ASCII); Layer 7 Application (HTTP, FTP, SMTP, DNS); TCP/IP model comparison (4 layers); Encapsulation/decapsulation | Beginner |
| 55 | IP Addressing & Subnetting | IPv4 address classes (A, B, C, D, E); Private address ranges (RFC 1918); CIDR notation; Subnetting fundamentals; Subnet masks; IPv6 addressing (128-bit); IPv6 features (autoconfiguration, IPSec built-in); NAT/PAT | Intermediate |
| 56 | Core Protocols | TCP (3-way handshake, flow control, reliability); UDP (connectionless, speed); ICMP (ping, traceroute); ARP (MAC resolution, ARP poisoning); RARP; Port numbers (well-known, registered, dynamic) | Intermediate |
| 57 | Network Services | DNS (resolution process, records: A, AAAA, MX, CNAME, PTR); DNS attacks (poisoning, hijacking, amplification); DHCP (DORA process); DHCP attacks (starvation, rogue server); NTP; SNMP (v1, v2c, v3) | Intermediate |
| 58 | Switching & VLANs | Layer 2 switching; MAC address table; Spanning Tree Protocol (STP); VLAN concepts and security; VLAN hopping attacks; Port security; 802.1Q trunking; Private VLANs; ARP inspection | Intermediate |
| 59 | Routing Concepts | Static vs. dynamic routing; Distance-vector protocols (RIP, IGRP); Link-state protocols (OSPF, IS-IS); Hybrid protocols (EIGRP); BGP (Border Gateway Protocol); Route poisoning; Routing security | Intermediate |
| 60 | Firewalls | Packet filtering (stateless); Stateful inspection; Application-level gateway (proxy); Circuit-level gateway; Next-generation firewalls (NGFW); WAF; Firewall architectures (bastion host, screened subnet/DMZ, dual-homed) | Intermediate |
| 61 | IDS/IPS | Network-based (NIDS/NIPS); Host-based (HIDS/HIPS); Signature-based detection; Anomaly-based detection; Stateful protocol analysis; Inline vs. passive; False positives vs. false negatives; Snort, Suricata | Intermediate |
| 62 | VPN Technologies | IPSec (AH, ESP, transport mode, tunnel mode, IKE); SSL/TLS VPN; L2TP; PPTP (deprecated); Site-to-site vs. remote access VPN; Split tunneling; Always-on VPN; VPN concentrator | Intermediate |
| 63 | Wireless Security | 802.11 standards (a/b/g/n/ac/ax); WEP (RC4, weak IV); WPA (TKIP); WPA2 (AES-CCMP); WPA3 (SAE, 192-bit); Evil twin attacks; Wardriving; Rogue APs; Wireless IDS; RADIUS authentication | Intermediate |
| 64 | Network Attacks | DoS/DDoS (SYN flood, Smurf, UDP flood, amplification); Man-in-the-Middle (MITM); Replay attacks; Session hijacking; IP spoofing; DNS attacks; ARP poisoning; Botnet/C2; DDoS mitigation strategies | Advanced |
| 65 | Email Security | SMTP, POP3, IMAP protocols; S/MIME (certificates, encryption, signing); PGP/GPG; SPF (Sender Policy Framework); DKIM (DomainKeys Identified Mail); DMARC; Email gateway security; Phishing/spear phishing defense | Intermediate |
| 66 | Secure Communications | TLS 1.3; HTTPS; SSH; Secure file transfer (SFTP, SCP, FTPS); Voice security (VoIP, SIP); SRTP; Secure messaging; Signal protocol | Intermediate |
| 67 | CDN & Network Optimization | Content Distribution Networks; Load balancers (Layer 4, Layer 7); Reverse proxy; Caching; DDoS protection via CDN; SD-WAN; SASE (Secure Access Service Edge) | Intermediate |
| 68 | Network Segmentation | Network zones; DMZ design; Microsegmentation; Zero Trust Network Access (ZTNA); Software-Defined Networking (SDN); Network Function Virtualization (NFV); East-West vs. North-South traffic | Intermediate |
| 69 | **Domain 4 Review** | Comprehensive review of all Domain 4 topics; 20 MCQs covering entire domain; Protocol/port reference table; Network attack defense matrix | Review |

---

### DOMAIN 5: Identity and Access Management (13%) — Days 70–85

| Day | Topic | Sub-Topics | Difficulty |
|-----|-------|------------|------------|
| 70 | IAM Fundamentals | Identification, Authentication, Authorization, Accountability (IAAA); Identity lifecycle; Provisioning and deprovisioning; Subject vs. object; Access control principles | Beginner |
| 71 | Authentication Methods | Type 1: Something you know (passwords, PINs, passphrases); Type 2: Something you have (smart cards, tokens, OTP); Type 3: Something you are (biometrics); Password policies (complexity, aging, history, lockout) | Intermediate |
| 72 | Biometrics & MFA | Biometric types (fingerprint, iris, retina, facial, voice, gait); FRR (Type I error); FAR (Type II error); CER/EER; Crossover Error Rate; Multi-factor authentication (MFA); Two-step vs. two-factor; Adaptive authentication | Intermediate |
| 73 | SSO & Kerberos | Single Sign-On benefits and risks; Kerberos components (KDC, TGT, TGS, AS); Kerberos authentication flow; Kerberos attacks (pass-the-ticket, golden ticket, Kerberoasting); SESAME | Advanced |
| 74 | Federated Identity Management | SAML 2.0 (IdP, SP, assertions); OAuth 2.0 (grant types, tokens); OpenID Connect (OIDC); WS-Federation; Federation trust models; Identity Provider (IdP) concepts; Cross-domain authentication | Advanced |
| 75 | Authorization – DAC & MAC | Discretionary Access Control (owner-controlled, ACLs); Mandatory Access Control (labels, clearances, lattice); Sensitivity labels; Compartments; SELinux; Rule-based access control | Intermediate |
| 76 | Authorization – RBAC & ABAC | Role-Based Access Control (roles, hierarchies, static/dynamic SoD); Attribute-Based Access Control (policies, attributes, XACML); Policy-based access; Temporal access restrictions; Context-aware access | Intermediate |
| 77 | Access Control Implementation | Access control lists (ACLs); Capability tables; Access control matrices; Content-dependent access control; Context-dependent access control; Restricted interfaces; Database views | Intermediate |
| 78 | Identity Management Lifecycle | Account provisioning; Account review and recertification; Account modification; Account suspension and deletion; Orphan accounts; Dormant accounts; Service accounts management | Intermediate |
| 79 | Privileged Access Management | PAM concepts; Just-in-time access; Privilege bracketing; Privileged account types; Bastion hosts / jump servers; Session recording; Credential vaulting; Emergency break-glass procedures | Advanced |
| 80 | Directory Services | LDAP (operations, DN, schema); Active Directory (domains, forests, trusts, OUs, GPO); RADIUS vs. TACACS+; Diameter protocol; X.500; Cloud directory services | Intermediate |
| 81 | Access Control Attacks | Brute force and dictionary attacks; Rainbow table attacks; Credential stuffing; Password spraying; Kerberoasting; Pass-the-hash; Privilege escalation; Social engineering for credentials | Advanced |
| 82 | Session & Credential Management | Session tokens and cookies; Session fixation; Session hijacking; Token management; Credential storage (hashing, salting); Password managers; Passwordless authentication (FIDO2, WebAuthn) | Intermediate |
| 83 | Identity as a Service (IDaaS) | Cloud-based identity management; IDaaS providers; Benefits and risks; Integration with on-premises; Hybrid identity models; SCIM (System for Cross-domain Identity Management) | Intermediate |
| 84 | Zero Trust Architecture | Zero Trust principles (never trust, always verify); NIST SP 800-207; Micro-perimeters; Continuous verification; Policy Decision Point (PDP); Policy Enforcement Point (PEP); Software-defined perimeter; BeyondCorp model | Advanced |
| 85 | **Domain 5 Review** | Comprehensive review of all Domain 5 topics; 20 MCQs covering entire domain; Authentication protocols comparison; Access control models summary | Review |

---

### DOMAIN 6: Security Assessment and Testing (12%) — Days 86–99

| Day | Topic | Sub-Topics | Difficulty |
|-----|-------|------------|------------|
| 86 | Assessment Strategies Overview | Assessment vs. audit vs. evaluation; Internal vs. external assessments; Assessment planning and scoping; Rules of engagement; Assessment frequency; Reporting and documentation | Beginner |
| 87 | Vulnerability Assessments | Vulnerability scanning (authenticated vs. unauthenticated); Network vulnerability scanners (Nessus, Qualys, OpenVAS); Host-based scanning; CVSS scoring; CVE/CWE databases; Vulnerability prioritization | Intermediate |
| 88 | Penetration Testing – Methodology | Penetration testing phases (planning, reconnaissance, scanning, exploitation, post-exploitation, reporting); PTES; OSSTMM; NIST SP 800-115; Reconnaissance techniques (passive/active) | Intermediate |
| 89 | Penetration Testing – Types | Black box, white box, gray box testing; Internal vs. external testing; Physical penetration testing; Social engineering testing; Red team vs. blue team vs. purple team; Bug bounty programs | Intermediate |
| 90 | Log Management & Monitoring | Log types (security, system, application, firewall, IDS); Log collection and aggregation; Log analysis; SIEM fundamentals; Log retention policies; Log integrity (tamper-proofing); Continuous monitoring | Intermediate |
| 91 | Code Review & Analysis | Static code analysis (SAST); Dynamic code analysis (DAST); Interactive analysis (IAST); Manual code review; Peer review; Code review checklists; Common coding flaws (CWE Top 25) | Intermediate |
| 92 | Software Testing Methods | Unit testing; Integration testing; System testing; Acceptance testing (UAT); Regression testing; Smoke testing; Performance testing (load, stress, volume); Test-driven development (TDD) | Intermediate |
| 93 | Specialized Testing Techniques | Misuse case testing; Abuse case testing; Fuzzing (mutation, generation, protocol); Fault injection; Boundary value analysis; Equivalence partitioning; Attack surface analysis | Advanced |
| 94 | Security Audits | Internal audits; External audits; Third-party audits; Regulatory audits; Audit planning; Evidence collection; Audit trails; Audit findings and remediation; Auditor independence | Intermediate |
| 95 | SOC Reports | SOC 1 Type I & Type II (financial controls, SSAE 18); SOC 2 Type I & Type II (Trust Services Criteria: Security, Availability, Processing Integrity, Confidentiality, Privacy); SOC 3 (general-purpose); SOC for Cybersecurity; SOC for Supply Chain | Advanced |
| 96 | Security Metrics | Key Performance Indicators (KPIs); Key Risk Indicators (KRIs); Security metrics framework; Mean Time to Detect (MTTD); Mean Time to Respond (MTTR); Patch compliance rate; Vulnerability remediation time; Dashboard design | Intermediate |
| 97 | BCDR Testing | Checklist review (desk check); Tabletop exercise (structured walkthrough); Simulation test; Parallel test; Full interruption test; Test frequency and documentation; Lessons learned; After-action reports | Intermediate |
| 98 | Test Coverage & Reporting | Test coverage analysis; Statement/branch/path coverage; Requirements traceability matrix; Security assessment reports; Executive summaries; Technical findings; Risk ratings; Remediation tracking | Intermediate |
| 99 | **Domain 6 Review** | Comprehensive review of all Domain 6 topics; 20 MCQs covering entire domain; Assessment types comparison; SOC reports summary | Review |

---

### DOMAIN 7: Security Operations (13%) — Days 100–117

| Day | Topic | Sub-Topics | Difficulty |
|-----|-------|------------|------------|
| 100 | Security Operations Concepts | Need-to-know and least privilege; Separation of duties and responsibilities; Privileged account management; Job rotation; Service Level Agreements (SLAs); SOC structure and tiers | Beginner |
| 101 | Investigations | Investigation types (administrative, criminal, civil, regulatory); Digital investigation process; Due care and due diligence in investigations; Interview and interrogation; Reporting; Cooperation with law enforcement | Intermediate |
| 102 | Digital Forensics – Evidence | Evidence types (real, documentary, testimonial, demonstrative); Best evidence rule; Hearsay rule; Chain of custody; Evidence handling (collect, examine, analyze, report); Admissibility requirements (relevant, reliable, legally obtained) | Advanced |
| 103 | Digital Forensics – Procedures | Forensic process (identification, preservation, collection, examination, analysis, presentation); Disk imaging and hashing; Volatile vs. non-volatile evidence; Order of volatility; Timeline analysis; Anti-forensics; Network forensics | Advanced |
| 104 | Incident Management | Incident vs. event; Incident management framework (NIST SP 800-61); Incident Response Team (IRT/CSIRT/CERT); Incident categories and severity levels; Incident response policy; Communication plans | Intermediate |
| 105 | Incident Response Lifecycle | Preparation; Detection and Analysis (IoC, IoA); Containment (short-term, long-term); Eradication; Recovery; Post-incident activity (lessons learned); Root cause analysis; IR playbooks and runbooks | Advanced |
| 106 | SIEM & Security Monitoring | SIEM architecture; Log correlation; Use cases and alert rules; SOAR integration; Security analytics; User and Entity Behavior Analytics (UEBA); Threat hunting; Network traffic analysis | Intermediate |
| 107 | Threat Intelligence | Threat intelligence sources (OSINT, commercial, government); Threat intelligence lifecycle; Indicators of Compromise (IoC); STIX/TAXII; MITRE ATT&CK framework; Threat intelligence platforms (TIP); Intelligence sharing (ISACs) | Intermediate |
| 108 | Preventive Measures | System hardening (CIS benchmarks); Patch management process; Antimalware solutions; Application whitelisting/allowlisting; Endpoint detection and response (EDR); Host-based firewalls; Security baselines | Intermediate |
| 109 | Change & Configuration Management | Change management process (RFC, CAB, approval, implementation, review); Configuration management (baselines, CMDB); Configuration items; Unauthorized change detection; Infrastructure as Code (IaC) | Intermediate |
| 110 | Vulnerability & Patch Management | Vulnerability management lifecycle (discover, prioritize, remediate, verify); Patch management process; Virtual patching; Compensating controls; Vulnerability disclosure (responsible, full, coordinated); Zero-day management | Intermediate |
| 111 | Disaster Recovery Planning | DRP vs. BCP relationship; Disaster types (natural, man-made, technical); DRP components; Recovery strategies; Plan documentation; DRP team roles; Communication procedures; Plan distribution | Intermediate |
| 112 | Recovery Strategies & Sites | Hot site (fully operational); Warm site (partially equipped); Cold site (shell facility); Mobile site; Cloud-based recovery; Reciprocal agreements; Subscription services; Recovery cost comparison; RAID levels (0, 1, 5, 6, 10) | Advanced |
| 113 | Backup & Recovery | Backup types (full, incremental, differential); Backup strategies (3-2-1 rule); Backup rotation (GFS); Off-site storage; Tape vs. disk vs. cloud backup; Recovery testing; RTO/RPO alignment; Data replication (synchronous vs. asynchronous) | Intermediate |
| 114 | DR Testing & Maintenance | Read-through/checklist test; Tabletop/structured walkthrough; Simulation test; Parallel test; Full interruption test; Test scheduling; Maintenance triggers; Plan updates; After-action reviews | Intermediate |
| 115 | Physical Security Operations | Perimeter security (fences, gates, bollards); Lighting; CCTV and surveillance; Guards and patrols; Mantraps/vestibules; Badges and access cards; Visitor management; Tailgating/piggybacking prevention | Intermediate |
| 116 | Personnel Safety & Security | Travel security; Duress systems; Emergency management; Evacuation plans; Shelter-in-place procedures; Occupant emergency plans (OEP); Safety training; First aid and AED | Beginner |
| 117 | **Domain 7 Review** | Comprehensive review of all Domain 7 topics; 20 MCQs covering entire domain; IR lifecycle summary; Recovery site comparison table | Review |

---

### DOMAIN 8: Software Development Security (11%) — Days 118–130

| Day | Topic | Sub-Topics | Difficulty |
|-----|-------|------------|------------|
| 118 | SDLC & Security Integration | SDLC phases (initiation, development, implementation, operation, disposal); Security in each SDLC phase; NIST SP 800-64; Security requirements gathering; Threat modeling in design; Security testing in development | Intermediate |
| 119 | Development Methodologies | Waterfall (sequential, rigid); Agile (Scrum, Kanban, sprints, user stories); Spiral model (risk-driven); RAD; Prototyping; DevOps (CI/CD pipeline); DevSecOps (shift-left security); Feature-driven development | Intermediate |
| 120 | DevSecOps & CI/CD Security | CI/CD pipeline security; Infrastructure as Code (IaC) security; Container security scanning; Image signing; Secrets management; Pipeline integrity; Automated security gates; Shift-left testing; GitOps security | Intermediate |
| 121 | Programming Concepts & Security | Compiled vs. interpreted languages; Object-oriented programming (inheritance, polymorphism, encapsulation); Source code management; Code signing; Memory management; Garbage collection; Type safety; Input validation | Intermediate |
| 122 | Database Security | Relational database concepts; SQL injection (types, prevention); Inference attacks; Aggregation attacks; Polyinstantiation; Database views; Row-level security; Database encryption (TDE); NoSQL security; Data warehousing security | Advanced |
| 123 | Web Application Security – Part 1 | OWASP Top 10 (first 5): Broken Access Control, Cryptographic Failures, Injection, Insecure Design, Security Misconfiguration; HTTP methods; Session management; Input validation; Output encoding | Advanced |
| 124 | Web Application Security – Part 2 | OWASP Top 10 (last 5): Vulnerable Components, Authentication Failures, Software/Data Integrity Failures, Logging/Monitoring Failures, SSRF; XSS (reflected, stored, DOM); CSRF; Clickjacking; Content Security Policy (CSP) | Advanced |
| 125 | Secure Coding Practices | Input validation (whitelist/blacklist); Output encoding/escaping; Parameterized queries; Error handling (fail securely); Secure session management; Cryptographic best practices; Principle of least privilege in code; CERT Secure Coding Standards | Intermediate |
| 126 | Software Security Testing | Static Application Security Testing (SAST); Dynamic Application Security Testing (DAST); Interactive Application Security Testing (IAST); Runtime Application Self-Protection (RASP); SCA (Software Composition Analysis); Penetration testing for apps | Intermediate |
| 127 | APIs & Microservices Security | REST API security; GraphQL security; API authentication (API keys, OAuth, JWT); Rate limiting; API gateway; Microservices security patterns; Service mesh; Inter-service authentication; API versioning | Intermediate |
| 128 | AI/ML Security | AI/ML in security operations; Adversarial machine learning; Data poisoning; Model evasion; Model theft; Bias in security AI; Ethics of AI in security; Deepfakes; Automated threat detection | Intermediate |
| 129 | Third-Party Software Security | Commercial off-the-shelf (COTS) security; Open-source security risks; Software Composition Analysis (SCA); Software Bill of Materials (SBOM); Vendor security assessments; Library/dependency management; License compliance | Intermediate |
| 130 | **Domain 8 Review** | Comprehensive review of all Domain 8 topics; 20 MCQs covering entire domain; OWASP Top 10 summary; SDLC security controls matrix | Review |

---

### FINAL REVIEW & MOCK EXAMS — Days 131–140

| Day | Topic | Sub-Topics | Difficulty |
|-----|-------|------------|------------|
| 131 | Cross-Domain Review: D1 + D2 | Security & Risk Management deep dive; Asset Security deep dive; Interconnections between domains; Scenario-based questions; 20 mixed MCQs | Review |
| 132 | Cross-Domain Review: D3 + D4 | Architecture & Engineering deep dive; Network Security deep dive; Crypto + Network integration scenarios; 20 mixed MCQs | Review |
| 133 | Cross-Domain Review: D5 + D6 | IAM deep dive; Assessment & Testing deep dive; Access control + testing scenarios; 20 mixed MCQs | Review |
| 134 | Cross-Domain Review: D7 + D8 | Security Operations deep dive; Software Security deep dive; IR + SDLC integration scenarios; 20 mixed MCQs | Review |
| 135 | Mock Exam 1 | 125 questions across all domains; Timed (3 hours); CISSP-style scenario questions; Proportional domain coverage | Exam |
| 136 | Mock Exam 1 Review | Detailed answer review; Identify weak domains; Targeted study for weak areas; Key concept reinforcement | Review |
| 137 | Mock Exam 2 | 125 questions across all domains; Timed (3 hours); Increased difficulty; Focus on scenario and "think like a manager" questions | Exam |
| 138 | Mock Exam 2 Review | Detailed answer review; Progress comparison with Mock 1; Focus on remaining weak areas; Exam strategy refinement | Review |
| 139 | Mock Exam 3 | 125 questions across all domains; Timed (3 hours); Final comprehensive assessment; CAT-style adaptive difficulty simulation | Exam |
| 140 | Final Prep & Exam Strategy | Final weak-area review; Exam day logistics; Time management strategies; Question analysis techniques ("think like a manager"); CAT format tips; Confidence reinforcement; Last-minute key facts sheet | Review |

---

## Key Formulas Quick Reference (For Future Exercises)

| Formula | Equation |
|---------|----------|
| SLE | AV × EF |
| ALE | SLE × ARO |
| CBA Value | ALE(before) - ALE(after) - ACS |
| Risk | Threat × Vulnerability × Impact |
| MTD | RTO + WRT |
| MTBF | Total uptime / Number of failures |
| MTTR | Total downtime / Number of repairs |
| Availability | MTBF / (MTBF + MTTR) |
| CER/EER | Point where FRR = FAR |

---

## Study Tips (Embedded in Exercises)

- **Think like a manager**: CISSP tests management perspective, not just technical
- **Protect life first**: In any scenario, human safety is priority #1
- **Know the "why"**: Understand concepts, not just memorize facts
- **Eliminate wrong answers**: Use process of elimination for MCQs
- **Read carefully**: Scenario questions require full context analysis
- **Domain integration**: Real questions often span multiple domains

---

## Metadata (For AI Reference)

```yaml
version: 1.0
total_days: 140
mcq_per_day: 10
mcq_review_days: 20  # 20 MCQs on review days
theory_format: html
mcq_format: interactive_html
exercises_folder: exercises
completed_folder: completed
current_day: 0
status: not_started
```
