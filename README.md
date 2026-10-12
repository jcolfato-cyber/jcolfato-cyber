# Cybersecurity Portfolio | Jon Carlo Yuzon Olfato

Sydney-based cybersecurity graduate candidate completing a Master of Business Information Systems (Cyber Security) in December 2026, with CompTIA Security+ certification and enterprise experience spanning governance, compliance, IAM, business systems, and operational analytics. Developing hands-on cybersecurity capabilities through Active Directory, RBAC, Group Policy, PowerShell, infrastructure security, vulnerability assessment, and security assurance, with a focus on Cybersecurity, Technology Risk, GRC, and Systems Analysis.

My current portfolio is centred on an interconnected enterprise banking cybersecurity environment designed to demonstrate the progression from secure infrastructure and identity architecture through technology risk, cloud security, and security monitoring.

Before transitioning into cybersecurity, I worked in engineering roles at Samsung Electro-Mechanics Philippines, where my experience included operational analytics, compliance initiatives, documentation control, process improvement, enterprise reporting, and collaboration across engineering and IT stakeholders.

This background developed a strong appreciation for operational reliability, governance, audit readiness, data integrity, and disciplined technical documentation.

## Education

### Master of Business Information Systems (Cyber Security)

Australian Institute of Higher Education, Australia

- Expected completion: **December 2026**
- Current GPA: **6.50 / 7.00**

## Enterprise Banking Cybersecurity Portfolio

The Enterprise Banking Cybersecurity Portfolio is a five-repository security programme built around an interconnected banking laboratory environment.

Rather than treating each repository as an isolated exercise, the portfolio progressively develops the same enterprise environment across infrastructure security, identity architecture, governance and technology risk, cloud security, and security operations.

The programme follows a practical security lifecycle:

### Infrastructure → Identity → Governance → Cloud → Detection

| Repository | Security Domain | Status |
| --- | --- | --- |
| [Secure Enterprise Network Lab](https://github.com/jcolfato-cyber/secure-enterprise-network-lab) | Network Security / Infrastructure Security | **Completed** |
| [Enterprise Banking IAM Architecture](https://github.com/jcolfato-cyber/enterprise-banking-iam-architecture) | IAM / Active Directory / Privileged Access | **Completed** |
| Enterprise Banking GRC Assessment | GRC / Technology Risk | **Design Complete - Implementation in progress** |
| Cloud Banking Infrastructure Hardening | Cloud Security / Infrastructure Hardening | **Planned** |
| Enterprise Banking Security Monitoring & AD Threat Detection | Security Operations / SIEM / Detection Engineering | **Planned** |

### Secure Enterprise Network Lab

**Repository:** [secure-enterprise-network-lab](https://github.com/jcolfato-cyber/secure-enterprise-network-lab)

Enterprise UTM/QEMU infrastructure lab providing the isolated network, Active Directory, and system foundation for the interconnected banking cybersecurity portfolio.

The environment consists of Windows Server 2022, Windows 11 Pro, Ubuntu Server, and Kali Linux systems operating across an isolated Host-Only `10.10.10.0/24` network.

Key implementation areas include:

- UTM/QEMU enterprise virtual infrastructure
- Windows Server 2022 Active Directory Domain Services and DNS
- `banking.lab` Active Directory domain
- Windows 11 corporate workstation integration
- Ubuntu security monitoring foundation
- Kali Linux controlled security-testing workstation
- Static IPv4 addressing and Host-Only network isolation
- Cross-platform connectivity and infrastructure validation
- Evidence-backed architecture and deployment documentation

### Enterprise Banking IAM Architecture

**Repository:** [enterprise-banking-iam-architecture](https://github.com/jcolfato-cyber/enterprise-banking-iam-architecture)

Enterprise Identity and Access Management architecture implemented within the `banking.lab` Active Directory environment.

The project extends the infrastructure foundation into a structured identity control plane incorporating administrative tiering, role-based access, privileged identities, service identities, Group Policy security controls, PowerShell provisioning, and independent security assurance.

Key implementation areas include:

- Tiered Active Directory architecture across Tier 0, Tier 1, and Tier 2 administrative boundaries
- Role-Based Access Control (RBAC) through Active Directory Global Security Groups
- Privileged administrative separation
- Standard, privileged, and service identity governance
- PowerShell-based identity provisioning
- Group Policy security controls
- Password and account lockout policy
- LDAP signing enforcement
- Service-account interactive logon restrictions
- Independent read-only IAM assurance framework

Final assurance outcome: `14 PASS | 0 FAIL | 2 WARN`

The project closed with zero mandatory control failures and a documented residual observation retained for transparency.

### Enterprise Banking GRC Assessment

Repository: Not yet published

The current portfolio project has completed its assessment design and implementation is in progress. It will evaluate the existing banking environment from governance, technology risk, and security-control perspectives.

Framework hierarchy:

- **APRA CPS 234** — primary regulatory and prudential lens
- **ACSC Essential Eight** — technical security maturity assessment
- **ISO/IEC 27001:2022** — supporting governance and ISMS control alignment

ISO/IEC 27001:2022 will be used for defensible control alignment and gap assessment rather than represented as a certification-style compliance audit.

The assessment will use evidence from the implemented banking environment to identify risk, evaluate control maturity, document security gaps, and establish remediation priorities.

### Cloud Banking Infrastructure Hardening

Repository: Not yet published

This repository will extend the banking security architecture into AWS and focus on secure cloud infrastructure design and configuration hardening.

Planned areas include:

- AWS security architecture
- Cloud Identity and Access Management
- Network security and segmentation
- Logging and security visibility
- Encryption and data protection
- Configuration hardening
- Security validation
- Recognised cloud security and hardening practices

### Enterprise Banking Security Monitoring & AD Threat Detection

Repository: Not yet published

The final banking portfolio repository will complete the defensive lifecycle by introducing centralised security monitoring, detection engineering, and identity-threat validation.

Planned areas include:

- Microsoft Sentinel
- Security telemetry collection
- Windows and Linux log analysis
- Active Directory security monitoring
- Detection engineering
- Suspicious identity behaviour detection
- Alert investigation
- Security control validation
- Correlation of attack behaviours with implemented defensive controls

## Technical Capabilities

### Identity & Access Management

- Active Directory Domain Services
- Active Directory architecture
- Organisational Unit design
- Role-Based Access Control (RBAC)
- Active Directory Global Security Groups
- Administrative tiering
- Privileged access separation
- Group Policy
- Identity provisioning
- Service-account controls
- Least privilege
- PowerShell automation and assurance

### Infrastructure & Network Security

- Windows Server 2022
- Windows 11 Pro
- Ubuntu Server
- Kali Linux
- UTM/QEMU virtualisation
- Mixed x86_64 and ARM64 environments
- Host-Only network architecture
- Static IPv4 addressing
- DNS and domain infrastructure
- Infrastructure validation
- Technical evidence collection

### Security Assessment & Architecture

- Security control validation
- Vulnerability assessment
- Network reconnaissance
- Threat modelling
- STRIDE methodology
- Trust boundary analysis
- Security architecture review
- Risk-based remediation planning

### Governance, Risk & Compliance

- Technology risk assessment
- Security control mapping
- Control gap analysis
- APRA CPS 234 concepts
- ACSC Essential Eight
- ISO/IEC 27001:2022 control-alignment concepts
- Security documentation and evidence management

### Tools & Platforms

- PowerShell
- Git and GitHub
- Visual Studio Code
- Wireshark
- Nmap
- Nessus
- OWASP Threat Dragon
- Windows Server
- Linux
- UTM
- QEMU

## Certifications & Professional Development

My certification and professional development roadmap complements the portfolio by building structured knowledge across security, governance, and cloud technologies alongside hands-on implementation.

| Certification / Development | Status | Target | Focus |
| --- | --- | --- | --- |
| [CompTIA Security+ (SY0-701)](https://www.credly.com/badges/7293ae0d-fb82-4b78-9743-39c3d8e70929/public_url) | **Completed** | October 2026 | Security operations, threats, vulnerabilities and security controls |
| [Google Cybersecurity Professional Certificate](https://www.credly.com/badges/fd69647e-8cef-4974-ad6c-a89f5ddab537/public_url) | **Completed** | May 2026 | Cybersecurity fundamentals, SIEM concepts, incident response and risk |
| GRC Mastery | Planned | November 2026 | Governance, technology risk, policy and compliance |
| Certificate of Cloud Security Knowledge (CCSK v5) | Planned | December 2026 | Cloud architecture, governance and security controls |
| AWS Certified Solutions Architect – Associate | Planned | Early 2027 | AWS architecture, infrastructure design and resilient cloud solutions |

## Earlier Cybersecurity Projects

These repositories represent earlier hands-on cybersecurity work completed before the development of the interconnected enterprise banking portfolio.

### Hospital Active Directory Security Lab

**Repository:** [hospital-active-directory-lab](https://github.com/jcolfato-cyber/hospital-active-directory-lab)

Built an enterprise-style Windows Server 2022 Active Directory environment using a simulated healthcare organisation.

Implemented organisational unit structures, user and group administration, role-based access, Group Policy restrictions, shared-folder permissions, and a domain-joined Windows 11 workstation.

### Online Banking STRIDE Threat Model

**Repository:** [online-banking-stride-threat-model](https://github.com/jcolfato-cyber/online-banking-stride-threat-model)

Developed a STRIDE threat model for a simulated online banking platform using OWASP Threat Dragon.

Assessed authentication, trust boundaries, transaction integrity, data protection, availability risk, and security-control requirements across the modelled banking architecture.

## Connect

- **LinkedIn:** [Jon Carlo Yuzon Olfato](https://www.linkedin.com/in/joncarloolfato)
- **GitHub:** [jcolfato-cyber](https://github.com/jcolfato-cyber)
