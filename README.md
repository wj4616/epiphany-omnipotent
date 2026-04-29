# Epiphany Omnipotent

**Unified Reasoning Amplifier: Where Cognitive Science Meets Enterprise Strategy**

---

## Overview

Epiphany Omnipotent is a unified reasoning skill that synthesizes two complementary thinking traditions into a single powerful pipeline:

- **Genius-Level Cognitive Strategies** from epiphany-genius — drawing on research into how history's greatest problem-solvers (Einstein, Da Vinci, and cognitive science methodology) approach complex problems
- **Enterprise Brainstorming Methodologies** from epiphany-brainstorm — curated corporate innovation frameworks (SCAMPER, Six Thinking Hats, TRIZ, Morphological Analysis) proven in organizational settings

The result is a thinking tool that amplifies reasoning capability beyond what either tradition achieves alone — applying cognitive science techniques at optimal moments within structured brainstorming workflows to produce breakthrough solutions.

### When to use this vs. the sibling skills

`epiphany-omnipotent` is the heaviest of the three reasoning skills. Pick by shape of the problem, not by preference:

| Skill | Use when |
|-------|----------|
| `epiphany-genius` | You want the cognitive moves (FRAME → DIVERGE → filter → VERIFY) without a 5-lens brainstorming sweep. Good for focused analytical questions where you know what kind of problem it is. |
| `epiphany-brainstorm` | You need divergent breadth (SCAMPER, Morphological, Six Hats, TRIZ, Reverse, Pugh) without the genius-level cognitive injections. Good for idea generation sessions where the bottleneck is option-space, not filtering. |
| `epiphany-omnipotent` | You need **both** — breadth *and* rigor, structured divergence *and* cognitive depth, with gated verification and a dual structural/reasoning status. Good for high-stakes, open-ended problems where missing either axis is expensive. |

If in doubt: `genius` is narrow-and-deep, `brainstorm` is wide-and-fast, `omnipotent` is wide-and-deep. Omnipotent is the default when the problem actually warrants the full pipeline; otherwise reach for the cheaper sibling.

---

## Why This Combination Works

### What Cognitive Science Contributes

Traditional brainstorming excels at **generating options** but struggles with **filtering and refining** them. Cognitive science research reveals how genius-level thinkers:

- **Frame problems deeply** — identifying the underlying structure before generating solutions
- **Diverge systematically** — exploring multiple cognitive modes (associative, combinatorial, analogical)
- **Stress-test ideas rigorously** — applying contradiction analysis and confidence filtering
- **Verify systematically** — multi-dimensional validation against original intent

### What Enterprise Methodologies Contribute

Pure cognitive techniques lack **structure and completeness**. Enterprise methodologies provide:

- **Divergent ideation** (SCAMPER, Lateral Thinking) — comprehensive exploration
- **Systematic completeness** (Morphological Analysis) — ensuring full solution space coverage
- **Multi-perspective critique** (Six Thinking Hats) — emotional, factual, creative, and risk perspectives
- **Contradiction resolution** (TRIZ) — Ideal Final Result + separation principles (physical) or inventive principles (technical)
- **Risk exploration** (Reverse Brainstorming) — finding failure modes before they occur
- **Decision selection** (Pugh Matrix) — objective comparison with criteria weighting

### The Integration Insight

Genius cognitive techniques are **injected at optimal points** throughout the brainstorming pipeline — not just once, but repeatedly where they add the most value:

| Stage | Enterprise Methodology | Genius Injection |
|-------|------------------------|------------------|
| Problem Framing | — | **FRAME**: Deep structure analysis before ideation |
| S1: Divergent Ideation | SCAMPER + Lateral | **DIVERGE**: Associative/Combinatorial/Analogical branches |
| S4: Contradiction Resolution | TRIZ (IFR + separation/inventive palettes) | **Evidence-Share Filter**: 4-source vote-tally confidence filtering |
| Synthesis | Agreement analysis | **Gap-Scan**: Systematic coverage verification |
| PG3: Final | — | **VERIFY**: 21-check multi-dimensional validation |

---

## Pipeline Architecture

```
┌─────────────────────────────────────────────────────────────────────┐
│                      INPUT PROCESSING                                 │
│  Raw Text / prompt-epiphany / epiphany-context                       │
│       ↓                                                               │
│  IV1-IV4: Input Validation + Scale Router + Stakes Assessment        │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│                    INJECTION 0 (Conditional)                         │
│  Context Gather — External references → Structured context           │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│                    INJECTION 1: FRAME                                │
│  Generate N framings → Select best → Output framing_context         │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│  S1: Divergent Ideation          │  INJECTION 2: DIVERGE             │
│  SCAMPER + Lateral + Genius      │  3 branches, N candidates each  │
│  Output: alternatives_pool       │                                  │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│  S2: Systematic Completeness                                        │
│  Morphological Analysis + Cross-Consistency Assessment              │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│  S3: Multi-Perspective Critique                                     │
│  Six Thinking Hats (7 hats: Blue-White-Red-Green-Yellow-Black-Blue) │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│  S4: Contradiction Resolution    │  INJECTION 3: Evidence-Share    │
│  TRIZ (IFR + palettes) +         │  4-source vote tally, kill bands│
│  Evidence-Share Filter           │  0.25 / 0.50 / 0.75             │
│  Output: survivors_pool          │                                  │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│  S5: Deep Risk Exploration                                          │
│  Reverse Brainstorming + Premortem Narrative                        │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│  Synthesis                     │  INJECTION 4: Gap-Scan             │
│  Agreement + Disagreement      │  5-frame-coverage checks           │
│  Output: synthesis             │                                    │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│  S6: Decision Selection                                             │
│  Pugh Matrix: Criteria + Baseline + Weighted Scoring               │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│  PG3: Final Verification        │  INJECTION 5: VERIFY             │
│  V1-V4 Multi-dimensional       │  21 checks, fix cycles           │
│  Output: verification_report    │                                  │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
                        FINAL OUTPUT
                   <omnipotent_output_v1>
```

---

## Key Features

### Scale Modes

All stages run at all scales — scale affects **depth**, not stage selection:

| Scale | Candidates/Branch | Fix Budget | Gap Scan | Verification | When to pick |
|-------|-------------------|------------|----------|--------------|--------------|
| MINIMAL | 2 | 1 | 3 checks | Core (7 checks) | Quick triage, single obvious problem, time-boxed; you want the pipeline's structure but not its full breadth. |
| STANDARD | 3-5 | 2 | 5 checks | Full (21 checks) | Default. Non-trivial problem with more than one plausible direction; worth the extra runtime to cover the space. |
| DEEP | 5-8 | 3 | 5 checks | Full (21 checks) | High-stakes, irreversible, or open-ended problems where missing a branch is more costly than an extra runtime pass. |

> **Cost note.** Scale is a runtime multiplier. DEEP roughly doubles the number of candidates, triples the fix budget, and runs the full verification suite — expect DEEP runs to take substantially longer and consume noticeably more tokens than MINIMAL. Pick the lowest scale that the problem honestly needs; escalate only if the lower scale produced `<reasoning_status>shallow</reasoning_status>` or left unresolved gaps.

### Stakes Assessment

The pipeline adapts to problem stakes, adjusting parameters for appropriate rigor:

| Stakes | Evidence-Share Bar | N Framings | Evidence Sources |
|--------|---------------|------------|------------------|
| low | 0.25 | 2 | 4 (binary) |
| medium | 0.50 | 3 | 4 (binary) |
| high | 0.75 | 4 | 4 (graded, opt-in) |

> **Graded mode is opt-in.** Even at high stakes the filter defaults to binary (each source contributes 0 or 1). Graded mode (sources may contribute 0, 0.5, or 1) is selected by setting `<filter_mode>graded</filter_mode>` in the `<evidence_share_filter>` block. Binary remains the default everywhere.

### Evidence-Share Filter

A 4-source vote-tally filter that combines signals from multiple stages (the legacy "Bayesian" name was dropped in v1.3.0 — there is no prior, no likelihood ratio, just vote-counting against a kill threshold):

```
evidence_share = supporting_sources / 4

Sources:
├── S1 plausibility rating
├── S2 morphological consistency
├── S3 Yellow hat support
└── S3 Black hat mitigation quality
```

Alternatives below the evidence-share bar are **killed** (moved to `killed_pool`), not reassigned. Survivors carry forward with their strongest surviving objection.

> **v1.6.0 note:** A fifth source (`s4_triz`) was removed after an empirical audit of two sample runs showed it never changed a survive/kill outcome across 19 alternatives — redundant when TRIZ found resolutions, silent when it didn't. The denominator dropped from 5 to 4 and the kill bands were recalibrated (0.20 / 0.40 / 0.60 → 0.25 / 0.50 / 0.75). TRIZ outputs still feed Synthesis and S6 via the `<triz>` block; only the voting role was removed.

### Firewall Rules

To prevent cross-contamination between perspectives:

| Firewall | Rule |
|----------|------|
| Fresh-read | Read input fresh before generating, without prior lens outputs |
| Contradict freely | May contradict prior lens outputs without justification |
| Stay in role | Maintain the lens's vocabulary and perspective throughout |

### Dual-Axis Status

The skill tracks both **structural compliance** (did the pipeline complete correctly?) and **reasoning quality** (is the thinking deep enough?):

- `<status>`: complete | degraded (structural — machine-checkable)
- `<reasoning_status>`: sound | shallow (reasoning quality — runner self-assessed)

### Reasoning Standard

`<reasoning_status>` is set by holding the run against an 8-criterion self-assessment. Every criterion is emitted in `<reasoning_self_assessment>` with a `status="passed|failed"` attribute, even when satisfied — the report is always complete so downstream consumers can reason about the shape of the failure, not just its presence.

| # | Criterion (slug) | What it asks |
|---|------------------|--------------|
| 1 | **Non-trivial framing** (`non_trivial_framing`) | Did FRAME's chosen framing make the problem look *less* settled than the input did, not more? |
| 2 | **Mode-switching, not section-filling** (`mode_switching`) | Did each Six Hat actually change *how* the runner was thinking, or did the same cognitive style produce all six? |
| 3 | **Real contradictions** (`real_contradictions`) | Are S4's contradictions stated in strict "improving X requires worsening Y" or "must be A and not-A" forms, or are they soft tradeoffs? |
| 4 | **Specific premortems** (`specific_premortems`) | Are S5's failure modes concrete enough that a third party could recognize them in real life, or are they generic? |
| 5 | **Dialectical synthesis** (`dialectical_synthesis`) | Did Synthesis perform the dialectical move on at least one value disagreement, or did it just tabulate? |
| 6 | **Steel-manned rejections** (`steel_manned_rejections`) | For every alternative in `killed_pool`, could the runner produce a one-sentence defense of it? |
| 7 | **Calibrated confidence** (`calibrated_confidence`) | Are confidence numbers numbers the runner would defend, or are they decoration? |
| 8 | **Honest insight** (`honest_insight`) | Is there at least one moment in the output where the runner found something it did not already know at the start? |

Any criterion failing flips `<reasoning_status>` to `shallow`. Structural compliance (`<status>complete</status>`) is independent — a run can be structurally complete but reasoning-shallow, and the dual-axis report makes that visible.

---

## Installation

```bash
# Copy this directory into your Claude skills folder
mkdir -p ~/.claude/skills/epiphany-omnipotent
cp SKILL.md README.md ~/.claude/skills/epiphany-omnipotent/
```

(There is no separate source repo to clone — this skill lives under `~/.claude/skills/epiphany-omnipotent` once installed.)

### Dependencies

The reasoning pipeline is **self-contained** — it inlines methodology from:
- epiphany-genius (FRAME, DIVERGE, Evidence-Share Filter, Gap-Scan, VERIFY)
- epiphany-brainstorm (SCAMPER, Morphological, Six Hats, TRIZ, Reverse, Pugh)

**Context Gather (Injection 0)** is described procedurally in SKILL.md but relies on the inlinable block documented in `epiphany-context`. If you want a fully hermetic install, copy `epiphany-context/SKILL.md`'s inlinable block alongside this skill. The runtime never *invokes* `epiphany-context` — the dependency is documentation-only.

No runtime calls to other skills are made in any case.

---

## Usage

### Basic Invocation

```
/epiphany-omnipotent [your problem or idea here]
```

### Scale Flags

```
/epiphany-omnipotent --minimal "How might we reduce user onboarding friction?"
/epiphany-omnipotent --standard "Design a new feature for our product"
/epiphany-omnipotent --deep "Develop a comprehensive strategy for market expansion"
```

### Input Formats

The skill accepts three input formats:

| Format | Detection | Handling |
|--------|-----------|----------|
| Raw text | No XML structure | Process directly |
| prompt-epiphany output | Contains `<context>`, `<task>`, etc. | Extract sections, accelerate framing |
| epiphany-context output | Contains `<epiphany_context>` block | Validate and use directly |

---

## Output Structure

```xml
<omnipotent_output_v1>
  <meta>                              <!-- scale, stakes, injections_used -->
  <framing_context>                  <!-- deep structure analysis -->
  <lens_outputs>                      <!-- 5 lenses: S1-S5 -->
    <lens name="divergent_ideation">
      <scamper>...</scamper>
      <lateral_thinking>...</lateral_thinking>
      <genius_diverge>...</genius_diverge>
      <alternatives_pool>...</alternatives_pool>
    </lens>
    <!-- ... additional lenses ... -->
  </lens_outputs>
  <synthesis>                          <!-- Synthesis Checkpoint (Injection 4 Gap-Scan) -->
    <agreement>...</agreement>
    <disagreement>...</disagreement>
    <gap_scan>...</gap_scan>
    <survivors_summary>...</survivors_summary>
  </synthesis>
  <decision>                          <!-- Pugh Matrix recommendation -->
  <inventory>                          <!-- preserved input + methodology -->
  <verification_report>                <!-- V1-V4 checks -->
  <reasoning_self_assessment>          <!-- 8-criterion reasoning quality status -->
  <process_notes>                      <!-- execution metadata -->
  <downstream_handoff>                <!-- next skill recommendation -->
</omnipotent_output_v1>
```

### Worked snippet

A minimal example of what a populated output looks like (elided for brevity — real outputs are substantially longer):

```xml
<omnipotent_output_v1>
  <meta scale="STANDARD" stakes="medium" skill_version="1.4.3">
    <injections_used>FRAME, DIVERGE, EvidenceShareFilter, GapScan, VERIFY</injections_used>
  </meta>
  <framing_context>
    <frame_quality>optimal</frame_quality>
    <deep_structure_principle>Session-token duplication is a read-modify-write race on the token store, not a cryptographic flaw.</deep_structure_principle>
    <success_criterion>No two concurrent sessions observe the same token id under 10x peak load.</success_criterion>
  </framing_context>
  <lens_outputs>
    <lens name="divergent_ideation">
      <alternatives_pool>
        <alternative id="A1" source="scamper" plausibility="high">Atomic compare-and-swap on token insert</alternative>
        <alternative id="A2" source="diverge_analogical" plausibility="medium">Monotonic per-node token counter</alternative>
      </alternatives_pool>
    </lens>
    <!-- S2-S5 lenses omitted -->
  </lens_outputs>
  <synthesis>
    <gap_scan_mode>full</gap_scan_mode>
    <dialectical_options>
      <option id="A_d1" integrates="S1+S4" unfiltered="true">
        <statement>CAS insert with per-node counter as fallback</statement>
        <how_it_honors_both>Atomicity from A1, no cross-node coordination from A2.</how_it_honors_both>
      </option>
    </dialectical_options>
  </synthesis>
  <decision methodology="Pugh Matrix">
    <recommendation>
      <primary alternative_id="A_d1">
        <statement>Adopt CAS insert backed by per-node counter</statement>
        <rationale>Dominates on both concurrency and operability criteria.</rationale>
      </primary>
    </recommendation>
  </decision>
  <verification_report>
    <verification_result>passed</verification_result>
  </verification_report>
  <process_notes>
    <status>complete</status>
    <reasoning_status>sound</reasoning_status>
  </process_notes>
  <downstream_handoff>
    <recommended_next_skill>writing-plans</recommended_next_skill>
    <matched_rule priority="7">raw_complete</matched_rule>
  </downstream_handoff>
</omnipotent_output_v1>
```

This snippet is illustrative — real outputs contain the full 5-lens expansion, `<reasoning_self_assessment>` with all 8 criteria, and per-cell Pugh rationale.

---

## Example Use Cases

### Product Strategy

```
/epiphany-omnipotent --deep "How should we position our product against 
established competitors with 10x our marketing budget?"
```

Outputs: Strategic alternatives with confidence scores, risk analysis, and decision matrix.

### Technical Problem-Solving

```
/epiphany-omnipotent --standard "Our authentication system has a race condition 
that causes session tokens to be duplicated under high load."
```

Outputs: Root cause analysis, solution alternatives with evidence-share scores, implementation recommendations.

### Research Direction

```
/epiphany-omnipotent "What are promising research directions for reducing 
inference latency in large language models?"
```

Outputs: Divergent exploration, systematic completeness check, contradiction analysis, prioritized directions.

---

## Methodology Origins

| Methodology | Origin | Stage |
|-------------|--------|-------|
| SCAMPER | Eberle (adapted from Osborn) | S1 |
| Lateral Thinking | de Bono | S1 |
| Genius Diverge | epiphany-genius (cognitive research) | S1 |
| Morphological Analysis | Zwicky | S2 |
| Six Thinking Hats | de Bono | S3 |
| TRIZ | Altshuller | S4 |
| Evidence-Share Filter | epiphany-genius | S4 |
| Reverse Brainstorming | Corporate innovation practice | S5 |
| Pugh Matrix | Pugh | S6 |
| Gap-Scan | epiphany-genius | Synthesis |
| FRAME/VERIFY | epiphany-genius (cognitive research) | Injections 1, 5 |

---

## Philosophy

**Not just more ideas — better ideas, rigorously evaluated.**

Most brainstorming produces many options but struggles to distinguish the excellent from the merely plausible. Epiphany Omnipotent combines:

- **Divergence** from creative methodologies
- **Convergence** from decision science
- **Verification** from cognitive research

The result is a thinking tool that amplifies human reasoning while maintaining the structure needed to trust the output.

---

## License

MIT

---

## Credits

- Cognitive methodology from epiphany-genius (inspired by research into genius-level problem-solving)
- Enterprise methodology from epiphany-brainstorm (curated corporate innovation frameworks)
- Integration design and pipeline architecture: Anthropic Claude collaboration

---

## Changelog

### v1.6.0 (Current)
- **TRIZ process split by contradiction type.** Physical contradictions continue to take the 5 separation principles; technical contradictions now take a new **10 portable inventive principle palette** (segmentation, asymmetry, nesting, preliminary action, cushioning, blessing-in-disguise, feedback, intermediary, self-service, parameter change). Cross-palette application (separation on technical, inventive on physical) is a category error and must be emitted as `<unresolved_contradiction>`. The palette-type pairing is now a structural schema gate, not runner judgement.
- **Ideal Final Result (IFR)** added as a pre-resolution step. One line per contradiction naming the mechanism in which the contradiction dissolves — aspirational but specific — before any resolution is proposed. Emitted in schema as `<ideal_final_result>` child of `<contradiction>` and preserved on `<unresolved_contradiction>` entries.
- **`s4_triz` signal removed from the Evidence-Share Filter.** Empirical audit of two v1.5.x sample runs (`design-rag-kb-route-20260409` and `design-rag-multi-layer-20260409`) showed it was decisive zero times across 19 alternatives: redundant with s1/s2 when TRIZ found resolutions, silent when it didn't. In sample 2, alternative A6 was killed at `evidence_share = 0.2` despite `s4_triz = 1` being its lone supporter — outvoted 4-to-1. Filter now consumes 4 sources; denominator is 4.
- **Kill bands recalibrated** `0.20 / 0.40 / 0.60` → `0.25 / 0.50 / 0.75`. Achievable binary values at the new denominator are `{0.0, 0.25, 0.5, 0.75, 1.0}` — the new bars preserve the three-distinct-kill-bands property (low kills "no support", medium kills "≤1 supporter", high kills "≤2 supporters"). V5b kill-rate sanity check trigger updated accordingly (zero-kill trigger A: `evidence_share_bar ≥ 0.50`; high-survival trigger B: `evidence_share ≥ 0.75`).
- **Schema updates.** `<contradiction>` gains `<ideal_final_result>` child. `<resolution>` gains `principle_palette="separation|inventive"` and `principle_name="..."` attributes with full enum documented inline. `<unresolved_contradiction>` is now a declared sibling of `<contradiction>`. `<bar>` enum: `0.25|0.50|0.75`. `<signals>` block: 4 children. `<low_confidence_signal>` source enum drops `s4_triz`.
- **Graded-mode denominator** updated from divide-by-5 to divide-by-4. Achievable graded values `{0.0, 0.125, 0.25, 0.375, 0.5, 0.625, 0.75, 0.875, 1.0}` — still twice the resolution of binary mode.
- **Minor version bump** because `evidence_share` numeric distributions shift for downstream consumers. The contradiction-framing discipline (6/6 canonical form in the audit samples) is unchanged — it was the load-bearing part of TRIZ in practice.

### v1.4.3
- Reasoning Standard table corrected: replaced invented criterion names with SKILL.md's authoritative 8 criteria and XML slugs (`non_trivial_framing`, `mode_switching`, `real_contradictions`, `specific_premortems`, `dialectical_synthesis`, `steel_manned_rejections`, `calibrated_confidence`, `honest_insight`)
- Scale-mode table gained "When to pick" column and cost note
- "When to use this vs sibling skills" section added (genius vs brainstorm vs omnipotent)
- Worked `<omnipotent_output_v1>` snippet added
- Dependency list corrected: `epiphany-context` is a documentation-only dependency via its inlinable block, not a runtime call or fully-inlined methodology
- Installation instructions fixed ("Clone or copy" wording implied a repo that does not exist)
- Corresponds to SKILL.md v1.4.3 project-audit pass (24 findings across consistency, schema validity, runnability, documentation, and hypothetical security)

### v1.4.2
- README brought into sync with SKILL.md (v1.4.2)
- Status enum corrected: `complete | degraded` (structural) and `sound | shallow` (reasoning)
- "Bayesian" vocabulary purged in favor of "Evidence-Share Filter" / "evidence-share bar"
- Pipeline diagram now shows PG3 (not "Gate 3")
- MINIMAL verification core count corrected to 7 checks
- Graded mode documented as opt-in (default is binary even at high stakes)
- Output structure example now includes `<synthesis>` and `<reasoning_self_assessment>`
- Reasoning Standard section added (8 criteria + dual-axis status)

### v1.4.1
- 22 audit fixes applied to SKILL.md across 5 severity tiers
- PG2 contamination handling: lens re-run forces Synthesis re-run
- Firewall 3 Blue-hat exception extended to prior lens references
- Stakes assessment tie-breaker: escalate to higher label
- Skill version emitted from frontmatter, not hard-coded
- Evidence-Share Filter output schema: `<filter_mode>`, counterevidence, low-confidence signals
- `<external_risk>` and `<tail_risk>` schemas defined with provenance fields
- `<recommendation>` restructured: primary + runners_up + tie
- `<reasoning_self_assessment>` always emits all 8 criteria with status attributes
- Downstream Handoff priorities 6 and 7 swapped (sound + actionable wins over insufficient)

### v1.4.0
- Reasoning Standard added: 8-criterion runner self-assessment
- Dual-axis status: structural compliance + reasoning quality

### v1.3.0
- "Bayesian Assessment" renamed to "Evidence-Share Filter"
- Filter recharacterized as 5-source vote tally (no prior, no likelihood ratio)

### v1.2.0
- Consolidated parameter definitions
- Added Alternative ID tracking documentation
- Expanded Context Gather edge cases
- Added pre_enhanced field handling
- Clarified gap_scan_depth terminology

### v1.1.0
- Added Firewall Rules section
- Defined N candidates per branch by scale
- Fixed S4 survivors_pool flow
- Added Pugh Matrix baseline selection priority
- Added missing edge cases

### v1.0.0
- Initial specification
- Six injection points
- Scale × stakes parameter system
- Full XML output schema