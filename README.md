# Awesome-Data-Pipeline-Observability

# Awesome-Data-Pipeline-Observability

## Top Data Pipeline Observability Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Data Reliability, Anomaly Detection, Freshness & Volume Monitoring, Pipeline Health & Data Downtime Prevention*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Pipeline Observability**. These systems monitor data freshness, volume, schema, distribution, and lineage so teams can detect and resolve data downtime before it impacts analytics and AI.



**Examples** include Monte Carlo, Bigeye, Acceldata, Soda, Metaplane, Anomalo, Databand (IBM), Datafold, Elementary, and WhyLabs (the category leaders).



**Open-source emphasis**: Data observability has a strong open foundation. **Great Expectations**, **Soda Core**, **Elementary**, and related testing frameworks provide production-grade monitoring and validation. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Monte Carlo](https://www.montecarlodata.com/)**  

  Leading data observability platform with automated monitoring for freshness, volume, schema, and distribution, plus lineage-based incident triage.



- **[Bigeye](https://www.bigeye.com/)**  

  Data observability and SLA platform with metric monitoring, autothresholds, and lineage for reliable data products.



- **[Acceldata](https://www.acceldata.io/)**  

  Data observability and reliability platform covering pipelines, quality, and operational health at scale.



- **[Soda](https://www.soda.io/)**  

  Data quality and observability platform with SodaCL checks, cloud and self-hosted options, and contract-style testing.



- **[Metaplane](https://www.metaplane.dev/)**  

  Warehouse-native data observability focused on automatic anomaly detection and quick time-to-value.



- **[Anomalo](https://www.anomalo.com/)**  

  AI-native data quality and observability platform specializing in unsupervised anomaly detection.



- **[Databand (IBM)](https://www.ibm.com/products/databand)**  

  IBM’s data observability offering for pipeline monitoring, lineage, and operational reliability.



- **[Datafold](https://www.datafold.com/)**  

  Data quality and diff platform used for regression testing, CI checks, and change impact analysis.



- **[Elementary](https://www.elementary-data.com/)**  

  dbt-native data observability (open-source core + commercial cloud) for monitoring models, tests, and anomalies.



- **[WhyLabs](https://whylabs.ai/)**  

  AI and data observability platform focused on monitoring data and model health over time.



## Open-Source GitHub Projects

- **[Great Expectations (GX Core)](https://github.com/great-expectations/great_expectations)**  

  Open-source data quality framework for defining, running, and documenting expectations about datasets—widely used as a validation and monitoring foundation.



- **[Soda Core](https://github.com/sodadata/soda-core)**  

  Open-source CLI and library for data quality checks using SodaCL—scans datasets for freshness, completeness, validity, and more.



- **[Elementary](https://github.com/elementary-data/elementary)**  

  Open-source dbt-native observability: dbt package + CLI for anomaly detection, test results, reports, and alerts.



- **[dbt tests](https://github.com/dbt-labs/dbt-core)**  

  Built-in and custom tests in dbt projects that form a first line of data quality and pipeline health checks.



- **[OpenLineage](https://github.com/OpenLineage/OpenLineage)**  

  Open standard for collecting lineage metadata that supports impact analysis and observability context.



- **[Marquez](https://github.com/MarquezProject/marquez)**  

  Open-source metadata service and OpenLineage reference implementation for job and dataset lineage.



- **[Data quality and anomaly open libraries](https://github.com/)**  

  Community packages for statistical anomaly detection, schema drift checks, and metric monitoring.



- **[Documentation and GX / Soda / Elementary playbooks](https://greatexpectations.io/)**  

  Guides for integrating open quality checks into orchestrators and CI pipelines.



- **[Self-hosted observability stacks](https://github.com/)**  

  Patterns combining Great Expectations or Soda Core + Elementary + OpenLineage for end-to-end open monitoring.



- **[Alerting and report generators](https://github.com/)**  

  Open tools that turn test results and anomalies into Slack/Teams notifications and static reports.



### Additional Strong Open-Source Options

- Starting with **dbt tests + Elementary** for dbt-centric stacks.

- Using **Great Expectations** or **Soda Core** for explicit, code-defined quality gates.

- Emitting lineage with **OpenLineage** for better incident context.

- Accepting that fully automated, cross-warehouse, low-configuration enterprise observability still favors commercial platforms (Monte Carlo, Anomalo, Bigeye, Metaplane, Acceldata, etc.).

- Focusing open-source efforts on test coverage, ownership of checks, and preventing silent data failures.



**Frameworks for building custom systems**: Define expectations with GX or Soda → run in CI and orchestrators → monitor dbt models with Elementary → collect lineage via OpenLineage → alert on failures. Suitable for analytics engineering teams. Large estates with high blast radius often add commercial observability for automatic coverage.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Observability reduces but does not eliminate data risk. Open-source tools require correct configuration and ownership. This list is not operational advice.



---

**Made for analytics engineers, data platform teams, and reliability advocates.**

Let's keep data pipelines trustworthy, visible, and as open as practical.
