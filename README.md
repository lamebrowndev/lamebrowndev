<div align="center">

![M. Salman Ahmed | AI Engineer](https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,45:1E3A8A,100:06B6D4&height=240&section=header&text=M.%20SALMAN%20AHMED&fontSize=48&fontColor=FFFFFF&fontAlignY=36&desc=AI%20ENGINEER&descSize=16&descAlignY=55&animation=fadeIn)

### Agents that act. Systems you can trust.

I build LLM applications with reliable tool use, grounded answers,<br />
and the evaluation infrastructure to know when they work.

**LLM Applications · RAG · AI Agents · Python**

<a href="https://www.linkedin.com/in/muhammad-salman-ahmed/"><img src="https://img.shields.io/badge/LinkedIn-1E3A8A?style=for-the-badge&logoColor=white" alt="Connect on LinkedIn" /></a>
<a href="https://x.com/lamebrowndev"><img src="https://img.shields.io/badge/Follow%20on%20X-0F172A?style=for-the-badge&logo=x&logoColor=white" alt="Follow on X" /></a>
<a href="mailto:xdcoder3289@gmail.com"><img src="https://img.shields.io/badge/Email%20Me-0891B2?style=for-the-badge&logo=gmail&logoColor=white" alt="Email M. Salman Ahmed" /></a>

<sub>Islamabad, Pakistan &nbsp; / &nbsp; 4+ years in software engineering &nbsp; / &nbsp; 2+ years building LLM applications</sub>

<br /><br />

[About](#about) &nbsp; · &nbsp; [Impact](#impact) &nbsp; · &nbsp; [Selected Work](#selected-work) &nbsp; · &nbsp; [Toolkit](#toolkit)

</div>

---

## About

I'm **M. Salman Ahmed**, an **AI Engineer** with a background in software engineering. I build **LLM applications, retrieval systems, and AI agents**. I connect language models to tools, data, and real workflows with explicit permissions, human approval, and observable execution.

My foundation is in frontend and API engineering. Today, I build across the agent lifecycle: orchestration, retrieval, tool integration, evaluation, and delivery. I pay close attention to the details that make a system dependable: how it handles a failed tool call, whose documents it can retrieve, when it asks for approval, and what each successful task costs.

**My approach:** make the behavior measurable, the permissions clear, and the failures recoverable.

## Impact

<table>
<tr>
<td align="center" width="33%">
<h3>$0.18 → $0.11</h3>
<strong>Cost per successful task</strong>
<br /><sub>More efficient agent execution</sub>
</td>
<td align="center" width="33%">
<h3>12% → 2%</h3>
<strong>Stalled runs</strong>
<br /><sub>Measured across 500 tests</sub>
</td>
<td align="center" width="33%">
<h3>8.4s → 5.9s</h3>
<strong>p95 latency</strong>
<br /><sub>Measured across 500 replays</sub>
</td>
</tr>
</table>

At **Felic.io**, my work also includes hybrid retrieval over **24,000 documents**, reaching **0.86 Recall@5** on 200 queries, and integrating **6 MCP/API tools** with scoped access, input validation, and human approval for writes.

## Selected Work

### 01 / [Citizen Service Workflow Agent](https://github.com/lamebrowndev/citizen-service-workflow-agent)

**A prototype for completing service tasks through controlled tool use.**

Built with Python, LangGraph, FastAPI, and MCP. Reached **96% tool-call accuracy across 600 labeled calls**, with a median of **4 steps per task**. Compared single-agent and multi-agent designs on 150 service tasks and selected single agents at equal task success.

`Agent orchestration` `Tool use` `Human approval` `Architecture evaluation`

### 02 / [Urdu-English Policy Assistant](https://github.com/lamebrowndev/urdu-english-policy-assistant)

**A bilingual retrieval prototype with answers people can trace to their sources.**

Combined pgvector and BM25 for hybrid retrieval, with cited answers, document-level permissions, and audit logs. Achieved **90% human-scored answer accuracy across 200 balanced Urdu and English policy questions**.

`Hybrid RAG` `Multilingual retrieval` `Citations` `Access control`

## Toolkit

**Languages & applications**

![Python](https://img.shields.io/badge/Python-0F172A?style=flat-square&logo=python&logoColor=38BDF8)
![TypeScript](https://img.shields.io/badge/TypeScript-0F172A?style=flat-square&logo=typescript&logoColor=38BDF8)
![React](https://img.shields.io/badge/React-0F172A?style=flat-square&logo=react&logoColor=38BDF8)
![FastAPI](https://img.shields.io/badge/FastAPI-0F172A?style=flat-square&logo=fastapi&logoColor=38BDF8)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0F172A?style=flat-square&logo=postgresql&logoColor=38BDF8)

**Agents & retrieval**

`LangGraph` · `LangChain` · `OpenAI SDK` · `AWS Bedrock` · `MCP`  
`pgvector` · `BM25` · `Embeddings` · `Hybrid search` · `Access-aware retrieval`

**Evaluation & delivery**

![LangSmith](https://img.shields.io/badge/LangSmith-0F172A?style=flat-square&logo=langchain&logoColor=38BDF8)
![pytest](https://img.shields.io/badge/pytest-0F172A?style=flat-square&logo=pytest&logoColor=38BDF8)
![Jest](https://img.shields.io/badge/Jest-0F172A?style=flat-square&logo=jest&logoColor=38BDF8)
![Docker](https://img.shields.io/badge/Docker-0F172A?style=flat-square&logo=docker&logoColor=38BDF8)
![AWS](https://img.shields.io/badge/AWS-0F172A?style=flat-square&logoColor=38BDF8)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0F172A?style=flat-square&logo=githubactions&logoColor=38BDF8)

<br />

<details>
<summary><strong>How I engineer dependable agents</strong></summary>

<br />

- **Bound execution.** Set step limits, timeouts, context budgets, and recovery paths.
- **Scope access.** Use least privilege, document-level permissions, and isolated user memory.
- **Keep people in control.** Require human approval for writes and retain audit trails.
- **Evaluate changes.** Version prompts, tool schemas, and structured outputs; replay representative tasks in CI.
- **Inspect failures.** Trace runs, document failure cases, and turn them into regression tests.
- **Justify complexity.** Compare architectures against task success, latency, and cost.

</details>

<details>
<summary><strong>Background & education</strong></summary>

<br />

**Agentic Systems Engineer · Felic.io**  
March 2023 to Present · Remote, United States

**Front End Engineer · Advergic.com**  
November 2021 to March 2023 · Islamabad  
Built React dashboards and TypeScript API integrations, reduced dashboard render time by 19%, and added 60 Jest tests for critical flows and API failures.

**MS in Computer Science, AI Track**  
Ghulam Ishaq Khan Institute of Engineering Sciences

**BS in Computer Science**  
VU Pakistan, Islamabad

</details>

---

<div align="center">

### Let's build something dependable.

Interested in agent workflows, retrieval systems, or evaluating LLM applications?<br />
**[Get in touch](mailto:xdcoder3289@gmail.com)** · **[Connect on LinkedIn](https://www.linkedin.com/in/muhammad-salman-ahmed/)** · **[Find me on X](https://x.com/lamebrowndev)**

<br />

![Contribution snake animation](https://raw.githubusercontent.com/lamebrowndev/lamebrowndev/output/snake.svg)

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,45:1E3A8A,100:06B6D4&height=110&section=footer)

</div>
