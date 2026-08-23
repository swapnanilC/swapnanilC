<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=6,11,20&height=200&section=header&text=SWAPNANIL%20CHAKRABORTY&fontSize=36&fontColor=ffffff&fontAlignY=45&desc=Java%20Backend%20Developer%20%7C%20GenAI%20Explorer&descAlignY=68&descSize=18&animation=twinkling" width="100%"/>

</div>

<div align="center">

```
$ whoami
> backend developer, currently rebuilding my foundations in spring boot
> side quest: teaching machines to remember things (RAG) ⚡
```

</div>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3000&pause=800&color=8A2BE2&center=true&vCenter=true&width=800&lines=%F0%9F%8E%AF+Deep-diving+into+Spring+Boot;%E2%9A%99%EF%B8%8F+Learning+Microservices+%26+Distributed+Systems;%F0%9F%A7%A0+Shipping+RAG-powered+GenAI+apps;%F0%9F%94%8E+Nerding+out+on+Vector+%26+Graph+Search" alt="rotating text"/>
</p>

<p align="center">
  <a href="https://github.com/swapnanilC"><img alt="GitHub" src="https://img.shields.io/badge/-swapnanilC-181717?style=flat-square&logo=github&logoColor=white"/></a>
  <a href="mailto:YOUR-EMAIL@example.com"><img alt="Email" src="https://img.shields.io/badge/-Reach%20Out-8A2BE2?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://linkedin.com/in/YOUR-LINKEDIN"><img alt="LinkedIn" src="https://img.shields.io/badge/-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <img alt="Profile Views" src="https://komarev.com/ghpvc/?username=swapnanilC&style=flat-square&color=8A2BE2&label=views"/>
</p>

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" height="2px"/>
</div>

<br/>

## `01.` The Gist

<table>
<tr>
<td width="60%" valign="top">

I'm building my career around **Java backend engineering** — right now that means going deep on **Spring Boot** and rounding out the pieces around it: databases, APIs, and the architecture patterns that hold real systems together.

Alongside that, I've been pulled into the **GenAI / RAG** world through a project of my own — turning past conversations into something an LLM can actually search and reason over. That project cracked open a whole side interest in embeddings, vector search, and how retrieval and generation fit together.

So the current split looks like:

- 🏗️ **~70% backend fundamentals** — Spring Boot, microservices, databases, event-driven systems
- 🧠 **~30% GenAI exploration** — RAG pipelines, embeddings, semantic search

</td>
<td width="40%" align="center">
  <img src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif" width="100%"/>
</td>
</tr>
</table>

<br/>

## `02.` Stack

<table>
<tr>
<td valign="top" width="50%">

**Core & Backend**
<br/>
<img src="https://skillicons.dev/icons?i=java,spring,postgres,git,github,maven" />

**Exploring next**
<br/>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,kafka" />

</td>
<td valign="top" width="50%">

**GenAI / LLM Tooling**
<br/>
<img src="https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain4j-000000?style=flat-square"/>
<img src="https://img.shields.io/badge/pgvector-336791?style=flat-square"/>

**Concepts I'm working through**
<br/>
`RAG` `Embeddings` `Vector Search` `Neo4j / Graph Modeling` `Semantic Retrieval`

</td>
</tr>
</table>

> Badges above are a snapshot of where my hands are dirty right now, not a resume of mastery — I'm early on several of these and that's kind of the point of this README.

<br/>

## `03.` Featured Build — Talk-To-Past-Self

<div align="center">
  <h3>🧠 <a href="https://github.com/swapnanilC/Talk-To-Past-Self">Talk-To-Past-Self</a></h3>
  <i>A RAG-based GenAI app that lets you have a conversation with your own conversation history.</i>
  <br/><br/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangChain4j-000000?style=flat-square"/>
  <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square"/>
</div>

<br/>

```
┌──────────────┐     ┌────────────────────┐     ┌───────────────────────┐
│ User Question│ ──► │ Generate Embedding │ ──► │ Vector Similarity     │
└──────────────┘     └────────────────────┘     │ Search (pgvector)     │
                                                  └──────────┬────────────┘
                                                             ▼
┌──────────────────────┐     ┌───────────────┐     ┌────────────────────┐
│ Context-Aware Answer │ ◄── │ Google Gemini │ ◄── │ Build Context from │
└──────────────────────┘     └───────────────┘     │ Retrieved History   │
                                                     └────────────────────┘
```

**What it does:**
- Stores conversation history in PostgreSQL, indexed by timestamp
- Embeds queries with Gemini and runs semantic similarity search via pgvector
- Assembles retrieved context and feeds it back to Gemini for a grounded, context-aware reply
- End to end, it's a working RAG loop — not just a wrapper around an API call

<div align="center">
  <a href="https://github.com/swapnanilC/Talk-To-Past-Self">
    <img src="https://img.shields.io/badge/Explore%20the%20Repo-8A2BE2?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</div>

<br/>

## `04.` Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=swapnanilC&show_icons=true&hide_border=true&theme=radical&count_private=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=swapnanilC&layout=compact&hide_border=true&theme=radical" height="165"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=swapnanilC&hide_border=true&theme=radical"/>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=swapnanilC&theme=react-dark&hide_border=true" width="90%"/>
</div>

<br/>

## `05.` What's Next

- [x] Get comfortable with Java & core Spring Boot
- [ ] Go deeper on Spring Boot + PostgreSQL patterns (currently here)
- [ ] Learn microservices architecture properly — service boundaries, API gateways, service-to-service comms
- [ ] Get hands-on with Kafka & event-driven design
- [ ] Solidify Docker & Kubernetes basics
- [ ] Push the GenAI side further — more advanced RAG, graph-based retrieval with Neo4j
- [ ] Ship a production-grade AI-powered backend project end to end

<br/>

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" height="2px"/>
</div>

<p align="center"><i>Always happy to talk backend architecture or GenAI experiments — feel free to reach out. ⭐</i></p>

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
