# Aboitiz Foods — MCOS & P&L Financial Stress Test & Budget 2027 Dashboard

Executive Leadership Presentation Dashboard built with **Streamlit** and **Plotly** for multi-year financial performance, cost of sales (COGS), standard absorption manufacturing cost of sales (MCOS), 8-Month YTD Actuals tracking, and variance analysis across business entities.

---

## 🌟 Key Highlights & Scenarios
- **Complete Multi-Year Scenarios & Benchmarks**:
  - **2026 Actual (8M YTD Jan–Aug 2026)**: Extracted directly from `08.2026 Stress Test_PL_Monthly_MCOS.xlsx`
  - **2026 Budget (8M YTD Benchmark)**
  - **2025 Actual (8M YoY Benchmark)**
  - **2024 Actual** (Full Year Baseline)
  - **2025 Actual (Y-1 Full Year)**
  - **2026 Budget** (Full Year)
  - **2026 LTF (8+4 Latest Forecast)**
  - **2027 Budget Target**
- **Core Financial Accounts**:
  - **Volumes (MT)**: Total Feed, Commercial Trading (CT), Day-old chicks (DOC)
  - **Revenue**: Gross Sales, Concessions, Net Sales (TP, RC, IC)
  - **Raw Material COS**: Material costs, Purchase price variances, Stock adjustments
  - **MCOS Variable Costs (VC)**: Labour, Utilities, Fuel & Electricity, Delivery, Production supplies
  - **MCOS Fixed Costs (FC)**: Salaries, Social benefits, Maintenance, Rent, Insurance, Professional fees
  - **Depreciation**: PPE (Buildings, Machinery & Equipment, Motor Vehicles, Computers, ERP) & ROU Assets
  - **Headcount**: Technical, Operations, Sales, Support, Total Head Count
- **Business Entities Covered**:
  - **Vietnam**: Total Vietnam, GCFD, GCFLA, AFC, GCFHN, Binh Duong
  - **China**: Total China, GCDG, GCZZ, GCZJ, GCZH, GCKM, GCMS
  - **Indonesia**: Total Indonesia, GCGX, GCYN, GCI (Total entity)
  - **Malaysia**: Total Msia, GCFM, GCS, GCFS, BFF, GLS
  - **Sri Lanka**: Sri Lanka, KGT
  - **Shrimp & Others**: DASH, GCSI, GCTI, GCSSB

---

## 🚀 How to Run Locally

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Launch Streamlit
```bash
streamlit run app.py
```
Then open your browser at `http://localhost:8501`.

---

## ☁️ Deploy to Streamlit Community Cloud
1. Repo is live at: `https://github.com/vananh-phamthi/Mcos`
2. Go to [share.streamlit.io](https://share.streamlit.io/).
3. Select repository `vananh-phamthi/Mcos` and branch `main`.
4. Set Main file path: `app.py`.
5. Click **Deploy!**

---
*Created for Aboitiz Foods Executive Presentation | Currency: USD '000 | Data Sources: `08.2026 Stress Test_PL_Monthly_MCOS.xlsx` & `2026LTF8+4 vs 2027B Stress Test_PL_Monthly_MCOS.xlsx`*
