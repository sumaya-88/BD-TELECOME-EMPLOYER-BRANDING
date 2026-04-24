# 📡 BD Telecom Employer Branding — LinkedIn Analysis 2026

> **A structured competitive analysis of LinkedIn employer branding strategies across top telecom companies in Bangladesh — with strategic recommendations for Banglalink.**

---

## 📌 Project Overview

This project was built to demonstrate core competencies in:
- **Digital research & competitive analysis**
- **Social media data collection and structuring**
- **Data visualisation (Python)**
- **Strategic reporting and presentation**

Skills directly relevant to **Banglalink's HR / Employer Branding** function.

---

## 🏢 Companies Analysed

| Company | LinkedIn Followers | Posts/Month | Engagement Rate |
|---|---|---|---|
| Grameenphone | 436,248 | 14 | 3.8% |
| Robi Axiata | 339,596 | 10 | 3.1% |
| **Banglalink** | **~168,000** | **8** | **2.5%** |
| Teletalk | ~12,000 | 2 | 0.8% |

*Data: Q4 2024 – Q1 2026 | Sources: LinkedIn public pages, BTRC, company press releases*

---

## 📁 Project Structure

```
bd_telecom_employer_branding/
│
├── report.html                        ← Full interactive report (open in browser)
├── data_collector.py                  ← Python data collection & visualisation script
├── README.md                          ← This file
│
├── data/
│   ├── bd_telecom_employer_branding.csv      ← Structured dataset (CSV)
│   ├── bd_telecom_employer_branding.xlsx     ← Structured dataset (Excel)
│   └── bd_telecom_employer_branding_full.json ← Full JSON with all attributes
│
└── assets/
    └── linkedin_performance_charts.png       ← 6-panel visualisation dashboard
```

---

## 🚀 How to Run

### 1. View the Report
Simply open `report.html` in any browser — no server needed.

### 2. Run the Data Script

```bash
# Install dependencies
pip install pandas openpyxl matplotlib seaborn

# Run the collector
python data_collector.py
```

This regenerates all data files and charts.

---

## 📊 Key Findings

1. **Flagship programmes drive disproportionate engagement** — GP's Platform SHE and Robi's Datathon generate 2–3× higher engagement than standard posts.
2. **Video content is underpowered** — Even the leader uses video in only 35% of posts, despite LinkedIn's 3× algorithm boost for video.
3. **Bangla language = untapped authenticity** — All operators post predominantly in English despite targeting a Bangladeshi talent pool.
4. **Employee advocacy is highest-ROI** — Employee-shared content gets 5–10× more reach than company page posts.
5. **Consistency beats virality** — GP's steady 14 posts/month is the primary driver of its follower advantage.

---

## 🎯 Top Recommendations for Banglalink

| Priority | Action | Timeline |
|---|---|---|
| 🔴 High | Activate LinkedIn Career Page | Week 1 |
| 🔴 High | Scale to 12–14 posts/month | Month 1–2 |
| 🟡 Medium | Launch "Digitalyst Stories" video series | Month 2–3 |
| 🟡 Medium | Build employee advocacy programme | Month 2–4 |
| 🟢 Strategic | Leverage WWF Green Office as EVP differentiator | Month 3–6 |
| 🟢 Strategic | Introduce bilingual (Bangla + English) content | Month 4–6 |

---

## ⚙️ Technical Notes

### LinkedIn API Limitation
LinkedIn's full analytics API requires:
- OAuth 2.0 credentials
- LinkedIn Marketing Developer Partner (MDP) agreement

The `data_collector.py` script includes a structured dataset based on publicly observable metrics and provides a framework ready to be extended with live API credentials.

### Data Sources
- LinkedIn company pages (public)
- BTRC subscriber data (March 2025)
- The Daily Star, The Business Standard, Prothom Alo
- LeadIQ, ZoomInfo company profiles
- Company Wikipedia pages and press releases

---

## 📐 Methodology

Engagement rates, average likes, comments, and shares are **estimated** from observable public data and LinkedIn industry benchmarks. These figures are directional rather than precise — LinkedIn does not expose post-level analytics publicly without API access.

---

## 🛠 Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Data collection, structuring, export |
| pandas | Data manipulation |
| matplotlib + seaborn | Visualisations |
| HTML / CSS | Interactive report |
| JSON / CSV / XLSX | Data exports |

---

## 📄 License

For educational and professional portfolio use.

---

*Prepared: April 2026 | Dhaka, Bangladesh*
