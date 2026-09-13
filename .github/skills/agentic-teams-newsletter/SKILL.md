---
name: agentic-teams-newsletter
description: "Research, write, edit, and fact-check the Agentic Teams newsletter for technical leaders building multi-agent systems and human-AI teams. Use when creating an issue, finding newsletter stories, summarizing agentic AI news, drafting sections, writing subject lines, or preparing publication-ready newsletter copy."
argument-hint: "Topic, date range, audience, or draft to edit"
user-invocable: true
disable-model-invocation: false
---

# Agentic Teams Newsletter

## Objective

Produce a useful, source-grounded newsletter about designing, operating, and leading teams of AI agents and people. Favor practical lessons, meaningful technical developments, and evidence over hype.

## Audience

Write for engineering leaders, AI architects, product builders, and practitioners who are evaluating or operating agentic systems. Assume technical fluency, but explain specialized terms when they first appear.

## When to Use

Use this skill to:

- Research recent agentic AI developments.
- Select stories for an Agentic Teams issue.
- Draft or revise a complete newsletter.
- Summarize a paper, release, benchmark, or case study.
- Generate subject lines, preview text, and section headings.
- Fact-check and edit an existing issue.

Do not use this skill for general AI copywriting, unsupported predictions, product documentation, or promotional announcements presented as independent reporting.

## Inputs

Determine the following before drafting:

- Publication date and reporting window.
- Target length and requested format.
- Primary theme, if provided.
- Required stories, links, sponsors, or calls to action.
- Audience emphasis: leadership, architecture, implementation, research, or operations.

If an input is omitted, use a seven-day reporting window, target 900 to 1,200 words, and balance technical and organizational coverage.

## Editorial Principles

- Lead with why a development matters to teams building or using agents.
- Separate demonstrated capabilities from vendor claims and speculation.
- Prefer primary sources: papers, official documentation, release notes, repositories, standards, and first-party case studies.
- Use independent reporting to add context, criticism, or confirmation.
- Prefer concrete details such as architecture, evaluation method, constraints, cost, latency, reliability, and deployment experience.
- Include human factors when relevant: supervision, role design, accountability, trust, and workflow changes.
- Avoid inflated language such as "revolutionary," "game-changing," and "the future is here."
- Do not imply that a demo, benchmark, or announcement proves production readiness.

## Research Procedure

1. Establish the reporting cutoff date and date range.
2. Search for candidate developments across research, open source, platforms, standards, evaluations, security, and real-world deployments.
3. Open and read the primary source for every candidate story.
4. Record the title, publisher, publication date, URL, key claim, supporting evidence, limitations, and relevance to agentic teams.
5. Reject stories outside the date range unless they provide necessary context.
6. Reject claims that cannot be traced to a credible source.
7. Rank candidates using the selection criteria below.
8. Select three to five stories that provide a varied, coherent issue.

## Story Selection

Score each candidate from 0 to 2 on:

- **Relevance:** Directly affects how agentic teams are designed, evaluated, secured, or managed.
- **Evidence:** Supported by inspectable technical details or credible real-world results.
- **Novelty:** Adds a material capability, finding, constraint, or perspective.
- **Practical value:** Gives readers a decision, technique, warning, or question they can use.
- **Timeliness:** Falls within the reporting window or explains an active development.

Prefer stories scoring at least 7 out of 10. Do not select several stories that repeat the same lesson.

## Drafting Procedure

1. Identify one editorial theme connecting the selected stories.
2. Write the subject line and preview text after the body is stable.
3. Open with a 100-to-150-word editor's note that states the issue's central tension or lesson.
4. Cover the most consequential story first.
5. For each main story, explain what happened, why it matters, what the evidence supports, and what readers should do or watch next.
6. Add a short practical section with an implementation pattern, evaluation technique, operating question, or team exercise.
7. Close with a compact reading list and one direct call to action.
8. Perform the fact-check and editorial review before returning the issue.

## Standard Issue Structure

Use this structure unless the user requests another format:

```markdown
# Agentic Teams

**Subject:** [Clear, specific promise]
**Preview text:** [One sentence that complements the subject]
**Issue date:** [Month DD, YYYY]

## Editor's Note
[The issue's central theme and why it matters now.]

## Lead Story: [Specific headline]
[What happened, evidence, implications, and practical takeaway.]

Source: [Publisher or author](URL), published [date].

## What Else Matters

### [Story headline]
[Concise analysis and takeaway.]

Source: [Publisher or author](URL), published [date].

### [Story headline]
[Concise analysis and takeaway.]

Source: [Publisher or author](URL), published [date].

## Field Note
[A concrete pattern, checklist, experiment, or operating question.]

## Worth Reading

- [Title](URL) - [Why it is worth the reader's time.]

## Closing
[One clear question or call to action.]
```

## Fact-Checking

Before finalizing:

1. Open every cited URL and confirm it supports the adjacent claim.
2. Verify names, organizations, product names, dates, versions, and numerical claims.
3. Attribute benchmarks and performance claims to the organization that reported them.
4. State important evaluation conditions and limitations near the claim.
5. Label forecasts, interpretations, and opinions explicitly.
6. Remove claims whose sources are unavailable, circular, undated, or materially ambiguous.
7. Confirm all links point to the intended source and are not search-result or tracking URLs.

Never invent a quotation, statistic, source, URL, publication date, or personal experience. If current web research is unavailable, say so and request sources or clearly limit the output to the supplied material.

## Style

- Use a confident, analytical, and conversational voice.
- Prefer short paragraphs and descriptive headings.
- Use active voice and concrete verbs.
- Define acronyms on first use.
- Keep quotations brief and use them only when the exact wording matters.
- Distinguish agents working as a system from humans collaborating with agents.
- Avoid repeating the same summary in the headline, opening sentence, and takeaway.
- Use ASCII punctuation unless a requested publishing format requires otherwise.

## Output Contract

Return:

1. Publication-ready newsletter copy in Markdown.
2. Three alternative subject lines, each no more than 60 characters.
3. One preview-text option, no more than 100 characters.
4. A source list containing publisher, title, publication date, and URL.
5. A brief fact-check note identifying unresolved claims or unavailable sources.

For research-only requests, return a ranked story slate instead of a full issue. Include each story's score, primary source, key evidence, limitation, and proposed editorial angle.

## Final Review

Confirm that:

- Every central claim has a nearby source.
- The issue contains a practical takeaway, not only summaries.
- Headlines describe the substance without clickbait.
- Dates and time-sensitive language are explicit.
- Vendor announcements are labeled and critically framed.
- The issue respects the requested length and reporting window.
- No unresolved placeholders remain.