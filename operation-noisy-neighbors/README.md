# 🕵️ Operation: Noisy Neighbors

A beginner-friendly **web security / log analysis CTF challenge**.

Investigate a leaked server access log, identify malicious behavior, and extract hidden flags hidden inside noisy traffic.

---

## 📌 Challenge Overview

You are given a simulated web server access log containing:

- Normal user traffic
- Automated scanners
- Exploit attempts
- Suspicious payloads
- Encoded hidden data

Your task is to:
- Analyze request patterns
- Identify malicious IP behavior
- Decode hidden payloads
- Recover flags

---

## 🎯 Objective

Solve all challenges inside the web interface:

- Identify suspicious IPs
- Detect enumeration/scanning tools
- Decode encoded strings
- Spot sensitive endpoint exposure
- Extract the final hidden flag

---

## 🧩 Challenge Structure

There are **7 challenges total**:

| Difficulty | Topics |
|------------|--------|
| Easy       | Frequency analysis, endpoint detection |
| Medium     | User-Agent analysis, HTTP methods, decoding |
| Hard       | Sensitive path discovery, hidden payload extraction |

---

## 🚀 How to Run the Challenge

### Option 1: Open Locally
Simply open the HTML file in your browser: noisy_neighbors_ctf.html

Double-click or open with:
- Chrome (recommended)
- Firefox
- Edge


---

## 🧠 Skills Tested

This challenge is designed to simulate real-world SOC / blue-team analysis:

- Web server log analysis
- Threat intelligence basics
- IP behavior correlation
- HTTP request inspection
- Encoding/decoding (Base64, obfuscation)
- Reconnaissance detection

---


---

## 🧩 Flags Format

All flags follow this format: thm{...}
Example: thm{the_flag}


---

## ⚠️ Notes

- This is a **simulated environment**
- No real servers are accessed
- All logs are intentionally crafted for learning purposes
- Designed for beginners in cybersecurity / CTFs

---

## 🏁 Credits

Created by **[thatboringbro (redacted)](https://x.com/thatboringbro)**

For educational cybersecurity practice and CTF learning.

---

## 📢 Hint (Optional)

If you get stuck:

> Look for repetition patterns, unusual user-agents, and encoded paths. Not everything in the log is noise.

---

Happy hacking 🧠💻
