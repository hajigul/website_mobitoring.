# Website Statistics Analyzer

A lightweight Python tool that collects useful technical, security, and content information about any website — perfect for quick reconnaissance, SEO checks, competitor analysis, or domain due diligence.

Runs best in **Google Colab**, Jupyter notebooks, or any Python environment.

## Features

- HTTP connection & redirect analysis
- Page load time & content size
- Server & CDN detection
- Important security headers check
- WHOIS registration details (creation & expiration dates)
- SSL/TLS certificate validity & issuer info
- Basic on-page SEO signals (title, meta description, H1 count, etc.)
- CMS detection (WordPress, Shopify, Joomla)
- Social media links discovery
- Results saved as CSV + displayed as pandas DataFrame

## Requirements

- Python 3.7+
- Libraries:
  - requests
  - beautifulsoup4
  - pandas
  - python-whois
  - whois (optional fallback)

## Installation (Google Colab / Jupyter)

```bash
!pip install requests beautifulsoup4 pandas python-whois -q
