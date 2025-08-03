# Forensic-Analysis-M57.biz Data Leak

## 📄 Project Overview
This repository contains a digital forensic analysis report detailing a data breach incident involving **M57.biz**, a startup company in the body art industry. The investigation focused on identifying the source and method of an unauthorized disclosure of a confidential file (`m57plan.xls`), which was found on a competitor’s support forum.

---

## 🔍 Summary of Findings
- The leaked file originated from the CFO Jean’s computer.
- A spoofed email was sent to Jean, appearing to be from the company president, Alison.
- Jean unintentionally sent the confidential file in response to this phishing email.
- Forensic tools like **EnCase** and **Autopsy** were used for evidence collection and verification.
- No involvement was found from other employees.

---

## 🧪 Forensic Tools Used
- **EnCase**: For disk and metadata analysis.
- **Autopsy**: For Outlook `.pst` file investigation.
- **MD5 Hashing**: For file and disk integrity validation.

---

## 📅 Key Timeline
| Event | Timestamp |
|-------|-----------|
| File Creation | July 20, 2008 – 1:28:03 AM |
| Spoofed Email Received | July 20, 2008 – 5:39:47 AM |
| File Discovered Online | April 21, 2008 |

---

## ✅ Security Recommendations
1. **Employee Training**: Recognize spoofed and phishing emails.
2. **Email Security**: Implement SPF, DKIM, and DMARC.
3. **Secure File Sharing**: Use encrypted platforms instead of email for sensitive files.
4. **Access Control**: Apply role-based permissions and encryption.
5. **Incident Response**: Establish a formal response plan and conduct regular audits.

---

## 📁 Contents
- 📘 [`Forensic-Analysis-M57.biz Data Leak.pdf`](./Forensic-Analysis-M57.biz%20Data%20Leak.pdf) — *Click to download the full report*

---

## 👨‍💻 Author
**Hasnain Khan**  
