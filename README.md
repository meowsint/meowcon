## About tool

MeowCon Engine is a web-based reconnaissance toolkit designed for security researchers, bug hunters, and OSINT practitioners. It collects relevant publicly-available information about a target domain and opens curated search queries (dorks) across many public sources (crt.sh, Shodan, Censys, GitHub, Wayback, Google dorks, etc.).

**Key idea:** simplify recon by centralizing commonly-used dorks and OSINT sources into one compact interface so recon becomes faster, repeatable and shareable.

---

## Features

- **Subdomain finding:** quick links to crt.sh, SecurityTrails, Netcraft, Hunter, Censys, Shodan and wildcard Google dorks.  
- **Technology detector:** builtwith, W3Techs, WhatCMS and similar tools to identify tech stack and CMS.  
- **Port scanning:** convenient links to online port checkers and quick origin/IP lookup tools.  
- **URLs collecting:** Wayback/CDX, urlscan, VirusTotal, AlienVault/OTX and other URL-collection sources.  
- **All vulnerability Scanner:** curated parameter dorks for SQLi, XSS, LFI, RCE, SSRF, open-redirects and other common vulnerable parameter patterns.  
- **Github advance dorking:** pre-built GitHub/code search queries to find secrets, config files, tokens and leaks.  
- **Github custom payloads dorking:** load a payload list (raw URL) or paste custom payloads and generate GitHub search links automatically.  
- **CMS dorking:** WordPress-specific juicy dorks and phpMyAdmin/wp_users search helpers.  
- **Generic:** assorted Google dorks for sensitive files, backups, robots, phpinfo, server-status etc.  
- **cve search:** quick CVE/exploit lookup links (Exploit-DB, 0day.today, CISA, MITRE, etc.).

> **Workflow:** enter the **target domain** once (e.g. `example.com`). All buttons and payloads auto-replace `example.com` with your target, so recon is simplified and fast.

---

