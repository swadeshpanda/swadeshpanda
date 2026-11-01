<a id="top"></a>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A7EA4,50:8A63D2,100:FF694B&height=190&section=header&text=Swadesh%20Ranjan%20Panda&fontColor=ffffff&fontSize=44&fontAlignY=38&desc=Data%20%26%20Analytics%20Engineer%20%C2%B7%20Berlin&descAlignY=60&descSize=20" alt="Swadesh Ranjan Panda banner" width="100%">

<a href="https://github.com/swadeshpanda">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=0A7EA4&center=true&vCenter=true&width=720&lines=Turning+raw+data+into+trusted+insights;Building+tested+dbt+models+on+Databricks;Analytics+Engineer+%C2%B7+Berlin+%F0%9F%87%A9%F0%9F%87%AA;Open+to+full-time+roles" alt="Typing animation">
</a>

*I turn messy raw data into tested, documented models and dashboards that people can trust.*

**[🧑‍💻 About](#about) · [🧰 Stack](#stack) · [🗺️ How I work](#how) · [⭐ Project](#project) · [🎯 Focus](#focus) · [📊 Stats](#stats) · [📬 Contact](#contact)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-swadeshrp-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/swadeshrp/)
[![Email](https://img.shields.io/badge/Email-swadeshpanda95%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:swadeshpanda95@gmail.com)
[![Featured project](https://img.shields.io/badge/Featured%20project-dbt%20%2B%20Databricks-FF694B?style=for-the-badge&logo=dbt&logoColor=white)](https://github.com/swadeshpanda/Thelook-ecommerce-dbt-databricks)

![Status](https://img.shields.io/badge/status-open%20to%20full--time%20roles-2ea44f?style=flat-square)
![Location](https://img.shields.io/badge/based%20in-Berlin-0a7ea4?style=flat-square)
![Focus](https://img.shields.io/badge/focus-data%20engineering%20%C2%B7%20analytics%20engineering-8a63d2?style=flat-square)

</div>

---

<a id="about"></a>

## 🧑‍💻 About me

- 💼 **Working Student, Analytics Engineer at Kleinanzeigen** (Berlin)
- 🎓 **M.Sc. International Project Management & Data Science** at HTW Berlin
- 🛠️ I build the layer between raw data and decisions: **ingestion → modelling → testing → dashboards**
- 🔍 I care about **trusted numbers**: clear grain, one definition per metric, automated data tests, documented models
- 📬 **Open to full-time roles** in data engineering and analytics engineering

---

<a id="stack"></a>

## 🧰 Tech stack

**Languages & query**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Jinja](https://img.shields.io/badge/Jinja-B41717?style=for-the-badge&logo=jinja&logoColor=white)

**Transformation & orchestration**

![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)

**Cloud**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

**BI & AI tools**

![Looker](https://img.shields.io/badge/Looker-4285F4?style=for-the-badge&logo=looker&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Git](https://img.shields.io/badge/Git%20%2B%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

<a id="how"></a>

## 🗺️ How I work

```mermaid
flowchart LR
    A["📥 Raw data<br/>CSV, APIs, cloud storage"] --> B["🧊 Land in the warehouse<br/>Azure / AWS / Databricks"]
    B --> C["🧹 Clean<br/>staging models"]
    C --> D["⭐ Model<br/>facts, dimensions, KPIs"]
    D --> E["✅ Test and document<br/>dbt tests + docs"]
    E --> F["📊 Serve<br/>Looker / AI-BI dashboards"]
    G["⏱️ Orchestrate<br/>Airflow"] -.-> B
    G -.-> C
    G -.-> D

    classDef raw fill:#FFF3CD,stroke:#E0A800,color:#5c4400,stroke-width:2px
    classDef load fill:#D6EAF8,stroke:#2E86C1,color:#10375c,stroke-width:2px
    classDef stg fill:#D5F5E3,stroke:#27AE60,color:#0b3d1f,stroke-width:2px
    classDef mart fill:#FDEBD0,stroke:#E67E22,color:#5a2d00,stroke-width:2px
    classDef qa fill:#E8DAEF,stroke:#8E44AD,color:#33104a,stroke-width:2px
    classDef out fill:#FADBD8,stroke:#E74C3C,color:#5a1008,stroke-width:3px
    classDef orch fill:#EAECEE,stroke:#566573,color:#1c2833,stroke-width:2px
    class A raw
    class B load
    class C stg
    class D mart
    class E qa
    class F out
    class G orch
```

---

<a id="project"></a>

## ⭐ Featured project

<div align="center">

### 🛍️ [TheLook E-Commerce Analytics: dbt + Databricks](https://github.com/swadeshpanda/Thelook-ecommerce-dbt-databricks)

*End-to-end analytics engineering: raw CSVs → tested star schema → live AI/BI dashboard*

![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Jinja](https://img.shields.io/badge/Jinja-B41717?style=flat-square&logo=jinja&logoColor=white)

<a href="https://github.com/swadeshpanda/Thelook-ecommerce-dbt-databricks">
  <img src="https://raw.githubusercontent.com/swadeshpanda/Thelook-ecommerce-dbt-databricks/main/docs/images/dashboard.png" alt="TheLook Sales Dashboard" width="760">
</a>

</div>

| 📈 Result | |
|---|---|
| **Revenue** | $8.13M from valid orders |
| **Average order value** | $86.38 |
| **Repeat customers** | 30.9% of customers who ordered came back |
| **Raw data** | 2.8M+ rows across 7 tables |

<details>
<summary><b>🔎 What I built (click to expand)</b></summary>

<br>

- 🧹 **7 staging views** with renamed keys, `DECIMAL` money and PII removed
- 🔗 **Intermediate layer** joining each sale to the real unit cost from inventory
- ⭐ **Star schema**: `fct_order_items`, `fct_orders`, `dim_customers`, `dim_products`
- 📊 **KPI marts** for finance (`mart_monthly_sales`) and merchandising (`mart_category_performance`)
- ✅ **Data tests** on keys, relationships and accepted values, plus a business-rule test
- 🧩 **Jinja macro** that generates per-status order counts from one project variable
- 🖥️ **AI/BI dashboard** declared as a dbt exposure, so it shows up in the lineage

</details>

<details>
<summary><b>🧠 Design choices I'm proud of (click to expand)</b></summary>

<br>

- **Cost from the unit actually sold**, not the catalogue price, so historical profit doesn't move when prices change
- **Aggregate before joining** to avoid double-counting (fan-out)
- **One definition of a valid order**, defined once and reused by every KPI
- **PII dropped in staging**, so it never reaches downstream models or the dashboard

</details>

---

<a id="focus"></a>

## 🎯 What I'm focused on

| 🔭 Now | 🌱 Learning | 🤝 Looking for |
|---|---|---|
| Analytics engineering at Kleinanzeigen | CI for dbt, incremental models, snapshots | Full-time data engineering and analytics engineering roles |
| Building end-to-end dbt projects | Airflow orchestration patterns | Teams that care about tested, documented data |
| Master's in Data Science at HTW Berlin | Using AI tools such as Claude to work faster, with review | Open-source and team projects on BI and data quality |

---

<a id="stats"></a>

## 📊 GitHub stats

<div align="center">

<img src="https://streak-stats.demolab.com/?user=swadeshpanda&theme=tokyonight&hide_border=true" alt="GitHub streak" width="640">

<img src="https://ghchart.rshah.org/0a7ea4/swadeshpanda" alt="Contribution chart" width="100%">

![Followers](https://img.shields.io/github/followers/swadeshpanda?style=for-the-badge&logo=github&color=0a7ea4)
![Repos](https://img.shields.io/badge/public%20repos-14-8a63d2?style=for-the-badge&logo=github)
![Stars](https://img.shields.io/github/stars/swadeshpanda/Thelook-ecommerce-dbt-databricks?style=for-the-badge&logo=github&color=E67E22&label=project%20stars)
![Last commit](https://img.shields.io/github/last-commit/swadeshpanda/Thelook-ecommerce-dbt-databricks?style=for-the-badge&logo=git&color=2ea44f&label=last%20project%20commit)

<p align="right"><a href="#top">⬆️ back to top</a></p>

</div>

---

<div align="center">

<a id="contact"></a>

### 📬 Let's connect

I'm happy to talk about analytics engineering, dbt, data quality and building data teams.

[![LinkedIn](https://img.shields.io/badge/Message%20me%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/swadeshrp/)
[![Email](https://img.shields.io/badge/Send%20an%20email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:swadeshpanda95@gmail.com)

*Thanks for stopping by. 🙌*

</div>
