<h1 align="center">Hi, I'm Karthik 👋</h1>

<p align="center">
  Agentic AI Engineer — I build multi-agent systems: orchestrators, sub-agents, routing, hooks and guardrails.<br/>
  Lead Software Engineer at Persistent Systems · previously enterprise RAG and agents at Nomura.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/basupallykarthikreddy/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://basupallykarthikreddy.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://medium.com/@basupallykarthikreddy"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
  <a href="https://leetcode.com/u/karthikredddyy/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="mailto:basupallykarthikreddy@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

### 🧠 What I do

I design **agentic systems that hold up in production** — the orchestration, delegation and
governance around LLMs, not just the prompt.

- 🕸️ **Multi-agent orchestration** — a single orchestrator breaking work into bounded tasks and
  delegating to specialist sub-agents in a hierarchical tree, on **GitHub Copilot custom agents**.
- 🔀 **Routing & hand-offs** — per-caller allow-lists of child agents (no global registry),
  path-scoped instructions, and a structured status contract (`completed / partial / blocked / failed`)
  so the orchestrator aggregates and escalates deterministically.
- 🛡️ **Guardrails** — least-privilege tool scoping, human-in-the-loop approval gates, lifecycle hooks,
  MCP tool integration and agent memory.
- 🤖 **Agent Mode at Nomura** — multi-agent orchestration in **LangGraph** with routing, state and
  hand-offs, and **MCP** tool-calling into Confluence, Jira and financial data platforms.
- 🔎 **Enterprise RAG for 15,000+ users** — hybrid retrieval (BM25 + dense on PGVector, Reciprocal Rank
  Fusion, cross-encoder re-ranking) and a **RAG evaluation pipeline** (faithfulness, answer relevancy,
  contextual precision/recall) so changes are measured, not guessed.
- 🔧 **Sonar AutoFix** — an agentic CI/CD remediation platform that cleared **~40% of SonarQube issues**
  across enterprise microservices and won a **Nomura Star** award.

---

### 🚀 Featured projects

| Project | What it is |
|---|---|
| **[Agentic-Orchestration-Harness](https://github.com/karthikreddy-7/Agentic-Orchestration-Harness)** | Hybrid orchestration framework for **VS Code GitHub Copilot custom agents** — orchestrator → sub-agent hierarchy, routing without a global registry, structured status contracts, least-privilege tools, approval gates and optional hooks/MCP/memory. Installs into any repo's `.github/`. |
| **[ai-engineering-playbook](https://github.com/karthikreddy-7/ai-engineering-playbook)** ⭐63 | A zero-to-100 learning path for applied AI engineering — RAG, embeddings, vector search, agents, MCP and the production engineering around them. 56 pages, built as a searchable site. |
| **[ChoreoAI](https://github.com/choreo-ai/choreoai)** | Open-source Python framework for building **multi-agent systems that survive production** — budgets, guardrails, retries, evals and observability. On [PyPI](https://pypi.org/project/choreoai/); companion coding-agent harness: [choreoai-cli](https://github.com/choreo-ai/choreoai-cli). Pre-alpha, building in public. |
| **[CodeRAG](https://github.com/karthikreddy-7/coderag)** | **Code-aware RAG** that models source code by structure — method signatures, call graphs, static analysis — so retrieval follows real code relationships. `Python · Sentence Transformers · ChromaDB/PGVector/Weaviate · React · TypeScript` |
| **[TCS-NQT-CODING-SHEET](https://github.com/karthikreddy-7/TCS-NQT-CODING-SHEET)** ⭐985 · **[Infosys-SP-Coding-Questions](https://github.com/karthikreddy-7/Infosys-SP-Coding-Questions)** ⭐148 | Curated solution sets for the TCS NQT and Infosys SP hiring tests. **~1,100 stars combined.** |

---

### 🧰 Tech stack

**Agentic & LLM engineering**
<p>
  <img src="https://img.shields.io/badge/Multi--Agent%20Systems-6E40C9?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/GitHub%20Copilot%20Agents-000000?style=for-the-badge&logo=githubcopilot&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS%20Bedrock-232F3E?style=for-the-badge&logo=amazonaws&logoColor=FF9900"/>
  <img src="https://img.shields.io/badge/RAG-4B8BBE?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Langfuse%20%2F%20LangSmith-1C3C3C?style=for-the-badge"/>
</p>

**Retrieval & data**
<p>
  <img src="https://img.shields.io/badge/PGVector-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Weaviate-00C29A?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Sentence%20Transformers-FF6F61?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
</p>

**Languages & infra**
<p>
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitLab%20CI%2FCD-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
</p>

---

### 🎓 Background

**B.Tech, Electronics & Communication Engineering — VIT Vellore** (2020 – 2024), CGPA 8.71/10.

---

### 📊 GitHub stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=karthikreddy-7&theme=tokyonight" width="82%"/>
</p>
<p align="center">
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=karthikreddy-7&theme=tokyonight"/>
  <img width="49%" src="https://streak-stats.demolab.com/?user=karthikreddy-7&theme=tokyonight&hide_border=true"/>
</p>
