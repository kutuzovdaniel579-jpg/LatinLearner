# VIÆ — Powered by FoL
*A modern multilingual vocabulary platform built on structure, clarity, and Latin roots.*

**VIÆ** (pronounced *VIAE*, using the classical **Æ** ligature) is an open, modular learning platform focused primarily on **Latin**, with structured support for **English, French, Dutch, and Russian**.  
The project is developed under **FoL — OpenFluxLab**, emphasizing clean data design, consistency, and developer-friendly formats.

---

## 🌐 Overview
VIÆ provides a lightweight JSON-based vocabulary engine designed for:

- language learners  
- developers building language tools  
- educational platforms  
- automated quiz or lookup systems  

Every vocabulary entry follows a strict, unified schema, making the dataset predictable, scalable, and easy to integrate.

---

## 📚 Supported Languages
- Latin (primary)
- English
- French
- Dutch
- Russian

---

## 🧩 Data Structure

```json
{
  "word": {
    "NL": "Dutch meaning",
    "LA": "Latin form",
    "Gen": "Genitive / grammar info",
    "Tel": "Roman numeral (optional)"
  }
}
