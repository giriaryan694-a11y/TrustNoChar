# TrustNoChar 🛡️👁️

### *Human perception is the weakest link. Verify, don't trust.*

---

# 🌐 Overview

**TrustNoChar** is a zero-dependency, client-side laboratory designed to demonstrate how **typosquatting**, **Unicode homoglyph abuse**, and **visual rendering quirks** exploit human cognitive autopilot.

Paste domains, usernames, passwords, or paragraphs into the sandbox and instantly watch them transform into visually deceptive Unicode variants in real time.

The project was built for:

* 🛡️ Security awareness training
* 🎯 Red-team phishing simulations
* 🔍 Unicode spoofing research
* 🧠 Cognitive security demonstrations
* 🎨 UI/UX readability analysis
* 🧪 Browser rendering experiments

Everything runs fully offline inside the browser.
No frameworks. No telemetry. No tracking. No backend.

> “Typosquatting attacks the brain’s prediction engine, not the DNS protocol.”

---

# 🚀 Live Demo

## 🌐 Try It Here

link Demo : [https://giriaryan694-a11y.github.io/TrustNoChar/](https://giriaryan694-a11y.github.io/TrustNoChar/)

---

# ✨ Features

## 🎚️ Adjustable Deception Intensity

Dynamically control spoof density from:

* **0%** → Clean untouched text
* **100%** → Maximum homoglyph corruption

The probabilistic substitution engine preserves realism instead of replacing every character.

---

## 🔤 Real-Time Font Rendering Analysis

Switch between:

* Sans Serif
* Monospace
* Serif

This exposes how:

* `rn → m`
* `I → l`
* `0 → O`
* `vv → w`

become visually indistinguishable depending on kerning and font fallback behavior.

---

## 🔍 Unicode X-Ray Hover Inspection

Hover over spoofed characters to reveal:

```text
Original: a (U+0061)
Spoofed : а (U+0430)
```

This makes invisible Unicode abuse visible for awareness training and security education.

---

## 📋 One-Click Spoof Export

Export spoofed output instantly for:

* Authorized phishing simulations
* Threat intelligence testing
* Defensive monitoring
* Detection rule creation
* CTF challenges
* Homoglyph dataset generation

---

## 🛡️ Fully Client-Side

TrustNoChar is intentionally minimal.

### No:

* External APIs
* Frameworks
* Analytics
* Trackers
* Cloud processing
* Data collection

Everything executes locally inside the browser.

---

# 🧠 How It Works

## 🔡 Homoglyph Matrix Engine

The application maintains a curated Unicode substitution matrix containing visually similar characters from:

* Cyrillic
* Greek
* IPA Extensions
* Latin Extended
* Mathematical Unicode
* Fullwidth Unicode
* Modifier Symbols

Example:

| Original | Spoofed |
| -------- | ------- |
| a        | а       |
| e        | е       |
| o        | ο       |
| l        | ӏ       |
| A        | Α       |

These characters appear visually identical while remaining computationally distinct.

---

## 🎲 Probabilistic Mutation Logic

Instead of replacing all characters, TrustNoChar performs:

* Weighted random substitutions
* Context-aware mutation density
* Partial spoof preservation

This better simulates real-world typosquatting campaigns where subtlety increases success rates.

---

## 🖋️ Font Rendering Exploitation

The project demonstrates how browsers and operating systems:

* Collapse kerning
* Apply fallback glyph rendering
* Normalize spacing inconsistently
* Render Unicode differently across fonts

The same spoof can appear harmless in monospace but dangerous in sans-serif rendering.

---

## ⚠️ NFKC Normalization Demonstration

Modern browsers normalize many Unicode sequences using:

```text
NFKC (Normalization Form Compatibility Composition)
```

TrustNoChar intentionally demonstrates controlled bypass scenarios to show why:

> Visual inspection is not identity verification.

Cryptographic trust, domain validation, and canonical comparison matter more than appearance.

---

# ⚙️ Usage

## 1️⃣ Open the Application

Launch:

```text
index.html
```

inside any modern browser.

---

## 2️⃣ Paste Target Text

Examples:

```text
github.com
SecureLogin2026
Aryan Giri
admin@company.com
```

---

## 3️⃣ Adjust Spoof Intensity

Use the slider to control substitution probability.

Higher intensity = heavier Unicode corruption.

---

## 4️⃣ Toggle Fonts

Observe how rendering changes across:

* Serif
* Sans
* Monospace

---

## 5️⃣ Inspect Unicode Traps

Hover over highlighted characters to inspect:

* Original glyph
* Spoofed glyph
* Unicode code points

---

## 6️⃣ Export Output

Click:

```text
Copy Spoofed Text
```

to export the generated payload.

---

# 🔬 Example Attack Scenarios

| Legitimate       | Spoofed          |
| ---------------- | ---------------- |
| github.com       | gіthub.com       |
| microsoft.com    | micrοsoft.com    |
| paypal.com       | paypaӏ.com       |
| secure-login.com | secure-ӏogin.com |

These domains may appear legitimate at first glance while remaining entirely different Unicode strings.

---

# 🎯 Research Applications

TrustNoChar can assist with:

* Unicode security awareness
* Typosquatting research
* Anti-phishing education
* Browser rendering analysis
* Security conference demonstrations
* SOC analyst training
* Red-team payload visualization
* Accessibility & readability testing
* Cognitive bias experiments

---

# 🧱 Project Philosophy

TrustNoChar focuses on a critical reality:

```text
Humans trust visual similarity.
Computers trust exact byte sequences.
Attackers exploit the gap between them.
```

The goal is not malware development.
The goal is awareness through controlled visualization.

---

# 🛡️ Ethics & Security Disclaimer

⚠️ This project is intended strictly for:

* Educational use
* Defensive security awareness
* Authorized red-team simulations
* Research environments
* Controlled demonstrations

Do not use this tool for:

* Fraud
* Unauthorized phishing
* Brand impersonation
* Credential theft
* Malicious deception

All processing occurs locally in the browser.
No user data is stored, transmitted, or logged.

---

# 📂 Tech Stack

* HTML5
* CSS3
* Vanilla JavaScript
* Unicode
* Browser Rendering APIs

Zero dependencies.


# 📜 License

MIT License

---

# 👨‍💻 Author

**Written by Aryan Giri**

🛡️ Verify. Don't trust.
