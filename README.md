# AfriArt Marketplace 🌍

**Connecting African artisans with local buyers & the world.**

![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20Android-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-MVP-orange)

## Overview

AfriArt is a hybrid mobile marketplace designed to sell authentic African artefacts (masks, statues, textiles, jewelry, tools) to **both local African users** and **international buyers** — solving the problem that most platforms serve only one audience poorly.

### The Problem We Solve
- Locals struggle to find verified artefacts and pay with mobile money.
- Foreigners face shipping uncertainty, fake products, and no cultural authentication.

### Our Solution
- **Local mode**: Mobile money payments, local courier, COD option, regional languages.
- **Foreign mode**: Credit card, international shipping + duty estimator, authenticity badges, escrow protection.

---

## Key Features

| Feature | Local | International |
|---------|-------|----------------|
| Currency | GHS, NGN, KES, ZAR, XAF | USD, EUR, GBP |
| Payment | M-Pesa, MoMo, Airtel Money, COD | Stripe, PayPal, Credit Card |
| Shipping | Local courier, pickup points | DHL/FedEx + customs docs |
| Authentication | Phone number / National ID | Passport / Escrow |
| Map view | Find nearby artefacts | ❌ |

### Common Features (Both Modes)
- Artefact listing with origin tribe, age, material, certification
- Seller verification & reviews
- Order tracking (real-time)
- Dispute resolution
- WhatsApp sharing

---

## Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | Flutter (iOS + Android) |
| Backend | Node.js + Express |
| Database | PostgreSQL, Redis |
| Payments (Local) | Paystack, Flutterwave |
| Payments (Global) | Stripe, PayPal |
| Shipping APIs | Sendy, DHL, FedEx |
| Hosting | AWS (Cape Town region) |

---

## Project Structure

