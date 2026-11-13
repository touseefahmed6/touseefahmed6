## Hi, I'm Touseef 👋

I'm a full stack developer at AtomPoint in Karachi. Most of my work is putting AI into real products: an MCP server and WhatsApp agent for a legal platform, a real-time voice agent, an AI inbox, and the backends that keep them reliable.

I started at AtomPoint as an intern in May 2024 and have been shipping production apps there since, alongside finishing my Software Engineering degree in 2025.

[![Portfolio](https://img.shields.io/badge/Portfolio-touseef--ahmed.vercel.app-000000?style=flat&logo=vercel&logoColor=white)](https://touseef-ahmed.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Touseef_Ahmed-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/touseef-ahmed-4394ba260)

### Work I'm proud of

Most of this is company and client work, so the code is private. The products are live, so you can try them.

<table>
<tr>
<td width="50%" valign="top">
<a href="https://www.wakeel.ai/"><img src="assets/wakeel-ai.webp" alt="Wakeel AI" /></a>
<h4><a href="https://www.wakeel.ai/">Wakeel AI</a>, legal case management</h4>
<sub>MCP · Gemini · WhatsApp · Google Cloud Run · Next.js</sub>
<ul>
<li>MCP server with OAuth so lawyers can work with their case data from ChatGPT and Claude</li>
<li>One shared AI tool layer for ChatGPT, Claude and WhatsApp: every write needs confirmation, each firm sees only its own data, every AI change is logged</li>
<li>WhatsApp agent on Gemini that understands voice notes and replies in the user's language</li>
<li>Moved production from Heroku to Cloud Run with zero data loss</li>
</ul>
</td>
<td width="50%" valign="top">
<a href="https://setup.speakto.site/"><img src="assets/speakto.webp" alt="SpeakTo" /></a>
<h4><a href="https://setup.speakto.site/">SpeakTo</a>, real-time voice agent</h4>
<sub>Gemini Live API · Next.js · Express + WebSockets · Firecrawl · Expo</sub>
<ul>
<li>Talks to website visitors in real time and answers from the site's own pages</li>
<li>Moves the visitor around the site and highlights things on the page while it talks</li>
<li>Rebuilt audio playback as a continuous 24 kHz audio worklet to fix broken-up audio</li>
<li>Hands off to a human via Chatwoot or WhatsApp, with Stripe billing and a mobile app</li>
</ul>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://hub.trysimpl.ai/"><img src="assets/email-manager.webp" alt="Simpl AI Email Manager" /></a>
<h4><a href="https://hub.trysimpl.ai/">Simpl</a>, AI email manager</h4>
<sub>Node.js · Cloud Functions · MongoDB · GPT-5.1 · Gemini · Langfuse</sub>
<ul>
<li>Sorts incoming Gmail and Outlook mail and writes draft replies</li>
<li>Rules run before the AI is called, which cuts LLM cost</li>
<li>Langfuse tracing and a cost calculator on every LLM call</li>
<li>Stripe subscriptions, encryption and unit tests</li>
</ul>
</td>
<td width="50%" valign="top">
<a href="https://www.gradientai.co.uk/"><img src="assets/gradient-ai.webp" alt="Gradient AI" /></a>
<h4><a href="https://www.gradientai.co.uk/">Gradient AI</a>, education analytics</h4>
<sub>NestJS · Prisma · PostgreSQL · BullMQ · Gemini · Next.js</sub>
<ul>
<li>Gemini pulls topics out of exam papers, with every result checked and retried if wrong</li>
<li>Mark analysis engine that finds weak topics and at-risk students</li>
<li>Row-level security, BullMQ queues, Stripe billing, audit logs, 81 unit tests and CI</li>
</ul>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="assets/hr-automation.webp" alt="HR Slack bot" />
<h4>HR Slack bot</h4>
<sub>Node.js · Slack API · Cloud Functions · OpenAI</sub>
<ul>
<li>Leave, work from home and approval flows inside Slack</li>
<li>Monthly attendance reports for a 30-person company</li>
<li>Unlocks the office gate from Slack</li>
</ul>
</td>
<td width="50%" valign="top">
<img src="assets/social-generator.webp" alt="AI social image generator" />
<h4>AI social image generator</h4>
<sub>Next.js · Gemini · OpenAI · Firecrawl</sub>
<ul>
<li>Pulls a brand's look from any URL and makes a 5-slide carousel</li>
<li>AI paints only the background, then the real fonts, colours and logo go on top, so it looks professional</li>
</ul>
</td>
</tr>
</table>

### More work

- **Alsahm**, investing platform for the Oman stock exchange. One NestJS API serves the website, the Expo mobile app and the admin panel, in English and Arabic. Paper trading, a trading competition, watchlists, price alerts and live market data.
- **WhatsApp sales layer.** Self-hosted Evolution API connected to Chatwoot, with rules for routing each conversation to a salesperson, a sales panel, and tracking which ad each lead and sale came from.
- **[Backstage](https://stage-fe--backstage-solutions-us.us-central1.hosted.app/en/home)**, English and Arabic talent marketplace with AI job matching.
- **[Timegram](https://www.timegram.io/)**, time tracking and team capacity platform for remote teams.
- **Client websites in Next.js:** THK (with Strapi CMS), Lakewise, [Steelink](https://steelink.com.pk/) and the AtomPoint AI agents site.

### Open source

**[Dograh](https://github.com/dograh-hq/dograh)**, an open-source voice AI platform built on Pipecat. Five merged features in its embed widget: `onTranscript`, `onToolCall`, `sendText`, `updateContext`, and choosing a text-to-speech voice per session.

### What I work with

**Languages:**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**Frontend & mobile:**
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat&logo=expo&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Backend & data:**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-E0234E?style=flat)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat&logo=stripe&logoColor=white)

**AI:**
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logo=modelcontextprotocol&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=flat)
![Firecrawl](https://img.shields.io/badge/Firecrawl-FF6B00?style=flat)

**Automation & messaging:**
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Chatwoot](https://img.shields.io/badge/Chatwoot-1F93FF?style=flat&logo=chatwoot&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white)
![Slack API](https://img.shields.io/badge/Slack_API-4A154B?style=flat&logo=slack&logoColor=white)

**Cloud & tools:**
![Google Cloud Run](https://img.shields.io/badge/Cloud_Run-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Cloud Tasks](https://img.shields.io/badge/Cloud_Tasks-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

### What people I work with say

> "He understands requirements quickly, asks the right questions, and takes ownership of his work instead of just completing tasks for the sake of it."
>
> **Rai Muhammad Rafay**, Technical Project Manager, AtomPoint

---

<sub>On GitHub since 2023 · 1,400+ contributions, most of them in private company repos.</sub>
