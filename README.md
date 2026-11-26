<div align="center">

# Hi, I'm Muhammad Kumail 👋

### AI Engineer · I build RAG pipelines and multi-agent LLM systems that ship

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=00B4D8&center=true&vCenter=true&width=620&lines=Offline+RAG+assistant+%40+HBL+%E2%80%94+45%25+%E2%86%92+80%25+accuracy;%F0%9F%8F%86+1st+place%2C+AI+Mustaqbil+2.0+Hackathon;6-agent+LLM+orchestration+with+FastAPI+%2B+asyncio;CS+%40+FAST-NUCES+%E2%80%9927+%C2%B7+IBM-certified+AI+Developer)](https://github.com/muhammadkumail1)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-muhammad--kumail1-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-kumail1)
[![Email](https://img.shields.io/badge/Email-Get_in_touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kumail.muhammad2004@gmail.com)
[![Live Demo](https://img.shields.io/badge/Live_Demo-The_AI_Scientist-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://klayr.vercel.app)

</div>

---

## 🧠 About me

- 🏦 **AI Engineering Intern @ HBL** (Pakistan's largest bank) — sole engineer on an **offline, privacy-first RAG assistant** for internal staff. Hybrid retrieval (FAISS + BM25) lifted answer accuracy from **45% → 80%**, with zero cloud dependency.
- 🏆 **1st place, AI Mustaqbil 2.0** — shipped a **6-agent financial intelligence platform** in 24 hours with a 3-person team.
- 🎓 **BS Computer Science @ FAST-NUCES** (Karachi), graduating **Jun 2027**.
- 📜 IBM AI Developer Professional Certificate · Google AI Essentials · Microsoft Azure AI Fundamentals
- 🔭 **Open to:** AI/ML engineering internships and new-grad roles, plus hackathon teams building with LLMs.

---

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🏆 [FreelanceFlow](https://github.com/muhammadkumail1/FreelanceFlow)
**1st place, AI Mustaqbil 2.0 (86/100).** Six concurrent LLM agents (FX rates, platform fees, FBR tax rules, conflict resolution) tell Pakistani freelancers **when and how to withdraw** so they keep the 4–8% usually lost to fees.

`FastAPI` `asyncio` `WebSockets` `React` `Groq · Llama 3`

</td>
<td width="50%" valign="top">

### 🔬 [The AI Scientist](https://github.com/muhammadkumail1/Klayr) · [**live**](https://klayr.vercel.app)
**Hack-Nation × Fulcrum Science.** Turns a plain-English hypothesis into a lab-ready experiment plan (literature QC, protocol, biosafety, risks) in **under 60 seconds** with an 8-node LangGraph pipeline streamed over SSE.

`LangGraph` `FastAPI` `PostgreSQL` `Redis` `Docker` `TypeScript`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [SpamShield](https://github.com/muhammadkumail1/SpamShield)
An email spam detector with a **live 9-stage analysis pipeline** streamed over Server-Sent Events. Built in **both Node/Express and [Python/FastAPI](https://github.com/muhammadkumail1/AI_Project)**, with rate limiting, security headers and tests.

`React` `Express 5` `FastAPI` `SSE` `pytest`

</td>
<td width="50%" valign="top">

### 📋 [DevTrack](https://github.com/muhammadkumail1/DevTrack)
A lightweight Jira alternative for student teams and small software houses: sprints, tasks, bug tracking, **role-based access control** and a live progress dashboard.

`MongoDB` `Express` `React` `Node.js` `RBAC`

</td>
</tr>
</table>

---

## 🏗️ How I build RAG (HBL internship, private codebase)

```mermaid
flowchart LR
    A[Internal docs] --> B[Chunking + embeddings]
    B --> C[(FAISS<br/>dense)]
    B --> D[(BM25<br/>keyword)]
    Q[Staff question] --> C & D
    C & D --> E[Hybrid fusion + re-rank]
    E --> F[Local LLM via Ollama]
    F --> G[FastAPI → answer + sources]
```

> Fully on-prem with no data leaving the bank. Moving from plain vector search to hybrid retrieval and tuning the chunking took accuracy from **45% to 80%**.

---

## 🛠️ Tech stack

**AI / LLM**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Backend**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Frontend & tools**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 📊 GitHub activity

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=muhammadkumail1&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=transparent&title_color=00B4D8&icon_color=00B4D8" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=muhammadkumail1&layout=compact&hide_border=true&theme=transparent&title_color=00B4D8&langs_count=6" alt="Top languages" />
  <br/>
  <img src="https://streak-stats.demolab.com?user=muhammadkumail1&hide_border=true&theme=transparent&ring=00B4D8&fire=00B4D8&currStreakLabel=00B4D8" alt="GitHub streak" />
</div>

---

<div align="center">

**Building something with LLMs? Let's talk:** [LinkedIn](https://www.linkedin.com/in/muhammad-kumail1) · [Email](mailto:kumail.muhammad2004@gmail.com)

</div>
