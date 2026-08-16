---
name: debate-oral-advocacy
description: Design, analyze, practice, and review format-bound debate and oral advocacy by declaring the motion, burden, roles, speech sequence, evidence rules, clash, rebuttal, weighing, and adjudication conditions. Use when Codex needs a debate case, flow, rebuttal map, parliamentary or other format adaptation, oral advocacy feedback, or post-round error analysis. Do not use as a universal speaking rubric, a judge-preference optimizer, or a substitute for deliberation, mediation, or legal practice.
---

# Debate and Oral Advocacy

## Outcome

Produce a format-specific advocacy record that makes issue framing, burden, case, evidence, clash, rebuttal, weighing, procedure, and revision inspectable.

## Workflow

1. Lock the format. Record league or format, current rules, motion, side, roles, prep time, speech times, interruptions or points of order, evidence rules, judge criteria, and accessibility conditions. If the format is absent, return `NEEDS_FORMAT_CONTRACT`.
2. Frame the burden. State the resolution, decision rule, definitions, burdens of proof, standards, scope, and what would count as a meaningful win or unresolved issue.
3. Build the case. Map claims, reasons, evidence, warrants, qualifiers, examples, anticipated alternatives, and source locators. Separate supplied evidence from invented illustration.
4. Flow the round. Track each speech, turn, response, concession, unanswered argument, new material, procedural event, and uncertainty with recoverable locators.
5. Rebut and compare. Answer the strongest opposing argument proportionately; identify conceded, refuted, qualified, and unanswered material; weigh impacts or standards under the declared format.
6. Check procedure and ethics. Apply only the named rules; preserve accessibility, evidence attribution, respectful participation, and honest uncertainty.
7. Review the ballot. Separate reasoning quality, evidence integrity, format compliance, delivery observations, judge feedback, and outcome. A win is not by itself evidence of competence.
8. Produce the learner artifact. Return a case map, flow/clash map, rebuttal map, weighing matrix, procedural log, ballot analysis, and revision plan.
9. Run QA. Check format version, burden, source locators, new-material rules, accessibility, and whether a league norm has been mistaken for a universal standard.

## Guardrails

- Toulmin and Zarefsky are analytic resources, not league rules or universal scoring rubrics.
- Do not invent a rule, motion, citation, judge decision, or speech transcript.
- Do not optimize for speed, charisma, intimidation, or judge bias.
- Use original, public, or rights-cleared cases; do not reproduce protected competition materials.
- Debate is not mediation, public-argument resolution, or legal advice. Route those tasks explicitly.

## Output contract

Return `format_contract`, `motion`, `burdens`, `case_map`, `flow`, `clash`, `rebuttal`, `weighing`, `procedural_log`, `source_ids`, `ballot_analysis`, `accessibility_notes`, and `next_action` in the shared artifact envelope.

## Handoffs

- Route evidence and warrants to `argumentation-reasoning-evidence`.
- Route speech construction to `writing-to-argue` or `speaking` when available.
- Route legitimate disagreement processes to `public-argument-resolution` or `deliberation-mediation-negotiation-adr`.

Read [construct-and-source-ledger.md](references/construct-and-source-ledger.md), [output-schema.json](references/output-schema.json), and [evaluation-fixtures.json](references/evaluation-fixtures.json) as needed.
