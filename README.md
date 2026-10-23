# Hey, I'm Faizan.

**Engineer. Builder. Future founder.**

I work on AI systems, developer tools, backend infrastructure, and whatever else needs to exist to make a product work.

Previously a Forward Deployed Engineer at X-ARC. These days, I'm building my own stuff, getting deeper into systems engineering, and spending an unreasonable amount of time figuring out why AI agents keep doing stupid things.

I like building products. I like understanding what happens underneath them even more.

The first demo is usually the easy part. Getting things to install properly, handle failures, remember context, behave consistently, and actually work for someone other than the person who built them is where things get interesting.

That's the kind of engineering I care about.

[LinkedIn](https://www.linkedin.com/in/faizan-ahamad-khan-32032825b/) | [X / Twitter](https://x.com/tana_shahh) | [Email](mailto:faizan.kk889@gmail.com)

---

## What I've been up to

At **X-ARC**, I worked as a Forward Deployed Engineer.

The title doesn't really explain everything I worked on.

My work covered AI engineering, agent harnesses, backend execution, streaming infrastructure, frontend development, integrations, and UI/UX. Whatever the product needed, I was probably getting my hands dirty with it.

Outside work, I've been building my own projects since late 2025. Some started because I needed a tool. Others started because I thought an existing solution could be better.

A few became proper products. Others are experiments I'm still learning from.

I'm especially interested in agent infrastructure, MCP, local-first software, security, orchestration, and developer experience.

I also care about the business side of software. Understanding users, finding distribution, and figuring out what makes a product worth paying for.

Being able to build something is great. Knowing what deserves to be built is a different skill entirely.

---

## Things I've built

### [LoRe](https://github.com/fayzkk889/lore)

**Coding agents have terrible long-term memory. I'm working on that.**

LoRe is a local-first project memory system for coding agents.

It retrieves relevant conversations, decisions, constraints, and unfinished work from previous coding sessions, with references to the original messages.

Instead of starting every new session by explaining your entire project again, you can ask the agent to recover the context it needs.

The current Windows alpha supports local workflows with Codex and Claude Desktop, using MCP. It's free, with the current release distributed as a closed-source binary.

[Website](https://loredev.co) | [Repository](https://github.com/fayzkk889/lore)

### [MCPSense](https://github.com/fayzkk889/MCPSense)

**Giving an AI agent access to your tools is easy. Figuring out what you're exposing is another story.**

MCPSense is an MIT-licensed security inspection tool for MCP servers and configurations, written primarily in Go.

It examines configurations, source code, agent instructions, and supported live server metadata for suspicious behavior, risky patterns, and security issues.

It includes static analysis, prompt-injection heuristics, advisory checks, baseline comparisons, JSON/SARIF reports, and CI integration.

Available through npm and Go. No Go compiler needed for the npm installation.

It's a scanner, not a magical security guarantee. If a tool can't verify something, it should say so.

[Website](https://mcpsense.site) | [Repository](https://github.com/fayzkk889/MCPSense)

### [House](https://github.com/fayzkk889/house)

**An agent saying "I've fixed the bug" means absolutely nothing to me. Show me the tests.**

House is an autonomous debugging agent written in Go, inspired by differential diagnosis.

It approaches a bug by generating multiple possible explanations, investigating them independently through isolated subagents, comparing the evidence, and applying a minimal fix.

Then it checks whether the failing tests actually pass without introducing regressions.

The implementation includes 52 tools across eight namespaces, subagent orchestration, context compaction, retry handling, and an evaluation harness.

I wanted to explore what happens when you make agents investigate before they start changing code.

[Repository](https://github.com/fayzkk889/house)

### [OpenConvo](https://github.com/fayzkk889/openconvo)

**An AI workspace that doesn't require you to hand over control of everything.**

OpenConvo is an open-source, local-first AI chat workspace.

It supports free hosted models, BYOK, web research, streaming conversations, projects, file context, memory, and data export.

Conversations are stored locally in the browser by default.

Built for people who want a useful AI workspace without being locked into a single model provider.

[Live App](https://openconvo.vercel.app) | [Repository](https://github.com/fayzkk889/openconvo)

### [NanT](https://github.com/fayzkk889/NanT)

**Not an Average NoteTaker.**

I got tired of going back through programming lectures to find one explanation or code example.

NanT is an open-source tool that converts programming tutorials into structured written chapters with explanations, code screenshots, timestamps, and PDF exports.

It combines transcription, visual analysis, source references, and AI-assisted writing.

There's a local workflow and a hosted preview. Still working on accuracy and making the output useful enough to replace the constant rewinding.

[Live Preview](https://nant-sepia.vercel.app) | [Repository](https://github.com/fayzkk889/NanT)

### [P.I. SHIELD](https://github.com/fayzkk889/PI-Shield)

**Web pages weren't designed to be trusted instructions for AI agents. Yet here we are.**

A Chrome extension exploring prompt-injection attacks hidden inside web content.

It looks for suspicious hidden text, Unicode manipulation, HTML attributes, deceptive page structures, and clipboard-based attacks.

Built as a security research project to understand how untrusted content can influence AI systems.

[Repository](https://github.com/fayzkk889/PI-Shield)

### Other projects

- **[Incident Monitoring Platform](https://github.com/fayzkk889/incident-monitoring-platform):** Log ingestion, anomaly detection, AI-assisted incident analysis, and Slack alerts. Go, Python, PostgreSQL, React, Docker.
- **[User Age API](https://github.com/fayzkk889/user-age-api):** GoFiber, PostgreSQL, sqlc, validation, and layered backend architecture.
- **[SourceAsia Backend](https://github.com/fayzkk889/sourceasia-backend):** Go APIs, sliding-window rate limiting, concurrency, and tests.
- **[Credit Card Fraud Detection](https://github.com/fayzkk889/CreditCardFraudDetection):** XGBoost, SMOTE, SHAP, and imbalanced classification.
- **[LinkedIn Data Analytics](https://github.com/fayzkk889/Linkdin-Data-Analytics-Project):** Python, Pandas, Power BI, and job-market analysis.
- **[Expense Tracker](https://github.com/fayzkk889/expense-tracker):** Flask, React, SQLite, validation, and API testing.

I don't work on all of these every day. Some are active products, some are experiments, and some are things I built to learn a particular problem properly.

---

## What I work with

| Area | Technologies |
| --- | --- |
| Languages | Go, Python, JavaScript, TypeScript, C++ |
| Backend | FastAPI, Flask, REST APIs, PostgreSQL, SQLite |
| Frontend | React, Next.js, Tailwind CSS |
| Infrastructure | Docker, Git, GitHub Actions, CI/CD |
| AI Engineering | LLM APIs, MCP, tool calling, agent harnesses, memory, retrieval, multi-agent workflows, evaluations |
| Other | Security, observability, machine learning, system design |

I learn whatever the problem requires.

Right now, I'm particularly focused on getting stronger at Go, JavaScript/TypeScript, algorithms, system design, and the fundamentals behind reliable AI systems.

I want to be able to walk into an unfamiliar codebase, understand how it works, and contribute without needing someone to explain every abstraction to me.

---

## Things I have opinions about

**AI-generated code still needs an engineer.**

Generating a thousand lines is easy. Knowing whether those lines should exist, understanding the failure modes, and proving they work is the actual job.

**A passing demo is not a finished product.**

Installation, error handling, security, test coverage, documentation, and maintenance aren't optional details. They're engineering.

**Not every problem needs five microservices and a distributed message queue.**

Sometimes a well-written Go service and a database are enough. Complexity should earn its place.

**Open source is one of the best ways to learn.**

You get to read real implementations, have your assumptions challenged, and put your work where other engineers can inspect it.

**Distribution matters as much as building.**

You can write excellent software and still have nobody use it. I'm learning how to talk to users, validate problems, explain products, and get them into the right hands.

**I would rather have ten people who genuinely need something I built than ten thousand people liking a launch post.**

---

## What I'm working toward

I'm early in my career, and there's a lot I still need to learn.

I'm also not interested in waiting until somebody decides I'm experienced enough to work on difficult problems.

So I'm building things, studying the fundamentals, contributing to open source, and talking to people who are better at this than I am.

### Near term

I want to work with excellent engineers on serious problems.

Applied AI, AI infrastructure, forward-deployed engineering, backend systems, agent tooling, and developer infrastructure are the areas I'm most interested in.

I'm particularly drawn to small, technically ambitious teams where engineers have real ownership and decisions aren't made through endless layers of approval.

I'm open to globally competitive remote opportunities that support working from India, as well as strong India-based teams.

### Long term

I want to start and build companies.

Not because being a founder sounds impressive, but because I want to own problems from the first customer conversation to the architecture, product, distribution, and business.

I'm interested in software that solves persistent problems. Sometimes that means ambitious AI infrastructure. Sometimes it means a boring workflow tool that quietly makes someone's life easier.

I don't care whether an idea sounds exciting in a pitch deck. I care whether someone actually wants to use it.

I'm also interested in meeting potential co-founders and working with founding teams where I can take meaningful technical ownership.

The eventual goal is simple: have the engineering ability, product judgment, and relationships to build companies that can stand on their own.

---

## Reach out

I'm interested in talking to:

- Founders building ambitious AI, infrastructure, or developer-tooling companies.
- Engineering teams hiring for Applied AI, FDE, backend, agent infrastructure, or developer-tools roles.
- Open-source maintainers who could use another pair of hands.
- Engineers who enjoy getting into the details of how things actually work.
- Potential collaborators and co-founders who have interesting problems worth solving.

If you've got a difficult engineering problem, an interesting product, or something you think I should take a look at, send it over.

**[Email](mailto:faizan.kk889@gmail.com) | [LinkedIn](https://www.linkedin.com/in/faizan-ahamad-khan-32032825b/) | [X](https://x.com/tana_shahh)**

I prefer working code to impressive claims. The repositories are right there. Have a look.
