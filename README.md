# 💎 Frqtal Links | Integration Reference Guide

Welcome to the official integration blueprints for **Frqtal Links**. This directory serves as a high-level reference for developers looking to implement secure, dynamic payment checkouts within their own ecosystems.

---

## ⚡ Overview

This collection is designed to demonstrate best practices when consuming the Frqtal Links API. Instead of providing a rigid implementation, we offer a variety of **technical blueprints** that can be adapted to your specific architecture, whether you are building a modern SPA or a traditional server-side application.

### Supported Blueprints
- ⚛️ **React**: Advanced integration using isolated sandboxing for Single Page Applications.
- 🟢 **Node.js**: Clean backend implementations using native HTTP and Fetch modules.
- 🐘 **PHP**: Classic server-side patterns using cURL for reliable payment generation.
- 🐍 **Python**: Minimalist logic utilizing standard libraries for streamlined processing.

---

## 🛡️ Security & Best Practices

Integrating a payment system requires a deep focus on security. These examples are strictly for **reference purposes** and demonstrate the core logic of our API. When moving to a production environment, please ensure:

> [!IMPORTANT]
> **Token Safety**: API Tokens should never be exposed on the client side (browser). Always process payment requests through your own secure backend.

> [!CAUTION]
> **Sanitization**: Ensure you validate and sanitize all data coming from your users before forwarding it to the Frqtal ecosystem.

---

## 🚀 Getting Started

Each directory contains a self-contained example intended to show the "minimal path" to a successful integration. We recommend exploring the source code of the technology that best matches your stack to understand how to:

1.  Sign payment requests from a secure backend.
2.  Inject the dynamic Checkout HTML into your frontend.
3.  Handle lifecycle events and payment confirmations.

---

*© 2026 Frqtal Links - Empowering seamless payment experiences.*
