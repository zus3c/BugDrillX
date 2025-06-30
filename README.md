# BugDrillX - Learn. Hack. Evolve.

**BugDrillX** is a cybersecurity educational platform designed to guide beginners and professionals through the world of ethical hacking and bug bounty hunting. Powered by SCOLTECH, it offers a comprehensive roadmap to master offensive security techniques.

## Table of Contents

- [Project Description](#project-description)
- [Directory Structure](#directory-structure)
- [Tech Stack](#tech-stack)
- [Folder and File Explanations](#folder-and-file-explanations)
- [How to Run/View Locally](#how-to-runview-locally)
- [Contributing](#contributing)
- [License](#license)
- [Author Information](#author-information)

## Project Description

BugDrillX is an open-source web-based platform providing structured learning paths for bug bounty hunting and ethical hacking. It features a detailed roadmap covering reconnaissance, web and mobile application testing, network and cloud security, tools, and report writing. The platform is built with a modern, cyberpunk-themed interface to engage learners in a hands-on journey to become skilled security practitioners.

## Directory Structure

```
📁 BugDrillX
├── 📄 index.html
├── 📁 Reconnaissance
│   ├── 📁 Passive_Recon
│   │   ├── 📄 Google_Dorking.html
│   │   ├── 📄 WHOIS_Lookups.html
│   │   ├── 📄 Subdomain_Enumeration.html
│   │   └── 📄 OSINT_Tools.html
│   └── 📁 Active_Recon
│       ├── 📄 Port_Scanning.html
│       ├── 📄 Service_Enumeration.html
│       ├── 📄 Banner_Grabbing.html
│       └── 📄 Directory_Bruteforcing.html
├── 📁 Web_Application_Testing
│   ├── 📁 OWASP_Top_10
│   │   ├── 📄 Injection.html
│   │   ├── 📄 Broken_Authentication.html
│   │   ├── 📄 Sensitive_Data_Exposure.html
│   │   ├── 📄 XML_External_Entities.html
│   │   ├── 📄 Broken_Access_Control.html
│   │   ├── 📄 Security_Misconfiguration.html
│   │   ├── 📄 Cross_Site_Scripting.html
│   │   ├── 📄 Insecure_Deserialization.html
│   │   ├── 📄 CSRF.html
│   │   ├── 📄 Using_Components_with_Known_Vulnerabilities.html
│   │   └── 📄 Insufficient_Logging_and_Monitoring.html
│   ├── 📁 SQL_Injection
│   │   ├── 📄 Union_Based.html
│   │   ├── 📄 Error_Based.html
│   │   └── 📄 Blind_SQL_Injection.html
│   ├── 📁 Cross_Site_Scripting
│   │   ├── 📄 Stored_XSS.html
│   │   ├── 📄 Reflected_XSS.html
│   │   └── 📄 DOM_Based_XSS.html
│   ├── 📄 Remote_Code_Execution.html
│   ├── 📁 File_Inclusion
│   │   ├── 📄 LFI.html
│   │   └── 📄 RFI.html
│   ├── 📄 Business_Logic_Flaws.html
│   ├── 📄 IDOR.html
│   └── 📄 API_Security.html
├── 📁 Mobile_Application_Testing
│   ├── 📁 Android_Testing
│   │   ├── 📄 Static_Analysis.html
│   │   ├── 📄 Dynamic_Analysis.html
│   │   ├── 📄 Reverse_Engineering.html
│   │   └── 📄 Common_Vulnerabilities.html
│   └── 📁 iOS_Testing
│       ├── 📄 Static_Analysis.html
│       ├── 📄 Dynamic_Analysis.html
│       ├── 📄 Reverse_Engineering.html
│       └── 📄 Common_Vulnerabilities.html
├── 📁 Network_Security_Testing
│   ├── 📄 Network_Scanning.html
│   ├── 📄 Vulnerability_Scanning.html
│   ├── 📄 Exploitation.html
│   └── 📄 Post_Exploitation.html
├── 📁 Cloud_Security_Testing
│   ├── 📄 AWS_Security.html
│   ├── 📄 Azure_Security.html
│   ├── 📄 GCP_Security.html
│   └── 📄 Common_Vulnerabilities.html
├── 📁 Tools_and_Techniques
│   ├── 📁 Burp_Suite
│   │   ├── 📄 Configuration.html
│   │   ├── 📄 Extensions.html
│   │   └── 📄 Common_Use_Cases.html
│   ├── 📄 Nmap.html
│   ├── 📄 Metasploit.html
│   ├── 📄 Nikto.html
│   ├── 📄 Gobuster.html
│   ├── 📄 Sublist3r.html
│   ├── 📄 ReconNG.html
│   └── 📄 Other_Tools.html
├── 📁 Report_Writing
│   ├── 📄 Report_Template.html
│   ├── 📄 Vulnerability_Description.html
│   ├── 📄 Impact_Assessment.html
│   ├── 📄 Proof_of_Concept.html
│   ├── 📄 Remediation_Advice.html
│   └── 📄 Sample_Reports.html
├── 📁 Bugbounty_Learning_Resources
│   ├── 📄 Books.html
│   ├── 📄 Blogs.html
│   ├── 📄 Courses.html
│   ├── 📄 Conferences.html
│   ├── 📄 CTF_Platforms.html
│   └── 📄 About_Author.html
├── 📄 README.md
```

## Tech Stack

- **HTML5**: Structure and content of the website.
- **CSS3**: Styling with a dark, cyberpunk theme, including responsive design and animations.
- **JavaScript**: Interactive features like expandable folder trees and dynamic background animations.
- **Markdown**: Documentation (e.g., this README).
- **External Libraries**:
  - Font Awesome (for icons, e.g., logo shield).
  - (Optional) GSAP for advanced animations (if used in the homepage).

## Folder and File Explanations

- **`index.html`**: The homepage of BugDrillX, featuring a cyberpunk-themed interface with a roadmap, hero section, and navigation.
- **`Reconnaissance/`**: Covers information gathering techniques.
  - `Passive_Recon/`: Non-intrusive methods like Google Dorking, WHOIS Lookups, Subdomain Enumeration, and OSINT Tools.
  - `Active_Recon/`: Direct methods like Port Scanning, Service Enumeration, Banner Grabbing, and Directory Bruteforcing.
- **`Web_Application_Testing/`**: Focuses on vulnerabilities in web applications.
  - `OWASP_Top_10/`: Covers critical vulnerabilities like Injection, Broken Authentication, and XSS.
  - `SQL_Injection/`: Details Union-Based, Error-Based, and Blind SQL Injection techniques.
  - `Cross_Site_Scripting/`: Explains Stored, Reflected, and DOM-Based XSS.
  - Other files cover Remote Code Execution, File Inclusion (LFI/RFI), Business Logic Flaws, IDOR, and API Security.
- **`Mobile_Application_Testing/`**: Guides for testing Android and iOS apps.
  - `Android_Testing/` and `iOS_Testing/`: Include Static/Dynamic Analysis, Reverse Engineering, and Common Vulnerabilities.
- **`Network_Security_Testing/`**: Techniques for network scanning, vulnerability scanning, exploitation, and post-exploitation.
- **`Cloud_Security_Testing/`**: Security practices for AWS, Azure, GCP, and common cloud vulnerabilities.
- **`Tools_and_Techniques/`**: Tutorials on tools like Burp Suite (Configuration, Extensions, Use Cases), Nmap, Metasploit, Nikto, Gobuster, Sublist3r, ReconNG, and more.
- **`Report_Writing/`**: Guides for crafting professional bug bounty reports, including templates, vulnerability descriptions, impact assessments, proofs of concept, remediation advice, and sample reports.
- **`Bugbounty_Learning_Resources/`**: Curated resources like books, blogs, courses, conferences, CTF platforms, and author information.
- **`README.md`**: This file, providing project overview and setup instructions.

## How to Run/View Locally

1. **Clone the Repository**:
   ```bash
   https://zus3c.github.io/BugDrillX/main.html
   ```
   [BugDrillX](https://zus3c.github.io/BugDrillX/main.html)
   
## Contributing

BugDrillX welcomes contributions from the community! To contribute:

1. **Fork the Repository**:
   - Click the "Fork" button on GitHub to create your own copy.

2. **Create a Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author Information

**Zubair Usman**  
- **Role**: Cybersecurity Content Creator / Developer  
- **Handle**: [@Zus3c](https://github.com/Zus3c)  
- **Social Links**:
  - [LinkedIn](https://www.linkedin.com/in/zubair-usman)
  - [GitHub](https://github.com/Zus3c)
  - [Twitter/X](https://x.com/Zus3c)

**Powered by**: [SCOLTECH](https://pk.linkedin.com/company/scoltech)

---

*BugDrillX © 2025 – Learn. Hack. Evolve.*
