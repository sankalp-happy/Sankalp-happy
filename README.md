<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=24&pause=1600&color=58A6FF&center=true&vCenter=true&width=640&height=45&lines=Sankalp+Shankar;ML+engineer%2C+Bengaluru;LLM+serving+and+the+plumbing+around+it" alt="Sankalp Shankar" />

<p>
<a href="https://sankalpshankar.netlify.app"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=netlify&logoColor=white" alt="Portfolio"></a>
<a href="https://www.linkedin.com/in/sankalp-shankar-734007284/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://leetcode.com/sankalpshankar/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"></a>
<a href="https://github.com/sankalp-happy?tab=followers"><img src="https://img.shields.io/github/followers/sankalp-happy?style=for-the-badge&color=58A6FF&labelColor=0D1117&logo=github&logoColor=white" alt="Followers"></a>
</p>

</div>

Machine learning engineer in Bengaluru, finishing a BE in AI and ML at Acharya Institute of
Technology in 2027.

### Now

Machine learning intern at **Kapture CX**, where I mostly work with LLM based systems.
That sometimes includes but is not limited to model training , post training , fine-tuning and inferenece optimisations.

Before that I freelanced for **Southern Railway**, building a document ingestion pipeline that
distributes RDSO engineering standards and uses ETag revision tracking so it re-fetches a document
only when the document has changed.

### Things I've built

**[switchboard](https://github.com/sankalp-happy/switchboard)** is an LLM gateway. It sits between
your app and Groq, Google, or Anthropic, speaks the OpenAI API so nothing downstream has to change,
caches semantically similar prompts in Redis, and rotates to a fresh key the moment one returns a
429. Keys are encrypted at rest with Fernet, and there are Grafana dashboards for the parts you
only care about at 2am.
[Live](https://switchboard-tau-ruby.vercel.app)

**[PharmaGuard](https://pharmaguard-tbo.netlify.app)** turns a genomic VCF file into prescribing
guidance. PharmCAT and the CPIC rule set make every clinical decision, deterministically. Llama 3.3
is allowed to write the explanation and nothing else, which is the only arrangement I'd trust near
a prescription.

**[MediAssist AI](https://github.com/IAteNoodles/MedAssist)** is RAG clinical decision support with
appointment booking and a doctor dashboard, built on LangChain over a vector store with XGBoost
alongside it.

Also: **Red Agent**, a vulnerability scanner with modular exploit checks (FastAPI, Redis, AWS);
dropout implemented from the paper, forward and backward pass, in NumPy; and hybrid search over
PDFs combining FAISS with TF-IDF because dense retrieval alone kept missing exact terms.

Four hackathon wins so far, plus overall champion at XActitude techfest.

### Stack

Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

Serving and modelling

![vLLM](https://img.shields.io/badge/vLLM-1A1A2E?style=flat-square&logo=lightning&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-4B8BBE?style=flat-square&logo=meta&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

Services and data

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

### A snake is eating last year

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sankalp-happy/Sankalp-happy/output/github-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sankalp-happy/Sankalp-happy/output/github-snake.svg">
    <img alt="snake eating my contribution graph" src="https://raw.githubusercontent.com/sankalp-happy/Sankalp-happy/output/github-snake.svg">
  </picture>
</div>

### The same year, stacked

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile-3d-contrib/profile-night-rainbow.svg">
    <source media="(prefers-color-scheme: light)" srcset="./profile-3d-contrib/profile-season.svg">
    <img alt="3D contribution graph" src="./profile-3d-contrib/profile-season.svg" width="100%">
  </picture>

  <br>

  <img src="https://streak-stats.demolab.com?user=sankalp-happy&theme=github-dark-blue&hide_border=true&border_radius=8&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub streak" />
</div>

<div align="center">
<sub>Both graphs rebuild themselves every night at 18:00 UTC.</sub>
</div>
