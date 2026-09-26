# FastSpring Payment Gateway Module for WHMCS 8.10.1

[![PHP 8.1](https://img.shields.io/badge/PHP-8.1-blue.svg)](https://www.php.net/)
[![WHMCS Compatibility](https://img.shields.io/badge/WHMCS-8.10.1-green.svg)](https://www.whmcs.com/)
[![FastSpring API](https://img.shields.io/badge/FastSpring-API-orange.svg)](https://developer.fastspring.com/)
[![License:GPL-3.0](https://img.shields.io/badge/License-gpl3.0%20license-purple.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)

A complete, production-ready FastSpring payment gateway module engineered for **WHMCS 8.10.1** running on **PHP 8.1**.

The module integrates seamlessly with the official FastSpring REST API and Hosted Storefronts, supporting one-time payments, recurring subscriptions, automated webhook synchronization with HMAC-SHA256 signature verification, idempotency deduplication, client & admin subscription controls, automated termination cancellation, upgrade/downgrade synchronization, and refund reconciliation.

---

## 1. System Requirements

* **WHMCS Version:** 8.10.1 (or 8.x compatible)
* **PHP Version:** 8.1 (uses strict typing, match expressions, and native cURL)
* **PHP Extensions:** `curl`, `json`, `openssl`, `hash`, `mbstring`
* **FastSpring Account:** Live and/or Sandbox account with API and Webhook access.

---
