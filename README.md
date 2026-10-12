\# KPI Sense — Intelligent KPI Monitoring \& Reporting



KPI Sense is a Python application for monitoring key performance indicators,

detecting anomalies with machine learning and generating analytical reports.



> \*\*Status:\*\* early development. Project for the course

> \*Fundamentals of Artificial Intelligence\* at Poznań University of Economics and Business.



\## Planned features



\- CSV data ingestion and validation

\- Configurable KPI calculation engine

\- Anomaly detection: statistical baseline vs. Isolation Forest

\- Trend analysis

\- Interactive Streamlit dashboard

\- Exportable HTML report



\## Getting started



Requires \[uv](https://docs.astral.sh/uv/).



```bash

git clone https://github.com/martynawieruszewska/kpi-sense.git

cd kpi-sense

uv sync

uv run pre-commit install

uv run pytest

```



\## Authors



\- Martyna Wieruszewska

\- Julia Pieczara



\## License



Code is released under the MIT License. See \[LICENSE](LICENSE).
