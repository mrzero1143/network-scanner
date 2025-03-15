# MR ZERO X-Treme Scanner

![Python](https://img.shields.io/badge/python-3.x-blue)
![License](https://img.shields.io/badge/license-MIT-green)

**MR ZERO X-Treme Scanner** adalah alat scanning jaringan canggih dengan fitur GeoIP lookup, real-time threat intelligence, dan banyak lagi.

## Fitur Utama
- Host Discovery (ICMP Ping Scan)
- OS Fingerprinting menggunakan Nmap
- Covert SYN Port Scanning
- Service Detection & Vulnerability Correlation
- GeoIP Lookup
- Dark Web Exposure Check
- Real-time Threat Intelligence
- Network Map Visualization

## Instalasi

```bash
# Clone repository
git clone https://github.com/mrzero1143/network-scanner.git
cd network-scanner

# Buat virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r src/requirements.txt