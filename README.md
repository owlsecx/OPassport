# 🦉 OPassport

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OReconnaissance-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.1-cyan?style=flat-square"/>
</p>

> **OPassport** — IP Geolocation Intelligence Suite ║

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OPassport is an IP and domain geolocation intelligence suite. It resolves geolocation through multiple API providers with automatic fallback and adds WHOIS, DNS, threat-intelligence and offline IP-risk classification. Running it without flags opens its dark-mode GUI.

---

## ✨ Features

- Multi-API IP/domain geolocation with automatic fallback
- Offline IP classification and RFC/special-use categorisation with no network access
- Offline IP risk-scoring demonstration
- WHOIS, DNS record and threat-intelligence lookups
- CSV/JSON/TXT export, including writing JSON results to a file
- Dark-mode GUI alongside CLI flags for scripting

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OPassport --classify 8.8.8.8
./OPassport --lookup example.com --json-out out.json
./OPassport --risk-demo 10.0.0.1
./OPassport --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
