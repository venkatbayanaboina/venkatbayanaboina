### Hi, I'm Venkat — CS undergrad at NIT Calicut, building in systems, security, and applied AI.

I like working close to the metal: file transfer protocols, intrusion detection on embedded networks, and agentic systems that have to prove their decisions with measurable evidence — not just demo well.

```
class Engineer:
    def __init__(self):
        self.focus = ["systems programming", "network security", "distributed systems", "applied AI"]
        self.currently_building = "OpsPilot — AI SRE agent with a deterministic safety architecture"
        self.currently_learning = ["low-level networking internals", "DSA", "agentic evaluation methodology"]
```

**What I'm building**

- **[OpsPilot](https://github.com/venkatbayanaboina/opspilot)** — AI SRE agent with a deterministic safety architecture: the LLM investigates using native tool calling but never executes; every action is allowlisted and policy-gated, and recovery is verified from live system state. Benchmarked 5 modes across **473+ measured fault runs on 11 scenarios** — found the runbook scores **1.0 on known failures** but **0.2 on adversarial ones** (24 unnecessary actions, 5 false recoveries) while the LLM agent recovered **0 incidents**, and published the negative result with per-step traces, falsifiable predictions, and bootstrap 95% CIs.

- **[Research RAG Assistant](https://github.com/venkatbayanaboina/research-rag-assistant)** — Retrieval-Augmented Generation pipeline for grounded Q&A over research papers. Hierarchical chunking to preserve section structure, BGE embeddings indexed in FAISS, Gemini for context-grounded summarization.

- **[JAVIN Share](https://github.com/venkatbayanaboina/javin-share)** — cross-platform LAN file transfer with no cloud dependency. Three interchangeable relay strategies (disk / stream / buffered) to trade off throughput, latency, and memory under different network conditions. Backpressure-aware buffering and sender-lock concurrency control to keep multi-GB transfers reliable over flaky Wi-Fi.

- **[Hybrid CAN Bus Intrusion Detection System](https://github.com/venkatbayanaboina/mitigation-of-dos-attack-in-can-bus)** — real-time anomaly detection for in-vehicle networks, built around a Gaussian Naive Bayes classifier over engineered traffic features (timing, frequency, graph-relational). B.Tech research project, written up as a full academic report.

**Stack**

`Python` `C++` `Java` `JavaScript` · `FastAPI` `Node.js` `Express` `Socket.IO` · `PostgreSQL` `SQLite` `MySQL` · `Docker` `Prometheus` `Grafana` `GitHub Actions` · `FAISS` `scikit-learn` `NetworkX` `LLM Tool-Calling` · `Git`

**Elsewhere**

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/venkat-bayanaboina-a10824322/)
[![LeetCode](https://img.shields.io/badge/-LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/nanibnayanaboina/)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:nanibayanaboina2750@gmail.com)

---


