# 🕸️ RERA Odisha Web Scraping Project

This project is a Python-based web scraper that automates the extraction of real estate project data from the [RERA Odisha Portal](https://rera.odisha.gov.in). It uses Selenium to navigate through project detail pages and extracts key information like project name, promoter details, GST number, and more.

---

## 📌 Features

 Navigates to **RERA Odisha** official project listing page
- Extracts:
  - 🆔 RERA Registration Number
  - 🏢 Project Name
  - 👤 Promoter Name
  - 📍 Promoter Address
  - 💼 GST Number
- Clicks into each project detail page
- Handles dynamic page content and tab navigation
- Stores results in `rera_top6_projects.json`

---

## ⚙️ Requirements

> ✅ **Google Chrome must be installed on your system**  
> ✅ **Selenium must be installed via pip**

Install Selenium using:

```bash
pip install selenium

---

## 📁 Sample Output

```json
[
  {
    "rera_registration_no": "OD123456789",
    "project_name": "Green Valley Heights",
    "promoter_name": "ABC Developers Pvt Ltd",
    "promoter_address": "Plot No. 123, Bhubaneswar, Odisha",
    "gst_no": "22ABCDE1234F2Z5"
  },
  ...
]
