# Claude SEO, GEO & AEO Audit Skill

> **AI-powered SEO, GEO & AEO audits inside Claude — from URL to professional downloadable report in minutes.**

🌐 **Live site:** [claudeseoskill.netlify.app](https://claudeseoskill.netlify.app/)

Built by [Nthabeleng Aeden Manell](https://www.linkedin.com/in/aeden-manell/) · Powered by [Anthropic](https://anthropic.com) · Inspired by the original skill by [Alex Labat](https://github.com/alexlabat)

---

## Table of Contents

- [Overview](#overview)
- [What Makes This Different](#what-makes-this-different)
- [The Three Layers of Modern Search](#the-three-layers-of-modern-search)
- [Features](#features)
- [Audit Types](#audit-types)
- [Quick vs Full Audit](#quick-vs-full-audit)
- [How It Works](#how-it-works)
- [Installation](#installation)
- [Usage](#usage)
- [Report Output](#report-output)
- [Requirements](#requirements)
- [Scoring System](#scoring-system)
- [FAQ](#faq)
- [Credits & Acknowledgements](#credits--acknowledgements)
- [License](#license)
- [Connect](#connect)

---

## Overview

The **Claude SEO, GEO & AEO Audit Skill** is a free, open-source Claude AI Skill that performs comprehensive, multi-page website audits across three interconnected optimization disciplines:

- **SEO** — Search Engine Optimization for Google & Bing
- **GEO** — Generative Engine Optimization for AI search (Claude, ChatGPT, Perplexity, Gemini)
- **AEO** — Answer Engine Optimization for featured snippets, AI Overviews, and voice search

In 2026, the search landscape has fundamentally changed. Ranking on a page of blue links is no longer enough. AI search engines now generate answers, cite sources, and guide users through entire journeys without a single click. This skill ensures your website is optimized for all three layers of that new reality.

Paste a URL. Claude crawls your entire site — homepage, About, Services, Blog, Case Studies, FAQ, Contact and more — scores every dimension from 1–10, and auto-generates a polished agency-quality DOCX + PDF report you can share immediately.

---

## What Makes This Different

Most SEO tools — Ahrefs, Semrush, Screaming Frog — are built for the old search paradigm. They track backlinks and keyword rankings. They do not tell you:

- Whether an AI system like ChatGPT would cite your content
- Whether your FAQ page is structured for voice search
- Whether your schema markup qualifies you for Google's AI Overviews
- Whether your E-E-A-T signals are strong enough for generative retrieval

This skill audits all three layers simultaneously, produces a unified score, and delivers a single report with prioritized, actionable findings — all inside a Claude conversation, at zero cost.

---

## The Three Layers of Modern Search

### Layer 1 — SEO (Search Engine Optimization)

**Goal:** Rank on the first page of Google and Bing.

Traditional SEO remains the foundation. Without strong technical health, no other optimization layer can perform effectively. This audit covers crawlability, indexation, title and meta tags, heading hierarchy, internal linking, image alt text, canonical tags, page speed signals, and E-E-A-T indicators.

### Layer 2 — GEO (Generative Engine Optimization)

**Goal:** Be cited or recommended by AI search systems.

GEO is the discipline of making your content trusted and citable by large language models and generative retrieval systems. When a user asks Claude, ChatGPT, or Perplexity a question, GEO determines whether your brand is referenced in the generated answer. Key signals include source credibility, semantic richness, entity clarity, factual robustness, and content authority.

### Layer 3 — AEO (Answer Engine Optimization)

**Goal:** Be the direct answer — above all organic results.

AEO targets zero-click real estate: Google's AI Overviews, featured snippets, People Also Ask boxes, and voice search results. It requires structuring content around specific question-answer pairs, implementing FAQ and HowTo schema, using conversational phrasing, and keeping answers concise and self-contained.

---

## Features

| Feature | Description |
|---|---|
| **Multi-Page Site Crawl** | Crawls homepage, robots.txt, sitemap.xml, and all key internal pages |
| **SEO Audit** | Full technical and on-page analysis with scored findings |
| **GEO Audit** | AI citation readiness, E-E-A-T, entity clarity, and authority scoring |
| **AEO Audit** | Featured snippet, voice search, and schema structure scoring |
| **Structured Data Review** | JSON-LD validation and missing schema recommendations |
| **Content Quality Analysis** | Readability, topical depth, keyword density, and intent alignment |
| **Priority Matrix** | Findings ranked Critical → High → Medium → Quick Win |
| **DOCX Report** | Agency-quality Word document with cover page and full findings |
| **PDF Report** | Identical report auto-generated as a PDF |
| **Quick Audit Mode** | 1–2 minute scan of top 7 high-signal pages |
| **Full Audit Mode** | 5–10 minute comprehensive crawl with no page cap |
| **Chat Recap** | Instant score table and top 3 priorities in the conversation |
| **Free & Open Source** | No subscription, no API key beyond Claude access required |

---

## Audit Types

### SEO Audit

Deep technical and on-page analysis covering:

- Title tag length, uniqueness, and keyword presence
- Meta description optimization and click-through appeal
- Heading hierarchy (H1–H6) structure and keyword usage
- Internal linking depth and anchor text quality
- Canonical tag implementation and duplicate content signals
- Image alt text coverage and descriptive quality
- robots.txt and sitemap.xml health
- Core Web Vitals signals (LCP, CLS, FID indicators)
- Mobile-friendliness signals
- HTTPS and security signals
- E-E-A-T indicators (author bios, About page depth, citations)

### GEO Audit

Generative Engine Optimization covering:

- Source credibility and trustworthiness signals
- Citation-worthy content formatting (facts, statistics, original data)
- Entity clarity — is your brand, location, and niche clearly defined?
- E-E-A-T depth assessment (Experience, Expertise, Authoritativeness, Trust)
- AI-snippet readiness — is content structured for LLM extraction?
- Content authority signals — external links, author credentials, publications
- Semantic richness and topic coverage breadth
- Factual density and verifiability

### AEO Audit

Answer Engine Optimization covering:

- Question-answer content structure
- Featured snippet format suitability (paragraph, list, table)
- FAQPage and HowTo schema implementation
- Conversational query phrase matching
- Voice search phrasing and sentence length
- Concise answer density — does the page lead with a direct answer?
- People Also Ask opportunity identification
- AI Overview eligibility signals

### Structured Data Review

- JSON-LD presence and syntax validation
- Rich result eligibility (Articles, FAQs, Products, Events, Breadcrumbs, Reviews)
- Missing schema type recommendations
- Schema.org property completeness
- Nested schema accuracy

### Content Quality Analysis

- Flesch-Kincaid readability scoring
- Topical coverage gaps relative to search intent
- Keyword density and semantic keyword usage
- Primary search intent alignment (informational, navigational, transactional)
- Content depth relative to competing pages
- Unique value proposition clarity

---

## Quick vs Full Audit

| | Quick Audit | Full Audit |
|---|---|---|
| **Duration** | 1–2 minutes | 5–10 minutes |
| **Pages crawled** | Up to 7 high-signal pages | Every meaningful page (no cap) |
| **Scoring** | SEO, GEO, AEO scored 1–10 | SEO, GEO, AEO scored 1–10 |
| **Chat recap** | Yes | Yes |
| **DOCX report** | Yes | Yes |
| **PDF report** | Yes | Yes |
| **Priority matrix** | Condensed | Full (Critical → Quick Win) |
| **Best for** | Fast health checks, client previews | Full audits, before/after comparisons |

---

## How It Works

### Step 1 — Download & Install the Skill

Download the skill ZIP from this repository. Add it to Claude by placing it in your Claude skills directory or importing it via the Claude interface. The skill will be available in any Claude conversation immediately after installation.

### Step 2 — Invoke the Skill

Open a Claude conversation and invoke the SEO skill. Claude will ask one clarifying question — whether you want a Quick Audit or Full Audit — before proceeding. This question is asked every time, without exception, to ensure the right depth of analysis.

### Step 3 — Paste Your URL

Provide the URL of the website you want audited. You can supply:

- A homepage URL — Claude will discover and crawl internal pages automatically
- A specific page URL — Claude will audit that page plus related internal pages
- A domain only — Claude will resolve to the homepage and proceed

### Step 4 — Claude Crawls the Site

Claude fetches your homepage, robots.txt, and sitemap.xml in parallel. It builds a complete map of your site's internal structure, then systematically crawls:

- Homepage
- About page
- Services or Products pages
- Blog or News index and individual posts
- Case Studies or Portfolio pages
- FAQ page
- Contact page
- Any additional pages discovered via the sitemap

All findings are held until the full crawl is complete. Claude does not draw conclusions from the homepage alone.

### Step 5 — Receive Your Chat Recap

Within the conversation, Claude delivers:

- A score table showing SEO, GEO, and AEO each rated 1–10
- Your top 3 most impactful improvements, named specifically
- Your biggest current strength
- A brief executive summary readable in under one minute

### Step 6 — Download Your Report

Immediately after the chat recap, Claude auto-generates:

- A **DOCX report** — a full agency-quality Word document
- A **PDF report** — identical content, PDF format

Both are delivered in the conversation and ready to share with clients, stakeholders, or your development team.

---

## Installation

### Prerequisites

- Access to Claude (Claude.ai free tier, Claude Pro, or Anthropic API)
- Claude desktop app or web interface that supports Skills

### Install the Skill

**Option A — Claude Desktop App**

1. Download or clone this repository
2. Open the Claude desktop app
3. Navigate to Settings → Skills
4. Click "Add Skill" and select the skill folder from this repository
5. The skill will appear as available in all future conversations

**Option B — Manual Installation**

1. Download the skill ZIP from the [Releases](https://github.com/nthabelengaedenmanell/SEO-GEO-AEO-Audit-Skill-for-Claude/tree/main) page
2. Extract the ZIP to your Claude skills directory
3. Restart the Claude app if required
4. The skill will be available in your next conversation

**Option C — Clone the Repository**

```bash
git clone https://github.com/nthabelengaedenmanell/SEO-GEO-AEO-Audit-Skill-for-Claude.git
```

Then follow the installation steps for your Claude interface.

---

## Usage

### Basic Usage

Once the skill is installed, open Claude and invoke the SEO skill:

```
Run a Full Audit on https://yourwebsite.com
```

or simply:

```
Audit my site: https://yourwebsite.com
```

Claude will ask whether you want a Quick or Full Audit, then proceed automatically.

### Example Prompts

```
Perform a Quick SEO audit on https://example.com

Do a full SEO, GEO and AEO audit of https://mybusiness.com

Audit https://agency.com/services — focus on GEO and AEO

Run a complete site audit on https://ecommerce.com and give me the full report
```

### Interpreting the Chat Recap

The chat recap will always include:

```
SEO Score:  8/10
GEO Score:  6/10
AEO Score:  5/10

Top 3 Priorities:
1. [Specific finding #1]
2. [Specific finding #2]
3. [Specific finding #3]

Biggest Strength: [What your site does best]
```

Scores are calculated based on the total number of signals checked versus the number passing. A score of 7/10 or above is considered healthy. Scores below 5/10 indicate significant gaps requiring immediate attention.

---

## Report Output

### DOCX Report Structure

Every Full Audit generates a Word document containing:

1. **Cover Page** — Site name, audit date, scores at a glance, and branding
2. **Executive Summary** — 2–3 paragraph overview of overall site health and strategic priorities
3. **Score Dashboard** — Visual SEO / GEO / AEO score cards with context
4. **Pages Audited Log** — Full list of all pages crawled during the audit
5. **Signal-by-Signal Findings Table** — Every signal checked, its status (Pass / Fail / Warning), and a brief explanation
6. **Priority Matrix** — Findings ranked by impact: Critical → High → Medium → Quick Win
7. **What's Working Well** — Positive findings and current strengths to preserve
8. **Recommended Next Steps** — Specific, ordered action list for implementation

### PDF Report

The PDF is generated from the same content as the DOCX report with identical structure. It is formatted for client delivery and stakeholder presentations.

---

## Requirements

| Requirement | Detail |
|---|---|
| **Claude access** | Claude.ai (free or Pro) or Anthropic API |
| **Recommended** | Claude Pro or API for Full Audits on large sites |
| **Operating system** | Any (skill runs inside Claude, not locally) |
| **Dependencies** | None — no local packages, APIs, or keys required |
| **Cost** | Free and open source |

> **Note:** For very large sites (100+ pages), Full Audit mode may hit context limits on the free Claude tier. Claude Pro or API access with a higher context window is recommended for comprehensive multi-page crawls.

---

## Scoring System

Each of the three audit layers is scored independently on a 1–10 scale.

| Score | Interpretation |
|---|---|
| **9–10** | Excellent. Performing at the top level across this layer. |
| **7–8** | Strong. A few targeted improvements will push to excellent. |
| **5–6** | Moderate. Notable gaps that are likely impacting performance. |
| **3–4** | Weak. Significant structural issues requiring priority attention. |
| **1–2** | Critical. Foundational problems that need immediate remediation. |

Scores are calculated as a weighted percentage of signals passing for each layer. Critical signals (e.g., missing title tags, no schema, broken canonicals) are weighted more heavily than advisory signals.

---

## FAQ

**Can I audit any website, not just my own?**

Yes. You can audit any publicly accessible URL. The skill fetches pages the same way a search engine crawler would — it only accesses publicly available content.

**Does this replace Ahrefs, Semrush, or other SEO tools?**

No — and it does not try to. Traditional SEO platforms excel at keyword tracking, backlink analysis, competitor research, and rank monitoring over time. This skill fills a gap those tools leave entirely: GEO and AEO analysis, plus a holistic multi-layer audit in a single conversational workflow with an instant downloadable report.

**How often should I run an audit?**

After any significant site change (redesign, new content section, CMS migration), after major algorithm updates, and on a routine basis quarterly. For actively growing sites, monthly Quick Audits are recommended.

**Is the skill aware of my previous audit results?**

Not automatically. Claude does not persist memory between conversations by default. You can paste a previous audit's scores into a new conversation and ask Claude to compare, or save your reports and reference them manually.

**Can I contribute to this project?**

Yes — see the Contributing section below.

**Does this work with JavaScript-heavy or SPA websites?**

Claude fetches pages server-side and may not fully render JavaScript-heavy single-page applications. For SPAs or sites that require JavaScript to render meaningful content, results may be partial. Ensure your site has a proper sitemap.xml and server-side rendering for best results.

---

## Contributing

Contributions are welcome and encouraged. If you have ideas for new audit signals, improved scoring logic, additional report formats, or bug fixes, please open an issue or submit a pull request.

### How to Contribute

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Commit your changes: `git commit -m 'Add: description of your change'`
5. Push to the branch: `git push origin feature/your-feature-name`
6. Open a Pull Request with a clear description of what you changed and why

### Areas Where Contributions Are Welcome

- Additional GEO signals (new AI platforms and retrieval patterns)
- Expanded AEO schema coverage
- Improved scoring algorithms
- Report template enhancements
- Multilingual support
- Support for JavaScript-rendered sites
- Documentation improvements

---

## Credits & Acknowledgements

### Inspired by Alex Labat

This skill was built upon and inspired by the original **Claude SEO Skill** created by **Alex Labat** — a pioneering implementation of AI-powered SEO audits inside Claude. Alex's work demonstrated the potential of Claude Skills as a platform for real-world professional tooling, and laid the groundwork that made this version possible.

Thank you, Alex. Standing on the shoulders of giants.

→ [Alex Labat on GitHub](https://github.com/alexlabat)

### Powered by Anthropic

This skill runs on Claude, Anthropic's AI assistant. All crawling, analysis, and report generation is handled by Claude's language understanding and reasoning capabilities.

→ [Anthropic](https://anthropic.com) · [Claude.ai](https://claude.ai)

---

## License

This project is released under the **MIT License**.

```
MIT License

Copyright (c) 2026 Nthabeleng Aeden Manell

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## Connect

Built by **Nthabeleng Aeden Manell** — web developer, SEO strategist, and AI tools builder.

- LinkedIn: [linkedin.com/in/aeden-manell](https://www.linkedin.com/in/aeden-manell/)
- GitHub: [github.com/nthabelengaedenmanell](https://github.com/nthabelengaedenmanell)

If this skill has been useful to you, a ⭐ on the repository goes a long way. If you'd like to collaborate, discuss AI search strategy, or share feedback, connect with me on LinkedIn.

---

*© 2026 Nthabeleng Aeden Manell · [claudeseoskill.netlify.app](https://claudeseoskill.netlify.app/)*
