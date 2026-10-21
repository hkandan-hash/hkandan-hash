# Hi, I'm Harish 👋

**Data Science · Agentic AI · Data Engineering**

I build AI agents and data systems that are reliable, observable, and honest about what they don't know.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hkandan-hash)

---

## 🧭 About Me

I'm pursuing a Master's in Data Science at Saint Peter's University. Before that, I spent two years as a Software Engineer at Tata Consultancy Services building microservices for a telecom billing product, including a rating engine that processed over a million call detail records.

Questions I keep asking about anything I build:

- How do I know this answer is right, and what happens when it isn't?
- Can I see what the system did, step by step, after the fact?
- Is it safe to re-run?

---

## 🛠️ Technologies I Work With

### Languages
- **Python**, **TypeScript**, **Java**, **SQL**

### AI & Agents
- **LangGraph / LangGraph.js**: agent state machines, tool calling, retry and escalation loops
- **Claude on Amazon Bedrock**: via the Anthropic SDK
- **Hugging Face Transformers, Sentence-Transformers, PyTorch**: local embedding and QA models

### Data
- **pandas**, **SQLite**, **MySQL**, **Cassandra**, **Kafka**, **Redis**

### Cloud & Observability
- **AWS**: Lambda, Bedrock, S3, CloudFront, CloudWatch, CDK
- **OpenTelemetry**: tracing across agent steps
- **Datadog**

### Frontend & Delivery
- **React**, **Vite**, **Chart.js**
- **Docker**, **GitHub Actions**, **Jenkins**, **Spring Boot**

---

## 🚀 Featured Projects

### [Portfolio Monitoring Agent](https://github.com/hkandan-hash/portfolio-monitoring-agent)
An agentic AI assistant for an investment team. It answers questions about allocation drift, manager performance and meeting notes by calling tools in parallel, and every run is traced.

**Engineering work**
- LangGraph.js agent loop with an iteration cap, and tool failures returned to the model instead of crashing the run
- Claude on Amazon Bedrock with a refusal fallback, plus an offline planner so it runs and tests without cloud access
- OpenTelemetry spans per graph node, model call and tool, CloudWatch EMF metrics, and trace-linked JSON logs
- React UI with run metrics and a trace waterfall; AWS CDK stack with a CloudWatch dashboard and alarms

**Built with:** `TypeScript` · `LangGraph.js` · `Amazon Bedrock` · `OpenTelemetry` · `React` · `AWS CDK`

### [Agentic Support Triage](https://github.com/hkandan-hash/agentic-support-triage)
A LangGraph agent that routes support questions, retrieves passages with sentence embeddings, and extracts answers with a transformer QA model. When it isn't confident it broadens its search and retries, then escalates to a human instead of guessing.

**Engineering work**
- Evaluated on 11 questions: 11/11 routing and 7/9 correct answers, up from 5/11 and 3/9 in the first version
- Graph tests with scripted fake models, so CI runs without downloading models

**Built with:** `Python` · `LangGraph` · `Transformers` · `PyTorch` · `pytest`

### [US Weather Analytics Dashboard](https://github.com/hkandan-hash/us-weather-analytics) · [live](https://hkandan-hash.github.io/us-weather-analytics/)
A year of daily weather for four US cities, cleaned and aggregated with pandas and explored in an interactive dashboard.

**Built with:** `Python` · `pandas` · `Chart.js` · `GitHub Pages`

### [Weather Ingestion Pipeline](https://github.com/hkandan-hash/weather-ingestion-pipeline)
Ingests hourly weather data from the Open-Meteo API, validates it, and loads it into a SQLite warehouse.

**Engineering problems explored**
- Idempotent upserts and safe re-runs
- Immutable raw layer and data quality checks

**Built with:** `Python` · `SQLite` · `pytest` · `GitHub Actions`

---

## 🎯 What I'm Working On

```
Agentic AI
├── Evaluation
│   ├── Measuring agent accuracy, not just demoing it
│   └── Honest failure modes: retry, escalate, refuse
├── Observability
│   ├── Tracing every model and tool call
│   └── Metrics and alarms that catch regressions
└── Data
    ├── Reliable ingestion and quality checks
    └── Cloud data platforms
```

---

## 🧱 How I Like to Build

```
Define the question
        ↓
Build the smallest thing that answers it
        ↓
Measure it against real cases
        ↓
Trace it, so failures are explainable
        ↓
Fix what the measurements show, then repeat
```

---

## 📊 GitHub Stats

![Stats](https://github-readme-stats.vercel.app/api?username=hkandan-hash&show_icons=true&theme=default)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=hkandan-hash&layout=compact)

---

## 🤝 Let's Connect

I'm open to data science, AI and data engineering internships and collaborations. Feel free to reach out through GitHub.
