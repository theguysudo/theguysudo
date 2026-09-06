
solo dev, wandered into the matrix, never found my way back out...

<img width="480" height="268" alt="ngoding-mulu" src="https://github.com/user-attachments/assets/5fdc4e4b-e3b3-4fbc-b545-5ba470ce6143" />

it's just me, a terminal, and a codebase full of things I'd rather not explain to the police  
break it, rebuild it, convince myself it was on purpose the whole time  
that's the entire SDLC  
status is always "shipping."  
regrets are always 0, mostly because I stopped counting around commit #47 and never looked back  
if it works, I built that  
if it doesn't, it's a feature I haven't documented yet or evidence, depending who's asking

---

## what I am actually shipping

### [ENZO](https://github.com/theguysudo/ENZO) — self-hosted BYOK AI workspace
chat, agents, and skills (Gmail, Google Calendar, web search, project generation) running entirely on **your own provider API keys** — no subscription, no middleman.

- keys sealed client-side with AES-256-GCM — the server never sees them
- one-command Docker deployment: `ghcr.io/theguysudo/enzo`
- agents with scheduled runs + a custom agent builder that drafts an agent from a plain-language task description
- Apache-2.0

**live demo:** https://enzo-hub.duckdns.org
