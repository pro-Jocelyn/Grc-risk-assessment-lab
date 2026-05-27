risk-register.md
# Risk Register

| Risk ID | Asset | Risk Description | Threat | Vulnerability | Impact | Likelihood | Risk Score | Risk Level | Recommended Control |
|---|---|---|---|---|---|---|---|---|---|
| R-001 | Electronic Health Record System | Unauthorized access to patient records | Insider misuse or stolen credentials | No multi-factor authentication | 3 | 3 | 9 | High | Enable MFA and role-based access |
| R-002 | Employee Workstations | Patient data exposed from lost or stolen devices | Device theft | No full-disk encryption | 3 | 2 | 6 | High | Encrypt all clinic devices |
| R-003 | Email System | Employee clicks phishing email and exposes credentials | Phishing | Limited security awareness training | 3 | 3 | 9 | High | Conduct phishing and security awareness training |
| R-004 | Patient Records | Former employee still has access to patient data | Unauthorized access | No formal access termination process | 3 | 2 | 6 | High | Create user access removal procedure |
| R-005 | Wi-Fi Network | Unauthorized users connect to clinic network | Network intrusion | Weak Wi-Fi password or shared access | 2 | 2 | 4 | Medium | Use strong Wi-Fi security and separate guest network |
| R-006 | Backup System | Patient records cannot be restored after ransomware | Ransomware | Backups are not tested regularly | 3 | 2 | 6 | High | Test backups quarterly |
| R-007 | Front Desk Computer | Patient information visible to unauthorized people | Privacy exposure | Screen left unlocked | 2 | 2 | 4 | Medium | Enable automatic screen lock |
| R-008 | Cloud File Storage | Patient documents shared with the wrong person | Accidental disclosure | Poor file sharing controls | 3 | 2 | 6 | High | Restrict sharing permissions and review access |
