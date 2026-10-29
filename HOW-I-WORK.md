# How I work today

I'm a product-minded software engineer and architect with nearly two decades of experience. I don't write the code anymore: AI agents do. My job is to design the ecosystem where humans and agents work together, and to stay in the loop for every decision that matters.

## How I got here

- **2008–2022 · Building products by hand.** Freelancing, startups (one of them co-founded), interim CTO roles, product teams at scale, technical leadership in large companies. Domain-driven design, XP and TDD, hexagonal architecture: the habits I now ask of agents.
- **2022 · AI in a chat window.** Copy, paste, autocomplete in the editor. The code was still mine.
- **May 2025 · Claude Code.** A few demos at [Nfq](https://nfq.es/) and leadership saw the value fast. Eighteen months since: prompt engineering became context engineering, then agentic engineering, and now it's all about knowledge and loops.
- **2025 · No manual.** There was no paradigm and no proven way to work with agents; trying to write one doctrine for everyone was fencing in the open field. I stopped writing doctrine and started evangelizing: sharing what works with the people who spread it.
- **2026 · Knowledge first.** A versioned knowledge notebook as the source of truth, hooks that enforce the ritual. In my repos, commits co-signed by an agent went from none to 80–95%.
- **2026 · A fleet.** At Nfq, I'm leading a fleet of agents that migrate legacy systems at scale.

## What I believe

**Knowledge is the bedrock; code is disposable.** It gets generated. What deserves care is knowledge, described well and encoded for agents and humans alike, and the gates that keep the system on track. From it you compute the code and the docs, shaped by who is asking.

**There is no theory of everything.** The point of agents is that you shape the tool to your use case instead of bending the case to fit the tool. What transfers is understanding harnesses and models, and architectural intuition: systems thinking, software craftsmanship, now applied for real.

**The harness is most of the result.** The raw model through an API won't give you what you expect: even a chat app is a harness orchestrating models, decisions and tools behind every question. For everyday copilot work, pick a harness you're comfortable with (Claude Code, Codex, OpenCode) and shape it to your use case; you don't need two hundred skills, nor the same ones in every project. Reactive ecosystems are a different thing, and not everyone needs one. But people who work in the same ecosystem share one harness, so they work the same way.

**It's a spectrum.** From vibe coding to agentic engineering, as Google's [The New SDLC With Vibe Coding](https://www.kaggle.com/whitepaper-the-new-SDLC-with-vibe-coding) lays out. A weekend project should stay at the fast end. When something needs to last, knowing where you're heading makes the climb easy: tests, quality gates, automated rules, context tools so agents build it fast and cheap.

**Tools now survive their rewrites.** A wrong technology choice used to kill a tool; you waited for a new one built on the right stack. With agents, migrating the whole thing is within reach: tests as the contract, a harness that ports, humans who fix the process instead of patching the output. Code that passes a full conformance suite is reviewed more strictly than code a human skimmed: don't design the code, design the checkpoints and the rules of the place where the work happens, and the code becomes inferable. [Bun's rewrite in Rust](https://bun.com/blog/bun-in-rust) taught me more about agentic engineering than anything else.

**The gap is the opportunity.** People new to AI lack the intuition of having built software before; people who have it don't yet use the tools well. I sit where both meet, and I work to close the gap, both ways.

## What it looks like

**I design ecosystems that listen.** I don't shovel work into a chat. Meeting transcripts, email, pull requests and events flow to the agents; I define what each signal means, what it should trigger, and what I emit back.

**I talk before I build.** I rarely write a spec. I open the problem, ask the agent to interview me, look at options side by side, and decide with one sentence and a reason.

**I own the language; the agents own the typing.** The domain, the names and the use cases are mine, and I keep correcting them until they fit. Execution is delegated, end to end.

**I trust what I can see.** Screenshots with guides drawn on top, measurements in pixels, the real user trying it live. "It compiles" is not evidence.

**Memory lives in a notebook, not in the agent.** Every project that lasts has a versioned knowledge notebook the agents read before touching anything, checked on every commit. What we learn becomes a rule, a runbook or a skill.

**How much system depends on what's at stake.** Prototypes go fast: we're not launching a rocket. Anything touching real data, money or someone else's eyes goes through gates: dry runs, deterministic checks, and my sign-off on anything that goes out in my name. Most of those gates exist because something broke once.

**Every friction becomes a rule.** When an agent gets something wrong, it doesn't just get fixed: it becomes a rule, a gate or a written decision, with the reason it exists and the condition to retire it. The rigor lives in the process (a commit ritual, independent QA, a human go-ahead for anything that leaves the building) more than in test suites.

**My attention is the bottleneck, so I design for it.** Sessions with names and roles, handoffs between them, a watcher that reconciles the signal, unattended turns that never ask but leave their questions with a default answer. I spend my time on decisions, not on reading logs.

**I fight uncontrolled growth.** Hundreds of tests, ADRs and skills nobody can hold in their head is the failure mode, not the goal. Rules have a budget and get pruned; determinize what you can, cut what won't happen, keep the system small enough to steer.

## Tools and methods

- **Agents**: Claude Code (subagents, skills, hooks, plugins), MCP servers, Claude in the browser.
- **Knowledge**: [OKF](https://github.com/GoogleCloudPlatform/open-knowledge-format) notebooks as the source of truth, beads for work that spans sessions, and the signals the agents listen to: meeting transcripts, email, chat, pull requests, events from the rest of the ecosystem.
- **Deterministic gates**: git hooks, conventional commits, schema and coherence checks on every commit, test suites as contracts, guardrails built into the harness.
- **Judgment gates**: independent QA agents that get the criteria, not the solution; audit and reflection rituals on every commit; and my sign-off on anything that goes out in my name, traced and auditable at any time.
- **Craft**: domain-driven design, use-case driven architecture, hexagonal architecture, XP, systems thinking.
- **Stack for my harnesses**: TypeScript, Python with uv, Cloudflare Workers, Playwright. Beyond that, whatever the job needs: the migration I'm leading runs on Java, Spring Boot and Angular, none of which I had ever used. Agents let me make an impact on stacks I've never worked with.

## Right now

- **[Nfq](https://nfq.es/)** — leading a fleet of agents that migrate legacy systems at scale, and helping the company and its people make the shift to AI-native engineering.
- **[duality.works](https://duality.works)** — an anti-consultancy product studio. Slide decks don't compile.
- **[Bichos.](https://bichos.xyz)** — custom work-chat emojis turned into pixel-perfect 3D desk figures, modelled entirely in code.
