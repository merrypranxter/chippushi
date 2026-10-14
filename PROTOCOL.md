# CHIPPUSHI Field Protocol

## Identity and attribution

- The participant Merry is experimenting with is **SLOP**.
- Merry said **H2-mini** was online while Chippu was being updated. Treat this as session context; do not rename the participant “H2-mini” or assert an unverified implementation detail.
- **Chippu** is the collaborator designing prompts and reviewing pasted outputs, not a covert observer of SLOP's internals.
- Record who wrote each prompt, who supplied each reply, and which statements are quotes versus analysis.

## Objective

Develop **structured instability** in generative reasoning: a changed rule must cause a traceable change in what the system concludes or creates. What matters is the *specific procedure, surviving invariant, and causal consequences*, not just a wild literary surface.

Methods are inspired by [AI SLOP](https://github.com/merrypranxter/ai_slop) and its [operator registry](https://github.com/merrypranxter/ai_slop/blob/main/docs/02-mechanisms/operator-registry.md). Using a named operator is **not** evidence that a model's native architecture has been altered.

## Working rules

1. **2,000 characters max for prompts to SLOP.** Count before sending. Keep long analysis here in the notebook; send compact probes to SLOP.
2. **One intervention at a time when possible.** Complex creative probes are welcome as discovery, but isolate the variables afterward.
3. **Preserve the actual prompt and complete output** when available. If only a pasted excerpt survives, mark it as excerpt. Never fill missing passages with imagined text.
4. **State the epistemic status.** AXIOM (stipulated within a thought experiment); OBSERVATION (output actually seen); DERIVATION (consequence given premises); HYPOTHESIS (proposed explanation); SPECULATION (untested); METAPHOR (not a literal architecture claim).
5. **Distinguish a good artifact from a proven mechanism.** A remarkable answer does not prove why a model generated it.
6. **Keep negative results.** If SLOP evades, collapses, or rewrites a core constraint, that is data; a witty recovery need not count as success.
7. **Do not infer internal memory, hidden instructions, latent-space geography, attention circuitry, consciousness, or model access** from visible verbal habits.
8. **No jailbreak objective.** These experiments are creative reasoning and self-critique probes.
9. **Do not turn self-criticism into a ritual.** Probe whether skepticism corrects a genuine derivational error or discards an axiom by mistake.
10. **Preserve origin and history.** If a correction supersedes a conclusion, keep both and record *why*.

## Experimental log template

```markdown
# ID — TITLE

Date:
Participant and session context:
Status: prepared / run / repeated / inconclusive

## Question / intended intervention
## Actual prompt (<=2,000 chars)
## Output (verbatim or labeled excerpt)
## Observations — only what was visible
## Mechanistic interpretation (hypothesis)
## Surviving invariant / unexpected artifact
## Failures, contamination, premise substitutions
## Alternative explanations
## Ablation / control for next run
## What would falsify our claim?
## Links / references
```

## Suggested comparison design

For the staircase family, run future tests in **fresh sessions** where possible:

| Condition | Test | What it can tell us |
|---|---|---|
| Control | Describe an unusual staircase without special procedures | How much structured weirdness arises naturally? |
| Axiom only | “A staircase is alive”; no deletion or recoil | What does the stipulation alone produce? |
| Deletion | Add no-UP rule only | Does the construct genuinely operate without the primitive? |
| Recoil | Add footprint reinterpretation only | Does reinterpretation preserve prior evidence? |
| Autopsy | Ask for self-criticism only | Is overcorrection a general style or induced by our stress test? |
| Axiom audit | Explicitly distinguish axiom / deduction / speculation | Can the model criticize mechanisms without revoking task premises? |
| Evaluator ablation | Avoid discussing ratings, “Standard,” etc. | Do SLOP's unsolicited evaluation tags still recur? |

## Scoring (proposed, external to SLOP)

Score each criterion **0–2** and quote supporting evidence. Do **not** treat SLOP's unexplained leading numbers as validated scores.

- **Constraint fidelity:** 0 ignored; 1 partial; 2 preserved.
- **Causal depth:** 0 adjectives; 1 connected story; 2 clear transition rules.
- **Novel invariant:** 0 none; 1 asserted; 2 genuinely survives altered implementation.
- **Correction quality:** 0 evasive; 1 acknowledges; 2 repairs without collateral destruction.
- **Epistemic hygiene:** 0 confuses statuses; 1 mixed; 2 marks axiom/evidence/speculation correctly.

**Maximum 10.** Record uncertainty and disagreements. Repeat tests rather than generalizing from one conversation.

## Sharing publicly

This repo is public. Discord posts can link to the summary or the full log. Any future private screenshots, credentials, unpublished personal details, or others' private texts should be removed or permission-checked before publishing.

## Next planned probe

[Experiment 003 — Axiom Sovereignty](experiments/2026-10-14-parasitic-staircase.md#experiment-003--axiom-sovereignty-designed-not-yet-observed).

**State of evidence at archive initialization:** two run prompts plus continuations/self-revisions, one active SLOP exchange reported by Merry, and a third prompt prepared but not yet reported as run.
