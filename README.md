<!-- ===================== HEADER ===================== -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:58a6ff&height=210&section=header&text=Wesley%20Haruo&fontSize=50&fontColor=ffffff&fontAlignY=36&desc=Data%20Engineer%20%E2%80%A2%20Data%20Analyst%20%E2%80%A2%20ML%20Builder&descSize=17&descAlignY=57&animation=fadeIn" width="100%" alt="Wesley Haruo" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3500&pause=900&color=1F6FEB&center=true&vCenter=true&width=680&lines=ingest()+%E2%86%92+validate()+%E2%86%92+model()+%E2%86%92+serve()+%E2%86%92+monitor();Fraud+detection+%E2%80%A2+Forecasting+%E2%80%A2+BI+dashboards;I+turn+messy+data+into+decisions+people+act+on." alt="Typing intro" />
</div>

<p align="center">
  <a href="https://linkedin.com/in/Wesleyharuo"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/wesleyharuo?tab=repositories"><img src="https://img.shields.io/badge/All_Repos-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>
  <img src="https://komarev.com/ghpvc/?username=wesleyharuo&color=1f6feb&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile views" />
</p>

<br>

<!-- ===================== ABOUT ===================== -->
<table>
<tr>
<td width="56%" valign="top">

### 👋 Hey, I'm Wesley

I like the part of a data project most people skip: figuring out **what question the business is actually asking**, then building the pipeline, the model, and the one-page summary that answers it.

```python
class Wesley(DataEngineer, DataAnalyst):
    focus    = ["data detection", "forecasting", "BI"]
    ships    = ["pipelines", "models", "APIs", "exec summaries"]
    learning = ["Spark", "Airflow", "dbt", "AWS", "LLMs"]

    def deliver(self, data):
        return self.insight(data) >> "decision"
```

</td>
<td width="44%" valign="top">

### ⚡ Quick facts

- 🔍 **18+ public projects** across analytics, ML and full-stack
- 🛡️ Fraud systems with **drift monitoring** (KS · PSI) and **FINTRAC / PIPEDA**-aware design
- 🧪 Experiment tracking with **MLflow**, tuning with **Optuna**
- 📊 Every analysis ships with an **executive summary**, not just charts
- 🚀 Live on Vercel: [AI Hub](https://ai-hub-nine-kappa.vercel.app) · [Cop](https://cop-three.vercel.app)

</td>
</tr>
</table>

<!-- ===================== HOW I BUILD ===================== -->
## 🏗️ How I build data products

```mermaid
flowchart LR
    A[("Raw sources<br/>CSV · APIs · POS · DBs")] --> B["Ingest<br/>ETL · SQL"]
    B --> C["Validate<br/>schema · nulls · dupes"]
    C --> D["Transform<br/>Pandas · feature eng."]
    D --> E{"Goal?"}
    E -->|explain| F["BI & dashboards<br/>Plotly · Streamlit"]
    E -->|predict| G["ML models<br/>XGBoost · LightGBM"]
    G --> H["Serve<br/>FastAPI · Flask · Docker"]
    H --> I["Monitor<br/>drift · KS · PSI"]
    I -.->|retrain| D
    F --> J["Executive summary"]
    H --> J
```

<!-- ===================== STACK ===================== -->
## 🧰 Stack by layer

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,js,react,nextjs,nodejs,flask,fastapi,tailwind,postgres,mongodb,redis,docker,githubactions,vercel,sklearn,tensorflow&theme=dark&perline=9" alt="Tech stack icons" />
</p>

| Layer | Tools |
|---|---|
| **Ingestion & ETL** | ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) |
| **Storage** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) |
| **Modeling** | ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-EB5E28?style=flat-square) ![LightGBM](https://img.shields.io/badge/LightGBM-2E7D32?style=flat-square) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Prophet](https://img.shields.io/badge/Prophet-4285F4?style=flat-square) |
| **MLOps** | ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![Optuna](https://img.shields.io/badge/Optuna-1F3B73?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **Serving & APIs** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) |
| **Visualization & BI** | ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square) |
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) |
| **Leveling up** | ![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) |

<!-- ===================== FLAGSHIP: CARDGUARD ===================== -->
## 🛡️ Flagship — [CardGuard](https://github.com/wesleyharuo/CardGuard-) · Credit Card Fraud Detection

<!-- TODO: add your real metrics here, e.g.
![PR-AUC](https://img.shields.io/badge/PR--AUC-0.00-success?style=flat-square)
![Recall](https://img.shields.io/badge/Recall%40FPR1%25-0.00-success?style=flat-square)
-->
<!-- TODO: add a chart, e.g. <img src="https://raw.githubusercontent.com/wesleyharuo/CardGuard-/main/reports/pr_curve.png" width="48%"> -->

```mermaid
flowchart LR
    A[("Card transactions")] --> B["Feature engineering"]
    B --> C{"Class imbalance<br/>strategy"}
    C -->|undersampling| D["LightGBM"]
    C -->|class weights| E["XGBoost"]
    D --> F["Optuna<br/>hyperparameter search"]
    E --> F
    F --> G["MLflow<br/>runs · params · artifacts"]
    G --> H["Evaluation<br/>ROC-AUC · PR-AUC"]
    H --> I["CLI inference<br/>Dockerized"]
    I --> J["Drift monitor<br/>KS · PSI"]
    J -.->|retrain trigger| B
```

| Engineering decision | Why |
|---|---|
| **PR-AUC as primary metric** | Fraud is a tiny minority class; ROC-AUC can look excellent even when the model misses most fraud. PR-AUC exposes that. |
| **Undersampling vs. class weighting, both tested** | Each trades off differently between recall and false alarms, so they're benchmarked instead of assumed. |
| **KS + PSI drift checks** | Fraud patterns change. These flag when production data stops looking like training data, before accuracy silently degrades. |
| **Modular `data → features → models → evaluation`** | Each stage is swappable and testable on its own, the way it would live in production. |

<!-- ===================== RISK & INSURANCE AI ===================== -->
## 🧠 Risk & Insurance AI

<table>
<tr>
<td width="50%" valign="top">

### [KW Risk](https://github.com/wesleyharuo/KW_Risk)
Insurance claims intake, triage and fraud screening.

```mermaid
flowchart TD
    U["Claim + documents"] --> FE["React · Vite<br/>(Vercel)"]
    FE --> API["FastAPI · Uvicorn"]
    API --> OCR["OCR extraction"]
    OCR --> NLP["NLP triage"]
    NLP --> R["Rule engine"]
    NLP --> M["ML fraud model"]
    R --> S["Risk score"]
    M --> S
    S --> D["Live ops dashboard"]
```

**Hybrid scoring:** rules catch known patterns and stay explainable; ML catches what rules miss.

</td>
<td width="50%" valign="top">

### [AI Fraud Detection Canada](https://github.com/wesleyharuo/AI-Fraud-Detection-Canada)
Fraud platform designed around Canadian financial regulation.

```mermaid
flowchart TD
    I["Transaction ingestion"] --> F["Feature service"]
    F --> M["Neural net + ensemble"]
    M --> D["Decision engine"]
    D --> A["Monitoring & alerting"]
    D --> C["Compliance layer<br/>FINTRAC · PIPEDA"]
```

**Microservices**, so models, decisioning and alerting scale and deploy independently.

</td>
</tr>
<tr>
<td colspan="2">

### [Insurance Premium ML](https://github.com/wesleyharuo/Data_insurance_IA_ML_Insurance)

```mermaid
flowchart LR
    S["Public + external<br/>insurance data"] --> P["Cleaning &<br/>feature eng."]
    P --> T["Random Forest · Gradient Boosting · Neural Net"]
    T --> API["Flask REST API<br/>real-time quotes"]
    API --> UI["JS frontend"]
    API --> L["Prediction logs"]
    L -.->|retraining loop| T
```

</td>
</tr>
</table>

<!-- ===================== ANALYTICS ===================== -->
## 📊 Analytics & Business Intelligence

<table>
<tr>
<td width="33%" valign="top" align="center">

#### [☕ Maple Cafe Sales](https://github.com/wesleyharuo/maple-cafe-sales)
<img src="https://img.shields.io/badge/46,000+-transactions-1f6feb?style=for-the-badge" />

3 locations · full year 2024<br/>
Revenue by hour × location × category → staffing & menu decisions

</td>
<td width="33%" valign="top" align="center">

#### [🏔️ Maple Outfitters](https://github.com/wesleyharuo/maple-outfitters)
<img src="https://img.shields.io/badge/9,800+-orders-1f6feb?style=for-the-badge" />

5 sales channels<br/>
Retention, returns & discount impact → multi-channel strategy

</td>
<td width="33%" valign="top" align="center">

#### [🏙️ GTA Rental Market](https://github.com/wesleyharuo/gta-rental-market)
<img src="https://img.shields.io/badge/5,400+-listings-1f6feb?style=for-the-badge" />

10 neighborhoods<br/>
Pricing gaps, vacancy & absorption → investment signals

</td>
</tr>
<tr>
<td width="33%" valign="top" align="center">

#### [📈 Predicta Suite](https://github.com/wesleyharuo/Predicta_Suite)
Prophet **vs** ARIMA **vs** scikit-learn<br/>
Automated benchmarking for seasonal forecasting

</td>
<td width="33%" valign="top" align="center">

#### [⚙️ Process Improvement Platform](https://github.com/wesleyharuo/Process-Improvement-Data-Analytics-Platform)
Streamlit + SQL dashboards<br/>
Retail · supply chain · customer support

</td>
<td width="33%" valign="top" align="center">

#### [📐 Calc Vector](https://github.com/wesleyharuo/Calc_Vector)
NumPy · SciPy · Plotly<br/>
Live 2D/3D vector math in Streamlit

</td>
</tr>
</table>

<!-- ===================== PRODUCTS ===================== -->
## 🌐 Products & Platforms

<table>
<tr>
<td width="58%" valign="top">

### [Resume Evaluator SaaS](https://github.com/wesleyharuo/Aplicaton-new)
Multi-tenant platform that scores resumes against versioned rubrics.

```mermaid
flowchart LR
    C["Tenant A / Tenant B"] --> AU["Auth + RBAC"]
    AU --> API["Serverless API"]
    API --> DB[("Prisma ORM<br/>tenant-scoped data")]
    API --> Q["Upstash Redis queue"]
    Q --> W["Async scoring worker"]
    W --> R["Rubric v1 … vN"]
    W --> DB
```

**Why a queue:** scoring is slow and bursty, so requests return instantly and workers absorb the load.

</td>
<td width="42%" valign="top">

### 🚀 Live demos

<a href="https://ai-hub-nine-kappa.vercel.app"><img src="https://img.shields.io/badge/AI_Hub-Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a><br/>
<sub>Interactive AI tools & data viz hub</sub>

<a href="https://cop-three.vercel.app"><img src="https://img.shields.io/badge/Cop_Copilot-Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a><br/>
<sub>Multi-model chat copilot via OpenRouter</sub>

<br/>

**Also built:** [DigitalMenuHub](https://github.com/wesleyharuo/DigitalMenuHub) (QR menus + analytics) · [Lex](https://github.com/wesleyharuo/lex) (PHP + PostgreSQL file server) · [QuickStats Web](https://github.com/wesleyharuo/QuickStats-Web) · [Model Dig MKT](https://github.com/wesleyharuo/Model_Dig_MKT)

</td>
</tr>
</table>

<details>
<summary><b>🗂️ Every project at a glance (18)</b></summary>
<br>

| Project | What it is | Stack |
|---|---|---|
| [CardGuard](https://github.com/wesleyharuo/CardGuard-) | Card fraud detection | Python · LightGBM · Docker |
| [AI Fraud Detection Canada](https://github.com/wesleyharuo/AI-Fraud-Detection-Canada) | Compliance-aware fraud platform | Python |
| [KW Risk](https://github.com/wesleyharuo/KW_Risk) | Insurance claims AI | React · FastAPI |
| [Insurance ML](https://github.com/wesleyharuo/Data_insurance_IA_ML_Insurance) | Premium prediction API | Python · Flask |
| [Maple Cafe Sales](https://github.com/wesleyharuo/maple-cafe-sales) | POS sales analysis | Python |
| [Maple Outfitters](https://github.com/wesleyharuo/maple-outfitters) | E-commerce analytics | Python |
| [GTA Rental Market](https://github.com/wesleyharuo/gta-rental-market) | Real-estate market analysis | Python |
| [Predicta Suite](https://github.com/wesleyharuo/Predicta_Suite) | Sales forecasting | Prophet · ARIMA |
| [Process Improvement Platform](https://github.com/wesleyharuo/Process-Improvement-Data-Analytics-Platform) | Ops dashboards | Streamlit |
| [Model Dig MKT](https://github.com/wesleyharuo/Model_Dig_MKT) | Marketing analytics | Python · Flask |
| [QuickStats Web](https://github.com/wesleyharuo/QuickStats-Web) | Browser stats tool | HTML · JS |
| [Resume Evaluator SaaS](https://github.com/wesleyharuo/Aplicaton-new) | Multi-tenant SaaS | TypeScript |
| [AI Hub](https://github.com/wesleyharuo/AI-hub) | AI dashboard | HTML · Vercel |
| [Cop](https://github.com/wesleyharuo/cop) | AI copilot | OpenRouter · Vercel |
| [DigitalMenuHub](https://github.com/wesleyharuo/DigitalMenuHub) | QR restaurant menus | HTML · JS |
| [Lex](https://github.com/wesleyharuo/lex) | File server | PHP · PostgreSQL |
| [Process Improvement Web](https://github.com/wesleyharuo/Process-Improvemen) | Platform landing page | HTML |
| [Calc Vector](https://github.com/wesleyharuo/Calc_Vector) | Vector math app | Streamlit |

</details>

<!-- ===================== STATS (auto light/dark) ===================== -->
## 📈 GitHub Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=wesleyharuo&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" />
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=wesleyharuo&show_icons=true&theme=default&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=wesleyharuo&layout=compact&theme=github_dark&hide_border=true&langs_count=6" />
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=wesleyharuo&layout=compact&theme=default&hide_border=true&langs_count=6" alt="Top languages" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=wesleyharuo&theme=github-dark-blue&hide_border=true" />
    <img src="https://streak-stats.demolab.com?user=wesleyharuo&theme=default&hide_border=true" alt="Contribution streak" />
  </picture>
</p>

<!-- ===================== FOOTER ===================== -->
<div align="center">

### 🤝 Let's build something useful

Working on fraud, forecasting, or a dashboard nobody reads yet? I'd like to hear about it.

<a href="https://linkedin.com/in/Wesleyharuo"><img src="https://img.shields.io/badge/Say_hi_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

<sub>⭐ If a repo helped you, a star genuinely makes my day.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58a6ff,100:1f6feb&height=110&section=footer" width="100%" />

</div>
