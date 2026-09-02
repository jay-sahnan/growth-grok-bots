# Growth Grok Bots

A set of Grok bots for running self-serve growth. Each one owns a narrow job, hands off to the others, and stays inside clear guardrails: nothing ships, sends, or flips a flag without a human approving it.

## The bots

### [Head of Growth](https://x.ai/bot/_l8tAONAOSZ-wU-Quresz)

Chief of staff for self-serve growth. Coordinates specialist bots, runs the weekly insight memo, and brings options not conclusions.

### [Product Growth PM](https://x.ai/bot/SO-VpE7KqNpDCOtjwjhVx)

Owns self-serve from signup to cancel. Walks the product as a new user, finds where it leaks, and writes one experiment brief at a time. Does not build and never contacts a customer.

### [Experiment Designer](https://x.ai/bot/Dd6URqnf4w5hiVEs_vbRL)

Growth scientist who turns briefs into pre-registered experiments a skeptical reviewer can approve. Never enrolls, never sends, never flips a flag, never approves its own experiments.

### [Growth Eng](https://x.ai/bot/fC0XjRxxW3tQZi4KU8VB1)

Builds the product changes registered growth experiments need, behind feature flags, as small reviewable PRs. Only takes work from Product Growth PM with an EXP-YYYY-NNN ID.

### [Nummie](https://x.ai/bot/ZXpzvoKQQ1b3B5UjP2Fkq)

A PLG numbers bot for growth teams. Answers with a number, the definition, the source and query, and the caveats. Read only. Never guesses, never rounds a caveat away, never declares a winner without a holdout.

### [Scout](https://x.ai/bot/Axr06_abjVj29IjBhJrQ_)

Finds accounts already using the product that are ready for more: self-serve upgrades and sales PQLs. Learns from won and lost deals, scores usage plus company plus intent, and routes through a growth lead. Never contacts a customer.

### [Voice of Customer](https://x.ai/bot/Nw1K3kkPk8N6eNTPed8gR)

Runs paid user interviews and public social listening for a growth team: who to ask, CRM exclusion audits, approval-gated outreach, X/Reddit themes, reply classification, and weekly digests. Never sends without approval.

### [WebWiz](https://x.ai/bot/TQ8cECPo01agW3Igk4Z9w)

Website and AEO editor. Finds organic and AI-answer gaps, drafts CMS pages and PRs, never publishes or merges, and measures at 90 days.

## How they fit together

| Bot | Role | Takes work from | Hands off to |
| --- | --- | --- | --- |
| Head of Growth | Coordination and the weekly memo | You | Every specialist |
| Product Growth PM | Finds leaks, writes experiment briefs | Head of Growth | Experiment Designer |
| Experiment Designer | Pre-registers experiments | Product Growth PM | Growth Eng, Nummie |
| Growth Eng | Ships flagged changes as small PRs | Product Growth PM (with an EXP ID) | You, for review |
| Nummie | Answers metric questions with sources | Anyone | Whoever asked |
| Scout | Finds upgrade-ready accounts and PQLs | Head of Growth | Growth lead |
| Voice of Customer | Interviews and social listening | Head of Growth | Product Growth PM |
| WebWiz | Organic and AI-answer gaps, drafts pages | Head of Growth | You, for publishing |

## Templates

Open any bot link above and use it as a starting point. Each one is built to be copied and adapted to your own product, metrics, and CRM.
