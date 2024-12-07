# 🐬 Sublist3r - Subdomain Enumeration Tool

Sublist3r is a fast and efficient subdomain enumeration tool designed to help security professionals identify an organization's subdomains. By leveraging search engines and various APIs, Sublist3r allows users to discover hidden subdomains and gain insights into the attack surface of a domain. This tool is essential for reconnaissance in penetration testing and security assessments.

---

## 🔍 What is Sublist3r?

Sublist3r is an open-source tool that automates the process of subdomain enumeration. It uses search engines like Google, Bing, Yahoo, and others to find subdomains associated with a domain. Sublist3r is highly effective for reconnaissance tasks in penetration testing, vulnerability assessments, and attack surface mapping.

---

## 📥 Getting Started

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/aboul3la/Sublist3r.git
   cd Sublist3r
Install required dependencies:

bash
Copy code
pip install -r requirements.txt
Run Sublist3r:

To perform subdomain enumeration for a domain, use the following command:

bash
Copy code
python sublist3r.py -d example.com
Replace example.com with the domain you wish to scan.

🛠️ Features
Multiple Sources: Sublist3r uses search engines like Google, Bing, Yahoo, and others to enumerate subdomains.
Brute Force Support: Perform brute-force subdomain enumeration for more exhaustive results.
Threaded Scanning: Uses threading to speed up the enumeration process.
Export Options: Results can be exported in various formats like CSV and JSON for easy analysis.
API Integration: Leverages multiple public APIs for improved enumeration.
📚 Usage
Command-Line Arguments
-d <domain>: Target domain to scan.
-p <ports>: Specify ports to scan.
-v: Enable verbose output for detailed progress.
-o <filename>: Save results to a file.
Example usage:

bash
Copy code
python sublist3r.py -d example.com -v -o subdomains.txt
This will scan example.com, print detailed output, and save the results in subdomains.txt.

📘 Resources
Official Repository: Sublist3r GitHub
Documentation: Sublist3r Wiki
Sublist3r Blog: Sublist3r Blog
Common Use Cases: Penetration testing, reconnaissance, attack surface mapping, and identifying exposed subdomains.
🤝 Contributing
We welcome contributions! Feel free to open issues, submit bug reports, or create pull requests with improvements, new features, or enhancements. Please refer to the CONTRIBUTING.md for more details.

🛡️ License
Sublist3r is open-source and distributed under the GNU General Public License v3.0. See the LICENSE file for more details.

🌐 About Sublist3r
Sublist3r is developed and maintained by Aboul3la. It is actively used in penetration testing and vulnerability assessments, making it an essential tool for any security professional.

⭐ Show Your Support
If you find this repository useful, please give it a ⭐ and share it with others!
