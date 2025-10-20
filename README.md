# ⚡ Electric Vehicle (EV) Market Analysis

A data-driven analysis of the **EV market** (with a focus on India) to uncover **customer segments, adoption patterns, pricing bands, and regional trends**. The project applies **clustering and analytics** to support strategy for **EV startups** and mobility businesses.

---

## 🔍 Objectives
- Identify **market segments** based on demographics, usage, intent, and budget.  
- Explore **regional adoption** and charging/infrastructure readiness.  
- Quantify **price sensitivity** and the features customers value most.  
- Provide **actionable recommendations** for product, pricing, and go‑to‑market.

---

## 📦 Dataset (Illustrative Schema)
Typical columns used in the analysis:
- `age`, `gender`, `income_band`, `city_tier`, `region`
- `vehicle_type` (2W/3W/4W), `usage_pattern` (daily commute / long trips)
- `budget_in_lakh`, `brand_awareness`, `purchase_intent`
- `charging_access` (home/public), `range_preference_km`, `environmental_concern`
- `ev_experience` (test drive / previous ownership), `purchase_horizon_months`

> Data is cleaned and anonymized for research; synthetic augmentation is used where necessary.

---

## 🧭 Methodology
1. **EDA** – distributions, correlations, outlier handling, missing values.  
2. **Feature Engineering** – one-hot/categorical encoding, scaling, binning of budgets & ranges.  
3. **Clustering** – **K-Means** with silhouette analysis and elbow method to select K.  
4. **Segment Profiling** – demographics, budget, intent, and region for each cluster.  
5. **Insights & Strategy** – pricing bands, key features, and marketing focus.

---

## 🧠 Key Insights (Example)
- **Three–four distinct buyer segments** emerge (e.g., *Value Commuters*, *Mid‑range Family*, *Performance/Range Seekers*).  
- **Budget tiers** around **₹8–12L** and **₹15–20L** show clear intention spikes.  
- **Home charging** availability is a strong predictor of purchase intent; **public fast‑charging** improves adoption in Tier‑1 cities.  
- **Range preference** clusters around **250–350 km** for city usage; long‑range (>400 km) matters to highway users.  
- **Environmental concern + TCO awareness** correlates with higher willingness to switch to EV.

---

## 📊 Visuals (in the notebook)
- Segment distributions (bar/stacked bar)
- Budget & range density plots
- Regional adoption heatmap
- Silhouette scores & elbow curve
- Cluster radar charts for segment profiling

---

## ⚙️ Tech Stack
- Python • Pandas • NumPy • Scikit‑learn • Matplotlib/Seaborn • Plotly

---

## 🚀 Quick Start
```bash
git clone https://github.com/ziaee-mohammad/Electric-Vehicle-Market-Analysis.git
cd Electric-Vehicle-Market-Analysis
pip install -r requirements.txt
jupyter notebook EV_Market_Analysis.ipynb
```

---

## 📌 Deliverables
- `EV_Market_Analysis.ipynb` – full EDA, clustering, and insights
- `/reports/` – figures & summary exports
- `/data/` – (optional) anonymized or synthetic sample

---

## 🧭 Recommendations (for Startups)
- Offer **two trims per price tier** (value & extended‑range).  
- Bundle **home charger**; partner with **public fast‑charging** in Tier‑1.  
- Use **TCO calculators** in marketing to educate price‑sensitive buyers.  
- Localize features (connectivity, safety) by **city tier & segment**.

---

## 🧾 Author
**Mohammad Ziaee** — Data Science & AI Enthusiast  
GitHub: https://github.com/ziaee-mohammad
👉 Instagram: [@ziaee_mohammad](https://www.instagram.com/ziaee_mohammad/)

---

## 🏷️ Tags
`electric-vehicles` • `market-segmentation` • `clustering` • `kmeans` • `data-science` • `business-analytics`
