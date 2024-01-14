# SploitScan

## 📜 Description

SploitScan is a powerful and user-friendly tool designed to streamline the process of identifying exploits for known vulnerabilities and their respective exploitation probability. Empowering cybersecurity professionals with the capability to swiftly identify and apply known and test exploits. It's particularly valuable for professionals seeking to enhance their security measures or develop robust detection strategies against emerging threats.

## 🌟 Features

- **CVE Information Retrieval**: Fetches CVE details from the National Vulnerability Database.
- **EPSS Integration**: Includes Exploit Prediction Scoring System (EPSS) data, offering a probability score for the likelihood of CVE exploitation, aiding in prioritization.
- **PoC Exploits Aggregation**: Gathers publicly available PoC exploits, enhancing the understanding of vulnerabilities.
- **CISA KEV**: Shows if the CVE has been listed in the Known Exploited Vulnerabilities (KEV) of CISA.
- **User-Friendly Interface**: Easy to use, providing clear and concise information.
- **Comprehensive Security Tool**: Ideal for quick security assessments and staying informed about recent vulnerabilities.

## 🚀 Usage

```bash
python sploitscan.py CVE-YYYY-NNNNN
```

<img width="862" alt="image" src="https://github.com/xaitax/SploitScan/assets/5014849/5414a8a8-67ae-4fcf-b3b3-3c5003892e08">

## Contributing
Contributions are welcome. Please feel free to fork, modify, and make pull requests or report issues.

## 📌 Author

**Alexander Hagenah**
- [URL](https://primepage.de)
- [Twitter](https://twitter.com/xaitax)

## 👏 Credits

- [NIST NVD](https://nvd.nist.gov/developers/vulnerabilities)
- [FIRST EPSS](https://www.first.org/epss/api)
- [CISA Known Exploited Vulnerabilities Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)
- [nomi-sec PoC-in-GitHub API](https://poc-in-github.motikan2010.net/)

## ⚠️ Disclaimer

This tool is meant for educational and professional purposes only.
