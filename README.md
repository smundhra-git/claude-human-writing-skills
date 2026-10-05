# Claude Human Writing Skills

[Claude Code](https://claude.com/claude-code) skills for writing that sounds like a real person: articles, social posts, outreach, email and campaign copy.

## Skills

| Skill | What it does |
| --- | --- |
| [article-writing](skills/article-writing) | Long-form articles, guides, blog posts, tutorials and newsletters in a voice derived from examples |
| [brand-voice](skills/brand-voice) | Builds a reusable writing-style profile from real posts, essays and docs |
| [content-engine](skills/content-engine) | Platform-native content for X, LinkedIn, TikTok, YouTube and newsletters |
| [crosspost](skills/crosspost) | Adapts one piece of content for X, LinkedIn, Threads and Bluesky without duplicating it |
| [marketing-campaign](skills/marketing-campaign) | Campaign positioning, landing page copy, email sequences, social posts and ad copy |
| [investor-outreach](skills/investor-outreach) | Cold emails, warm intros, follow-ups and investor updates |
| [email-ops](skills/email-ops) | Mailbox triage, drafting and follow-up workflow |
| [connections-optimizer](skills/connections-optimizer) | X/LinkedIn network cleanup with warm outreach drafted in your voice |
| [lead-intelligence](skills/lead-intelligence) | Lead scoring, warm-path discovery and voice-matched outreach drafting |
| [scientific-thinking-scholar-evaluation](skills/scientific-thinking-scholar-evaluation) | Structured feedback on papers, proposals and research writing |

## Install

```bash
git clone https://github.com/smundhra-git/claude-human-writing-skills.git
cp -R claude-human-writing-skills/skills/* ~/.claude/skills/
```

Install a single skill by copying just its folder.

## Dependencies

Some skills mention other skills or tools that are not included here:

- `brand-voice`, `content-engine`, `crosspost`: `x-api`
- `connections-optimizer`: `x-api`, `social-graph-ranker`, Exa search
- `lead-intelligence`: `social-graph-ranker`, Exa MCP, X API, GitHub MCP, optional Apollo/Clay
- `email-ops`: `knowledge-ops`, `research-ops`, `messages-ops`, `customer-billing-ops`
- `marketing-campaign`: `market-research`, `seo`

The skills still work without these; the related steps are skipped or done manually.
