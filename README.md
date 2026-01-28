# CRYPTVAULT

**Secure. Offline. Zero-Knowledge.**

CryptVault is a military-grade text encryption tool designed for absolute privacy. It runs entirely on your device using the Web Crypto API. No servers. No cloud. No tracking.

---

<p align="center">
  <a href="https://github.com/potatameister/CryptVault/releases/latest">
    <img src="https://img.shields.io/badge/ANDROID-DOWNLOAD_APK-000000?style=for-the-badge&logo=android&logoColor=white" alt="Download APK">
  </a>
  <a href="https://potatameister.github.io/CryptVault/">
    <img src="https://img.shields.io/badge/WEB-OPEN_APP-000000?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Web Version">
  </a>
  <a href="https://github.com/sponsors/potatameister">
    <img src="https://img.shields.io/badge/SPONSOR-GITHUB-000000?style=for-the-badge&logo=github&logoColor=white" alt="Sponsor">
  </a>
</p>

---

## VISUALS

<p align="center">
  <img src="screenshots/screenshot1.jpg" width="300" style="border-radius: 12px; margin: 10px;" />
  <img src="screenshots/screenshot2.jpg" width="300" style="border-radius: 12px; margin: 10px;" />
</p>

## THE ARCHITECTURE

CryptVault is built on the principle that privacy is a human right.

*   **Offline First:** The code executes locally in your browser or on your Android device.
*   **Audit Ready:** Open-source architecture allows for full transparency.
*   **Standards Compliant:** Utilizes native AES-256-GCM and PBKDF2 key derivation (250,000 iterations).

## ENCRYPTION METHODS

| Protocol | Security Level | Use Case |
| :--- | :--- | :--- |
| **AES-GCM** | HIGH (Recommended) | Authenticated encryption. Detects tampering. |
| **AES-CBC** | HIGH | Standard block cipher chaining. Robust compatibility. |
| **AES-CTR** | MEDIUM | Counter mode. High speed for large datasets. |
| **Triple Layer** | MAXIMUM | Base64 encoding wrapped in AES-GCM wrapped in Base64. |
| **Simple** | LOW | Deterministic. Identical input yields identical output. |

## SUPPORT THE PROTOCOL

CryptVault is 100% free, open-source, and ad-free. If you value privacy tools, consider supporting the continued development.

### GitHub Sponsors

[Support via GitHub](https://github.com/sponsors/potatameister)

### Crypto Channels

**Monero (XMR) - Private**
```text
85rGKZsK4W7ENiP2xmTwDPG11W9uswJob4xgcQeby13wUFyRrWAhFzHN6nLSmQi1kV58tzUhswYqR5E1txL2HnCg6fP5gn6
```

**Bitcoin (BTC)**
```text
bc1qpamdenvjmzmjumz24s3hymcn77xu8gy9ur04ll
```

## LICENSE

Copyright 2024 potatameister.
Distributed under the MIT License.