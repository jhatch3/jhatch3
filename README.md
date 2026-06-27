<!-- Repo name must match your GitHub handle. Replace YOUR-USERNAME below (5 spots). -->

<div align="center">

# Justin Hatch
**ML & AI Engineer** · I ship production agent systems
CS @ University of Oregon · Grad Jun 2026 · Eugene, OR

[![Portfolio](https://img.shields.io/badge/Portfolio-CC785C?style=flat-square&logo=vercel&logoColor=white)](https://justin-portfolio-v1-git-main-jhatch3s-projects.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/justinhatch/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jjhatch03@gmail.com)

</div>

---

### About

Senior CS student specializing in Machine Learning, AI, and Data Science. I work across the stack — relational schema design and ETL pipelines, model training and evaluation, and production agent tooling. Most interested in problems where modeling, infrastructure, and product intersect, and in systems that stay correct, observable, and readable six months later.

> **Currently:** AI Engineer (contract) on AWS Bedrock · Applied AI Fellow @ Machine & Minds · building production agent tooling.

---

### Stack

| | |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/-TS-3178C6?style=flat-square&logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Node.js](https://img.shields.io/badge/-Node-339933?style=flat-square&logo=nodedotjs&logoColor=white) |
| **AI / LLM Ops** | ![Claude](https://img.shields.io/badge/-Claude-CC785C?style=flat-square&logo=anthropic&logoColor=white) ![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square) ![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square) ![RAG](https://img.shields.io/badge/-RAG-4B8BBE?style=flat-square) ![MCP](https://img.shields.io/badge/-MCP-000000?style=flat-square) ![Vector DBs](https://img.shields.io/badge/-Vector%20DBs-4B8BBE?style=flat-square) |
| **ML / Data Sci** | ![XGBoost](https://img.shields.io/badge/-XGBoost-EB6C2D?style=flat-square) ![SHAP](https://img.shields.io/badge/-SHAP-0094C6?style=flat-square) ![scikit-learn](https://img.shields.io/badge/-sklearn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![MLflow](https://img.shields.io/badge/-MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) |
| **Backend / Infra** | ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Pydantic](https://img.shields.io/badge/-Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white) ![Postgres](https://img.shields.io/badge/-Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Dagster](https://img.shields.io/badge/-Dagster-654FF0?style=flat-square&logo=dagster&logoColor=white) ![dbt](https://img.shields.io/badge/-dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) |

---

### Experience

| Role | Org | Focus |
|---|---|---|
| AI Engineer (Contract) | Stealth Startup | Agent orchestration harness on AWS Bedrock + Claude for a multi-tenant SaaS platform |
| Applied AI Fellow | Machine & Minds | Applied AI systems built for measurable P&L impact |
| AI Engineer Intern | Modern Amenities | FastAPI Claude sales chatbot, 900+ users, structured tool-use outputs |
| Lead Software Engineer | Oregon Blockchain Group | TrialWeave (HIPAA RWE) & Crop Share, led teams of 3-5 |


---

### Featured work

**Evergreen Capital — AI-Governed On-Chain Prediction Fund** · `Gemini` `FastAPI` `TypeScript`
A 5-agent research desk (Quant, Macro, Skeptic, Data Miner, Trader) that independently researches, debates via structured cross-examination, and produces weighted consensus votes — triggering autonomous Polymarket trades with no human in the loop. Built full-stack MVP in 24 hours; 1st place hack-a-thon.

**Churn Prediction + LLM Retention Email Pipeline** · `XGBoost` `TreeSHAP` `Dagster` `dbt` `MLflow` `Claude` `Postgres`
Nightly churn-to-retention pipeline scoring 18,618 customers at 0.79 ROC-AUC. XGBoost + TreeSHAP attributions are persisted as structured prompt input for Claude-generated retention emails, each grounded in live order and review history via read-only Postgres tools. An LLM-as-judge eval with enum-typed verdicts surfaced real generator bugs (wrong CTA intent, prohibited offers, tone mismatch).

**Market Data Pipeline + AI News Synthesis** · `FastAPI` `Supabase` `AWS` `Dagster` `LangChain`
Postgres medallion schema (Bronze to Silver to Gold to AI) keyed by (ticker, interval, timestamp) over 4.5M+ rows / 230+ tickers, with conflict-aware upserts and 100% idempotent reruns. A scheduled LangChain agent synthesizes market context, news, and reports into source-attributed summaries powering downstream RAG.

---
