# Awesome LLM Agent Privacy & Compliance Papers 🔒

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/yagobski/awesome-llm-agent-privacy/pulls)
[![Stars](https://img.shields.io/github/stars/yagobski/awesome-llm-agent-privacy?style=social)](https://github.com/yagobski/awesome-llm-agent-privacy)

> A curated list of papers on **privacy, security, and compliance** in LLM-based agent systems — covering attacks, defenses, benchmarks, and regulatory frameworks.

LLM agents increasingly handle sensitive data across healthcare, finance, legal, and corporate domains. Unlike traditional models, agents introduce **new attack surfaces**: inter-agent communication channels, tool arguments, shared memory, and RAG retrieval — all of which can leak private information without triggering output-level audits.

This list tracks the growing body of research addressing these challenges.

---

## 📋 Table of Contents

- [🔍 Surveys & Overviews](#-surveys--overviews)
- [📊 Benchmarks & Measurement](#-benchmarks--measurement)
- [⚔️ Attacks & Threat Models](#️-attacks--threat-models)
- [🛡️ Defenses & Mitigations](#️-defenses--mitigations)
- [🏥 Domain-Specific Privacy](#-domain-specific-privacy)
- [📜 Compliance, Regulation & Governance](#-compliance-regulation--governance)
- [🔧 Infrastructure & Protocols](#-infrastructure--protocols)
- [Contributing](#contributing)

---

## 🔍 Surveys & Overviews

| Date | Title | Venue | Links |
|------|-------|-------|-------|
| 2024/07 | **The Emerged Security and Privacy of LLM Agent: A Survey with Case Studies** | arXiv | [[paper]](https://arxiv.org/abs/2407.19354) |
| 2024/11 | **Navigating the Risks: A Survey of Security, Privacy, and Ethics Threats in LLM-Based Agents** | arXiv | [[paper]](https://arxiv.org/abs/2411.09523) |
| 2025/06 | **TRiSM for Agentic AI: A Review of Trust, Risk, and Security Management in LLM-based Agentic Multi-Agent Systems** | arXiv | [[paper]](https://arxiv.org/abs/2506.04133) |
| 2025/06 | **SoK: The Privacy Paradox of Large Language Models** | arXiv | [[paper]](https://arxiv.org/abs/2506.12699) |
| 2025/06 | **From Prompt Injections to Protocol Exploits: Threats in LLM-Powered AI Agents Workflows** | arXiv | [[paper]](https://arxiv.org/abs/2506.23260) |
| 2025/05 | **A Survey on Privacy Risks and Protection in Large Language Models** | arXiv | [[paper]](https://arxiv.org/abs/2505.01976) |
| 2025/04 | **A Survey of AI Agent Protocols** | arXiv | [[paper]](https://arxiv.org/abs/2504.16736) |
| 2025/01 | **On Protecting the Data Privacy of LLMs and LLM Agents: A Literature Review** | HCC | [[paper]](https://journal.hep.com.cn/hcc/EN/10.1016/j.hcc.2025.100300) |

---

## 📊 Benchmarks & Measurement

> Papers that **quantify** privacy leakage in LLM agent systems.

| Date | Title | Venue | Links |
|------|-------|-------|-------|
| 2026/02 | ⭐ **AgentLeak: A Full-Stack Benchmark for Privacy Leakage in Multi-Agent LLM Systems** | arXiv | [[paper]](https://arxiv.org/abs/2602.11510) |
| 2026/02 | **AgentLAB: Benchmarking LLM Agents against Long-Horizon Attacks** | arXiv | [[paper]](https://arxiv.org/abs/2602.16901) |
| 2025/11 | **Auditing M-LLMs for Privacy Risks: A Synthetic Benchmark and Evaluation Framework** | arXiv | [[paper]](https://arxiv.org/abs/2511.03248) |
| 2025/10 | **MAGPIE: A Benchmark for Multi-AGent Contextual PrIvacy Evaluation** | arXiv | [[paper]](https://arxiv.org/abs/2510.15186) |
| 2025/09 | **The Sum Leaks More Than Its Parts: Compositional Privacy Risks in Multi-Agent Collaboration** | arXiv | [[paper]](https://arxiv.org/abs/2509.14284) [[code]](https://github.com/Vaidehi99/CompositionalPrivacyRisks) |
| 2025/09 | **Privacy in Action: Towards Realistic Privacy Mitigation and Evaluation for LLM-Powered Agents** | arXiv | [[paper]](https://arxiv.org/abs/2509.17488) |
| 2025/08 | **Mind the Third Eye! Benchmarking Privacy Awareness in MLLM-powered Smartphone Agents** | AAAI 2026 | [[paper]](https://arxiv.org/abs/2508.19493) [[code]](https://github.com/Zhixin-L/SAPA-Bench) |
| 2025/06 | **MAGPIE: A Dataset for Multi-AGent Contextual PrIvacy Evaluation** | arXiv | [[paper]](https://arxiv.org/abs/2506.20737) |
| 2025/03 | **AgentDAM: Privacy Leakage Evaluation for Autonomous Web Agents** | NeurIPS 2025 | [[paper]](https://arxiv.org/abs/2503.09780) |
| 2024/12 | **Agent Tools Orchestration Leaks More: Dataset, Benchmark, and Mitigation** | arXiv | [[paper]](https://arxiv.org/abs/2512.16310) |

---

## ⚔️ Attacks & Threat Models

### Prompt Injection & Data Exfiltration

| Date | Title | Venue | Links |
|------|-------|-------|-------|
| 2026/02 | **The Landscape of Prompt Injection Threats in LLM Agents: From Taxonomy to Defense** | arXiv | [[paper]](https://arxiv.org/abs/2602.10453) |
| 2026/02 | **AgentLAB: Benchmarking LLM Agents against Long-Horizon Attacks** | arXiv | [[paper]](https://arxiv.org/abs/2602.16901) |
| 2025/11 | **When AI Agents Collude Online: Financial Fraud Risks by Collaborative LLM Agents on Social Platforms** | arXiv | [[paper]](https://arxiv.org/abs/2511.06448) |
| 2025/08 | **Searching for Privacy Risks in LLM Agents via Simulation** | arXiv | [[paper]](https://arxiv.org/abs/2508.10880) |
| 2025/04 | **Les Dissonances: Cross-Tool Harvesting and Polluting in Multi-Tool Empowered LLM Agents** | arXiv | [[paper]](https://arxiv.org/abs/2504.03111) |
| 2025/02 | **Red-Teaming LLM Multi-Agent Systems via Communication Attacks** | arXiv | [[paper]](https://arxiv.org/abs/2502.14847) |
| 2025/02 | **Commercial LLM Agents Are Already Vulnerable to Simple Yet Dangerous Attacks** | arXiv | [[paper]](https://arxiv.org/abs/2502.08586) |
| 2025/02 | **RTBAS: Defending LLM Agents Against Prompt Injection and Privacy Leakage** | arXiv | [[paper]](https://arxiv.org/abs/2502.08966) |
| 2024/07 | **Flooding Spread of Manipulated Knowledge in LLM-Based Multi-Agent Communities** | arXiv | [[paper]](https://arxiv.org/abs/2407.07791) |

### Backdoor & Distributed Attacks

| Date | Title | Venue | Links |
|------|-------|-------|-------|
| 2025/10 | **Collaborative Shadows: Distributed Backdoor Attacks in LLM-Based Multi-Agent Systems** | arXiv | [[paper]](https://arxiv.org/abs/2510.11246) |
| 2025/09 | **A Multi-Agent LLM Defense Pipeline Against Prompt Injection Attacks** | arXiv | [[paper]](https://arxiv.org/abs/2509.14285) |

### Memory & Retrieval Attacks

| Date | Title | Venue | Links |
|------|-------|-------|-------|
| 2025/10 | **Terrarium: Revisiting the Blackboard for Multi-Agent Safety, Privacy, and Security Studies** | arXiv | [[paper]](https://arxiv.org/abs/2510.14312) |

---

## 🛡️ Defenses & Mitigations

### Agent-Level Defenses

| Date | Title | Venue | Links |
|------|-------|-------|-------|
| 2026/03 | **Contextualized Privacy Defense for LLM Agents** | arXiv | [[paper]](https://arxiv.org/abs/2603.02983) |
| 2025/04 | **Progent: Programmable Privilege Control for LLM Agents** | arXiv | [[paper]](https://arxiv.org/abs/2504.11703) |
| 2025/09 | **Privacy in Action: Towards Realistic Privacy Mitigation and Evaluation for LLM-Powered Agents** | arXiv | [[paper]](https://arxiv.org/abs/2509.17488) |

### Unlearning & Forgetting

| Date | Title | Venue | Links |
|------|-------|-------|-------|
| 2025/02 | **ALU: Agentic LLM Unlearning** | arXiv | [[paper]](https://arxiv.org/abs/2502.00406) |

### Privacy Guardrails & Output Filtering

| Date | Title | Venue | Links |
|------|-------|-------|-------|
| 2025/01 | **Deploying Privacy Guardrails for LLMs: A Comparative Analysis of Real-World Applications** | arXiv | [[paper]](https://arxiv.org/abs/2501.12456) |

---

## 🏥 Domain-Specific Privacy

| Date | Title | Domain | Links |
|------|-------|--------|-------|
| 2025/09 | **User Privacy and Large Language Models: An Analysis of Frontier Developers' Privacy Policies** | Policy | [[paper]](https://arxiv.org/abs/2509.05382) |
| 2025/05 | **Privacy Meets Explainability: Managing Confidential Data and Transparency Policies in LLM-Empowered Science** | Research | [[paper]](https://arxiv.org/abs/2504.09961) |
| 2025 | **A Survey on Privacy Issues and Mitigation Strategies for LLMs in Healthcare** | Healthcare | [[paper]](https://link.springer.com/article/10.1007/s11227-025-08146-1) |

---

## 📜 Compliance, Regulation & Governance

| Date | Title | Venue | Links |
|------|-------|-------|-------|
| 2025/12 | **Global AI Governance Overview: Understanding Regulatory Requirements Across Global Jurisdictions** | arXiv | [[paper]](https://arxiv.org/abs/2512.02046) |
| 2025/09 | **Privacy in Action: Realistic GDPR/CCPA-aligned Evaluation** | arXiv | [[paper]](https://arxiv.org/abs/2509.17488) |

---

## 🔧 Infrastructure & Protocols

| Date | Title | Venue | Links |
|------|-------|-------|-------|
| 2025/04 | **A Survey of AI Agent Protocols** (MCP, A2A, security) | arXiv | [[paper]](https://arxiv.org/abs/2504.16736) |
| 2025/06 | **From Prompt Injections to Protocol Exploits: MCP/A2A vulnerabilities** | arXiv | [[paper]](https://arxiv.org/abs/2506.23260) |

---

## Contributing

Contributions are welcome! If you know a paper that should be in this list:

1. Fork the repository
2. Add the paper in the appropriate section following the table format
3. Submit a pull request

**Format:**
```
| YYYY/MM | **Paper Title** | Venue | [[paper]](arxiv_link) [[code]](github_link) |
```

---

## ⭐ Key Paper

If you use this list or find it useful, please also consider citing our benchmark paper:

```bibtex
@article{elyagoubi2026agentleak,
  title={AgentLeak: A Full-Stack Benchmark for Privacy Leakage in Multi-Agent LLM Systems},
  author={El Yagoubi, Faouzi and Al Mallah, Ranwa and Badu-Marfo, Godwin},
  journal={arXiv preprint arXiv:2602.11510},
  year={2026}
}
```

---

*Last updated: March 2026 | Maintained by [Faouzi El Yagoubi](https://github.com/yagobski)*
