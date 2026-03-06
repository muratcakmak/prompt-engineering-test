# Prompt & Agentic Engineering Masterclass

**A free, interactive 8-hour curriculum for mastering prompt engineering and agentic AI — from zero to production-ready.**

🔗 **Live:** [docs.omc345.com/prompt-engineering-eval.html](https://docs.omc345.com/prompt-engineering-eval.html)

---

## What is this?

A single-file HTML guide built as a Docusaurus-style interactive learning experience. It covers everything from the mental model of how LLMs think, through to building multi-agent production systems — with hands-on exercises powered by live LLM evaluation via OpenRouter.

No installation. No dependencies. Open the HTML file in any browser and start learning.

---

## Curriculum

### Hour 1 · Foundation — How LLMs Actually Think
Build the mental model that separates professionals from amateurs.
- The Core Mental Model
- Anatomy of a Perfect Prompt
- The Clarity Hierarchy
- Temperature, Tokens & Model Selection

### Hour 2 · Core Techniques — Zero-Shot, Few-Shot & Role Prompting
The 20% of techniques that gets 80% of your results.
- Zero-Shot Prompting
- Few-Shot Prompting
- Output Style Modeling — ✅ / ❌ Explicit Examples
- Role Prompting & Persona Engineering
- Instruction Formatting Techniques

### Hour 3 · Reasoning Techniques — Chain-of-Thought, Tree-of-Thought & Self-Consistency
Force the model to reason like your smartest colleague.
- Chain-of-Thought (CoT) Prompting
- Tree-of-Thought (ToT)
- Self-Consistency
- Reflexion & Self-Critique

### Hour 4 · Advanced Techniques — ReAct, Structured Output & Meta-Prompting
The techniques that bridge prompt engineering to agentic AI.
- ReAct: Reasoning + Acting
- Structured Output Prompting
- Meta-Prompting: Prompting the Prompt
- Prompt Chaining

### Hour 5 · Agentic Engineering — Agent Anatomy & Architecture Patterns
Build autonomous systems that plan, act, and adapt.
- The Four Core Components of Any Agent
- The 6 Core Agentic Patterns

### Hour 6 · Multi-Agent Systems — Orchestrators, Subagents & Agent Networks
The architecture behind production-scale AI systems.
- Why Multi-Agent?
- The Orchestrator System Prompt
- Handoff Protocols & Agent Communication
- The 5 Multi-Agent Architectures
- Error Handling & Graceful Degradation

### Hour 7 · Context Engineering — Mastering the Context Window
The skill that separates good agentic engineers from great ones.
- Context Rot & Attention Budget
- System Prompt Architecture
- Dynamic Context Strategies
- Token Optimization Tactics

### Hour 8 · Production Mastery — Evaluation, Safety & Becoming the Best
The practices that separate hobbyists from world-class engineers.
- Evaluating Prompts Like a Pro
- Debugging Failing Prompts
- Safety & Reliability in Agentic Systems
- The Iterative Engineering Process
- The King-Level Toolkit

### ★ Bonus · Reddit Intelligence — What the Community Actually Uses in 2025
Distilled from 15 top posts and 2,500+ upvotes — field-tested techniques from practitioners.
- ★.1 The KERNEL Framework *(2,526 upvotes)*
- ★.2 GACF Framework
- ★.3 Ask the Model to Ask YOU First
- ★.4 Generate-Knowledge (GK) Prompting
- ★.5 Cross-LLM Voting & Ensemble Prompting
- ★.6 Model-Specific Markup
- ★.7 Prompt Version Control & CI
- ★.8 Temperature as a Debug Tool
- ★.9 CoT Caveat — When NOT to Use It
- ★.10 Motivational & Reward-Structure Prompts

---

## Interactive Labs

Every exercise has a live **⚡ Interactive Lab** powered by OpenRouter. Connect your API key once and all 9 exercise labs unlock instantly.

**How it works:**
1. Click **⚡ Connect LLM** in the top header
2. Paste your [OpenRouter API key](https://openrouter.ai/keys) (free to get)
3. Write your prompt in the lab textarea
4. Hit **▶ Run Prompt** — real model response appears inline
5. Hit **🎯 Evaluate My Prompt** — Claude grades your prompt on 5 exercise-specific criteria with color-coded scores, written feedback, and a single top improvement tip

**Supported models:**
| Model | Provider | Notes |
|---|---|---|
| Grok 4 Fast ⚡ | xAI | Default |
| Grok 4.1 Fast 🔥 | xAI | Best for agentic tasks |
| Grok 4 | xAI | Full reasoning |
| Gemini 2.0 Flash | Google | Fast & cheap |
| DeepSeek V3 | DeepSeek | Budget pick |
| GPT-4o mini | OpenAI | — |
| Claude 3.5 Sonnet | Anthropic | — |
| GPT-4o | OpenAI | — |
| Llama 3.3 70B | Meta | Free tier |

> Your API key is stored only in memory and never transmitted anywhere except OpenRouter.

---

## Features

- **Docusaurus-style sidebar** — fixed left nav with collapsible sections, active section tracking as you scroll, sub-section links for every topic
- **43 subsections** across 9 modules
- **9 interactive exercises** with live LLM execution and AI-graded evaluation
- **Prompt templates** with syntax-highlighted role / instruction / context / output blocks
- **Do's & Don'ts** with real ✅ / ❌ side-by-side examples for key techniques
- **Searchable** — filter any topic from the header search bar
- **Progress tracking** — module completion counter in the sidebar
- **Mobile responsive** — hamburger menu on small screens
- **Zero dependencies** — single HTML file, works offline (exercises require internet)

---

## Usage

### Option A — Use the live hosted version
Visit [docs.omc345.com/prompt-engineering-eval.html](https://docs.omc345.com/prompt-engineering-eval.html)

### Option B — Run locally
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
open prompt-engineering-eval.html   # macOS
# or just double-click the file in any OS
```

No server needed. No `npm install`. No build step.

---

## Stack

Pure HTML + CSS + Vanilla JS. No frameworks, no build tools, no external dependencies loaded at runtime (except the OpenRouter API calls when labs are active).

---

Built by **Oguzhan Murat Cakmak**. Reach out him on [x/twitter](https://x.com/omc345).
