# Privacy Policy for Wealth-Meter

**Last Updated:** October 5, 2026  
**Effective Date:** October 5, 2026  
**Application:** Wealth-Meter (`com.wealthmeter.app`)  
**Developer:** Samidha Potphode  
**Contact:** `samidhapurushottampotphode@gmail.com`

---

## 1. Overview & Privacy-First Philosophy

Welcome to **Wealth-Meter**. Your financial privacy is our highest priority. Wealth-Meter is designed from the ground up on the principle of **"Privacy by Design and Default"**. 

Unlike conventional financial apps that require you to link bank accounts, create cloud profiles, or upload your asset ledgers to external servers, **Wealth-Meter operates entirely on-device**. We do not run proprietary backend databases that store, process, sell, or monetize your portfolio, balances, transactions, or identities.

---

## 2. Information We Collect and Process

### A. Personal & Financial Portfolio Data (Stored Locally Only)
When you use Wealth-Meter, you may manually enter financial records, including:
- Asset holdings (stocks, mutual funds, fixed/recurring deposits, provident funds, real estate, precious metals, cash).
- Transaction amounts, purchase prices, quantities, and maturity terms.
- Liabilities (loans, mortgages, APRs, and monthly EMIs).
- Financial goals, milestone targets, and multi-profile family tags.

> **Storage Guarantee:** All such financial data is stored **strictly on your local device storage** using encrypted Android storage structures (AES-256 GCM). None of your asset quantities, personal names, account values, or financial records are ever transmitted to or stored on our servers.

### B. Biometric Authentication Data
If you enable **Biometric App Lock** (Fingerprint, Face Unlock, or Device PIN):
- Authentication is handled exclusively by the official Android OS `BiometricPrompt` and Android KeyStore APIs.
- Wealth-Meter **never** accesses, reads, collects, or transmits your biometric samples or raw biometric data. The operating system only returns a cryptographic pass/fail verification token to the app.

### C. Live Market Quotes & Currency Conversion Queries
When you refresh current market prices (CMP) or check exchange rates:
- The app sends outbound network requests to public financial endpoints (e.g., Yahoo Finance API, Open.er-api FX exchange rate feeds).
- **Only public identifiers** (such as ticker symbols like `RELIANCE.NS` or currency codes like `USD/INR`) are queried.
- **No private portfolio details**, investment amounts, user IDs, or balance figures are ever attached to these price requests.

### D. Device and Technical Information
Standard technical diagnostics (such as Android OS version, device model, and network state `ACCESS_NETWORK_STATE`) may be evaluated locally by the operating system solely to ensure proper app rendering, internet connectivity detection for live price updates, and responsive layout behavior.

---

## 3. Third-Party Services & SDKs

Wealth-Meter integrates trusted third-party SDKs strictly to provide monetization and store functionalities:

### 1. Google Play In-App Billing (Google LLC)
- Used to process purchases for Wealth-Meter Ad-Free and Pro lifetime tiers.
- Purchases and payment transactions are handled directly by Google Play. We do not collect, process, or store credit card numbers, banking details, or billing addresses.
- [Google Play Privacy Policy](https://policies.google.com/privacy)

### 2. Google Mobile Ads (AdMob by Google LLC)
- Wealth-Meter displays banner advertisements exclusively to users on the Free tier.
- AdMob may collect and process device identifiers (such as Android Advertising ID), general geographic location, and app interaction data to deliver contextual or personalized advertising in accordance with Google's advertising policies.
- **Opt-Out:** Users can eliminate all advertisements and third-party advertising tracking permanently by upgrading to the Ad-Free or Pro tier via the in-app subscription hub.
- [Google AdMob Privacy Policy](https://support.google.com/admob/answer/6128543?hl=en)

---

## 4. Data Security & Storage (OWASP MASVS Aligned)

We implement robust defensive security controls to safeguard your financial privacy on your physical device:

1. **Hardware-Backed Encryption:** Portfolio data and backups are secured using AES-256 GCM encryption.
2. **Screen Protection Guard (FLAG_SECURE):** Users can enable the Screen Protection Guard setting to block unauthorized screenshots, prevent screen recordings, and hide confidential portfolio balances from appearing in the Android task switcher/recent apps preview.
3. **Stealth Privacy Mode:** A one-tap toggle allows masking exact currency balances with privacy bullets (`••••••`) when viewing portfolios in public spaces.
4. **Zero Account Telemetry:** We do not maintain user databases, tracking pixels, or third-party behavioral analytics trackers (such as Facebook SDK or marketing trackers).

---

## 5. User Rights, Data Control & Data Deletion

You maintain complete ownership and sovereignty over your financial data at all times:

- **Export Data:** You can export your complete portfolio ledger at any time in machine-readable JSON, CSV (Excel compatible), or printable PDF statements.
- **Backup & Portability:** Backups are stored as plain or encrypted payloads on your device or in your personal storage destination of choice.
- **Instant Complete Data Erasure:** You can permanently delete all local data, cached prices, profiles, and settings by clicking **"Reset All Data"** within the in-app Settings dialog or by clearing the application storage via Android System Settings. Once cleared, the data is permanently erased from the device and cannot be recovered by anyone.

---

## 6. Children's Privacy

Wealth-Meter is not directed to children under the age of 13 (or under 16 in the European Economic Area). We do not knowingly collect or solicit personal information from children.

---

## 7. International Privacy Compliance

- **GDPR (European Union):** Because your personal and financial data remains on your physical hardware, you have inherent right to access, rectify, port, and erase your data at your discretion.
- **CCPA / CPRA (California, USA):** We do not sell, rent, or share personal information or financial data to data brokers or third parties for monetary or commercial consideration.
- **DPDP Act (India):** Wealth-Meter processes information strictly on the data principal's device, with no central cloud storage or cross-border data transfer of personal portfolios.

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect app updates, new regulatory standards, or enhanced features. Any modifications will be posted here with an updated "Last Updated" revision date. We encourage you to review this policy periodically.

---

## 9. Contact Us

If you have any questions, suggestions, or concerns regarding this Privacy Policy or your data privacy in Wealth-Meter, please reach out:

- **Developer:** Samidha Potphode
- **Email:** `samidhapurushottampotphode@gmail.com`
