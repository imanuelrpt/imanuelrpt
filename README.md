<div align="center">

# Imanuel Rodericus Parlindungan Tempo

**Data Analyst** — Python · SQL · Statistics

Bekasi, Indonesia · Open to remote / Full-time

[![Email](https://img.shields.io/badge/Email-imanuelrpt13@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:imanuelrpt13@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-imanuelrpt-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/imanueltempo/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Tokopedia%20Analysis-1F6FEB?style=flat-square&logo=github&logoColor=white)](https://github.com/imanuelrpt/indonesia-ecommerce-behavior-analysis)

</div>

---

### Messy data in, defensible decisions out.

I'm a data analyst with a computer science background. I take public and official datasets — e-commerce listings, BPS statistics, air-quality readings — and turn them into answers a business can actually act on.

What I care about is **method, not decoration**: state the question, choose the test, check the assumption, report the effect size. A pretty chart that hides a biased sample is worse than no chart.

- 🔍 **Analysis you can audit** — median over mean when data is skewed, Spearman for rank data, effect size next to every p-value.
- 🧹 **Honest cleaning** — missing values documented, not imputed away; every dropped row has a stated reason.
- 🗄️ **SQL-first logic** — CTEs, window functions, RFM and cohorts live in SQL; Python draws the picture.
- 🚀 **End-to-end ownership** — from raw download to a notebook someone else can re-run.

---

## Featured analytics work

| Project | Question it answers | Stack | Headline result |
|---|---|---|---|
| **[Tokopedia E-commerce Behavior](https://github.com/imanuelrpt/indonesia-ecommerce-behavior-analysis)** ⭐ | Do discounts and ratings actually drive sales? | Python · pandas · SciPy · Google Trends | Median **35** units sold vs mean **7,896** (226×) — used median + log scale. Discount ↔ sales correlation is a **selection effect**: ρ = **+0.50** overall, but **−0.07** *within* discounted products. |
| **[Olist E-commerce Analytics](https://github.com/imanuelrpt/olist-ecommerce-analytics)** | Why does revenue growth feel fragile? | MySQL · CTE · window functions · RFM | **96,470** delivered orders, **3.00%** repeat-purchase rate, **8.11%** late deliveries. Late orders average **2.57★** vs **4.29★** on time. |
| **[Poverty & Unemployment in Indonesia](https://github.com/imanuelrpt/indonesia-poverty-unemployment-analysis)** | Are poverty and unemployment the same problem? | Python · BPS data · PCA + K-Means | National poverty **9.78% → 8.47%** (2020–2025), yet provinces span **3.72% to 30.03%** (8.1×). Poverty–unemployment correlation is **negative** (r = **−0.20**). |
| **[Indonesia Air Quality](https://github.com/imanuelrpt/indonesia-air-quality-analysis)** | Is air in Indonesia getting better, and where is it worst? | Python · IKU/IKLH · ISPU daily | National IKU **88.27 → 91.33** (2020–2024), but Banten (**69.84**) vs South Kalimantan (**96.41**). Density vs IKU: r = **−0.67**. PM2.5 is the critical pollutant on **86%** of Jakarta days. |
| **[Heart Disease Prediction](https://github.com/imanuelrpt/heart-disease-prediction)** | Can risk be flagged without missing sick patients? | scikit-learn · 6 models · 5-fold CV | Tuned Random Forest on held-out data: **recall 0.929**, ROC-AUC **0.952** — optimised for recall because a false negative costs more than a false positive. |

## Engineering & AI

| Project | What it is | Stack |
|---|---|---|
| **[SIPALA](https://github.com/imanuelrpt/SIPALA)** | Public complaint channel: anonymous reports with map pins and photo evidence, ticket-based tracking without an account, role-based dashboards for agencies | PHP · MySQL · Bootstrap |
| **[kosKu](https://github.com/imanuelrpt/kosKu-website)** | Boarding-house management: rooms, tenants, leases, monthly billing, instalment payments, P&L reports | CodeIgniter 4 · PHP 8 · Chart.js |
| **[ARC-AGI-3 Heuristic Explorer](https://github.com/imanuelrpt/ARC-AGI-3-Heuristic-Explorer-Agent)** | Agent that learns unseen 64×64 grid games from screen changes only — plus a fully offline test rig | Python · Jupyter · Kaggle |

---

## Toolbox

| Layer | Tools I use daily |
|---|---|
| **Language** | Python (pandas, NumPy, SciPy, scikit-learn), SQL, PHP |
| **Analysis** | EDA, hypothesis testing (Mann-Whitney, Kruskal-Wallis), effect size (Cliff's delta), correlation, cohort & RFM analysis, clustering |
| **Visualisation** | Looker Studio |
| **Data** | MySQL, PostgreSQL, CSV pipelines, notebook reproducibility |
| **Workflow** | Jupyter/Colab, Git & GitHub, AI-assisted development (Cursor, Claude Code) with manual diff review |

---

## How I work

1. **Write the question before the query.** A vague question produces a confident wrong answer.
2. **Check the distribution first.** Means lie on skewed data; medians and log scales don't.
3. **Correlation is a clue, not a conclusion.** When discount correlates with sales, the next question is *who chose to discount what*.
4. **Document the bias you cannot fix.** "798 rows had no sales figure, so they were excluded from sales analysis" beats a silent fillna.

---

## Currently

- 📚 Going deeper on **raw SQL & PostgreSQL** — indexes, `EXPLAIN ANALYZE`, row-level security.
- 🛠️ Building small **FastAPI + Next.js** apps to bridge analysis into product.
- 🤖 Exploring **LLM/OCR pipelines** for document-heavy data work.

---

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=imanuelrpt&show_icons=true&hide_border=true&count_private=false&include_all_commits=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=imanuelrpt&layout=compact&hide_border=true&langs_count=8)

**Open to Data Analyst / Analytics Engineer roles — remote or Jakarta/Bekasi area.**
Reach me at [imanuelrpt13@gmail.com](mailto:imanuelrpt13@gmail.com).

</div>
