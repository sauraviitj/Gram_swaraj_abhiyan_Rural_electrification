# 📈 Gram Swaraj Abhiyan: Rural Electrification Performance Tracker – Assam ⚡

This repository presents a performance tracking strategy developed under the **Gram Swaraj Abhiyan** in the state of **Assam**, aimed at accelerating **village saturation** in rural electrification.

---

## 🧾 Project Overview

Under **Phase 1 of the Saubhagya Scheme**, the focus was on electrifying villages with over 50% marginalized communities. While daily household connections were high, we observed poor village saturation.

To address this, we developed a custom **district-wise performance indicator** that balances both:

- The **quantity** of connections, and
- The **quality** of saturation (i.e., number of villages fully electrified)

---

## 📊 Daily Performance Metrics

Each district is monitored using the following daily indicators:

- **Villages Left**
- **Houses Left**
- **Connections Done** (Today)
- **Villages Saturated** (Today)

---

## 📈 Scoring Formula (Custom KPI)

To drive prioritization and track meaningful impact, we define a **custom score**:
Daily Performance indicator(connections done *villages saturated)
Score = Villages Saturated + (0.2 × Connections Done)
