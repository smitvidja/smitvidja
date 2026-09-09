<div align="center">

# Smit Vidja

**AI/ML Engineer — Ahmedabad, India**

</div>

I build AI systems that go all the way to production — not notebooks, not demos. Cyber Rakshak is live. My last role cut deployment time from hours to minutes. When I'm not shipping, I'm designing the next system I want to build — properly, on paper, before touching code.

📫 **smitvidja.work@gmail.com** · [LinkedIn](https://www.linkedin.com/in/smit-vidja-84-/) · Open to AI/LLM engineering roles — remote or Bangalore

**Currently:** finishing Cyber Rakshak → then building HireWise-AI.

---

## Shipped

### 🛡️ [Cyber Rakshak](https://github.com/smitvidja/CyberRakshak) — 80% built, deployed

A citizen files a cybercrime complaint by *talking* — in Hindi, Hinglish, or English — and the system handles the rest: understanding intent, pulling out the right details, building the case, routing it correctly. Most government-adjacent tools make people fill forms in a language and format that isn't theirs. This one doesn't.

- NLP pipeline for Hindi/Hinglish/English — intent classification, entity extraction
- RAG-backed LLM orchestration layer for grounded, accurate responses
- Full voice interface: speech in → LLM reasoning → speech out
- Anonymous and identified reporting flows
- "Cyber Warrior" layer — community responders assist in real cases

`Python` `FastAPI` `LangChain` `RAG` `spaCy` `STT/TTS` `Docker` `AWS`

---

## Building Next

### 🎯 HireWise-AI — architecture complete, build starting after Cyber Rakshak

Most AI hiring tools are a black box that spits out a score nobody can defend. HireWise is built the opposite way: **65% of the score is deterministic** — skill overlap, experience match, semantic similarity — fully reproducible and auditable. The remaining 35% is an LLM layer that reads for resume authenticity across 6 dimensions. If the LLM call fails, it defaults to neutral and the system keeps working. It never goes down because a model provider had a bad day.

`FastAPI` `PostgreSQL` `pgvector` `Next.js 14` `TypeScript` `Claude API`

---

## Design Lab

I spend real time defining problems before I let myself write code. These two haven't been built yet — they're rigorous product thinking exercises: problem definition, technical feasibility, architecture. I'm including them because the reasoning is real, even if the code isn't yet.

<details>
<summary><b>⚖️ RegIQ — Regulatory Intelligence for Indian legal & compliance teams</b></summary>
<br>

**The actual problem, stated precisely:** it's not that lawyers and compliance teams can't find information — it's that Indian regulatory data isn't a clean corpus. It's fragmented across SEBI, RBI, MCA, and NCLT PDFs, inconsistently OCR'd, with amendment chains that exist nowhere as machine-readable data. Answering "what was SARFAESI Section 13(2) applicable to on 14 March 2019?" requires reconstructing legal state over time — a knowledge representation problem, not a search problem.

**What I designed:**
- Corpus construction as Product 0 — before any AI feature can work, the data has to exist in usable form
- Temporal state reconstruction engine
- Authority graph: statute → rule → circular → case law
- Source-grounded RAG with citation-level traceability

**Chosen wedge:** SARFAESI/DRT recovery research — smallest source surface, clearest buyer, real financial stakes per decision.

*Status: problem definition complete (v1.0). Feasibility research before any build.*

</details>

<details>
<summary><b>🏢 WorkKin — AI coworkers that finish work, not just answer questions</b></summary>
<br>

**The gap I noticed:** automation is great when the steps are already known. Most real work isn't — it's "figure this out," then research, write, coordinate, revise, and confirm it actually happened. AI assistants stop at the answer. WorkKin doesn't stop until the outcome is verified.

**What I designed:**
- Durable workflow state (Temporal) — independent of any single model call, so failures recover instead of restarting from zero
- A 2D visual workplace where agents have visible state — not a UI flourish, the actual product surface
- Behavioral identity layer — agents have consistent tone and personality, separate from their permissions
- Explicit provenance: a remixed workflow is never confused with a validated one

**V1 scope:** Revenue & Lead Operations (commercial anchor) + Exception → Resolution (proves the platform is more than an outreach tool).

*Status: full product, business, and technical blueprint complete (v5). Sequenced after HireWise.*

</details>

---

## Experience

**AI/ML Engineer, ATRI Systems** (Apr–Jul 2025)
Built 70+ automated tests (250% coverage increase, 80% less manual testing). Owned the AWS CI/CD pipeline (Docker → ECR → EC2), cutting deploy time from hours to minutes.

**AI/ML Intern, Rashtriya Raksha University** (May–Dec 2024)
Real-time traffic surveillance system — 95%+ accuracy, 30+ FPS, multi-modal detection (vehicles, helmets, ANPR). Tuned YOLOv8 for a 40% performance gain.

**AI/ML Intern, Addealindia** (Jan–Apr 2024)
NLP models for classification, sentiment, and toxicity detection (88%+ accuracy). Prototyped a full ASR → MT → TTS speech translation pipeline.

---

## Recognition

🥈 2nd place, NSG DIGIRakshak National Hackathon (213+ teams) — defense-grade surveillance drone system
🎯 Top 50 nationwide, National Entrepreneurship Challenge
🌊 Smart India Hackathon — coastal monitoring drone with real-time sensor integration

---

## Stack

**ML/AI:** PyTorch · YOLOv8 · OpenCV · scikit-learn · spaCy · NLTK · LangChain · RAG · LLM orchestration
**Backend:** FastAPI · PostgreSQL · SQLAlchemy · pgvector · Redis
**Frontend:** Next.js · React · TypeScript · TailwindCSS
**Infra:** Docker · AWS (EC2/ECR) · CI/CD · Temporal
**Testing:** Playwright · PyTest

---

<div align="center">

If you're building something real with AI, I'd like to hear about it — **smitvidja.work@gmail.com**

</div>
