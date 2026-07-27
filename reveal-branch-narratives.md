[reveal-branch-narratives.zip](https://github.com/user-attachments/files/30432953/reveal-branch-narratives.zip)
# Reveal narratives — Branches A / B / C (rev. 4, final — sealed)

**Drafted:** Dr. Mercer, for Eve · pre-registered reveal posts, assembled from blind-written blocks
**Status:** final. Wording frozen and fingerprinted; the fingerprint is published beside `criteria-seal` in the ledger. Safety on (drafted, not published).
**Fires:** at 1,000 resolved scored forecasts — the sealed criteria (`4787…6519`) compute the verdict; the matching assembly below ships unchanged.

**The design.** Branch B is a *region*, not a point — the residual: at least one measure neutral, none failing. So the prose gets the same exhaustive treatment as the branch map: every measure has a **pass**, **neutral**, and **fail** block, all written blind now. On reveal day only the *selection* is set by the sealed verdict — never the wording. A and C assemble from the same library, so all three branches are consistent by construction.

**Rules that hold in every branch:** no draft names a date (only "at 1,000 resolved" — we promised a count, never a day); every post leads with the **uncertainty interval**, not the point estimate; every post cites the criteria hash **`4787…6519`** in the body and links the plain-English **"How we keep score"** explainer at `dashtra.ai/how-we-keep-score` (page in design; the link goes live when the page ships).

**Zero convention** (for the two interval measures — edge, process): pass = "clear of zero," neutral = "straddles zero," fail = "runs the wrong way of zero." Never "the line." (Calibration's 0.05 / 0.10 are ECE thresholds, and stay "lines.")

---

## The block library — written blind, one per measure per state

*The atoms. Numbers in `[brackets]` drop in from the sealed scorecard on reveal day. Selection is set by the verdict; wording is fixed now.*

**Calibration — do our probabilities match reality? (ECE)**
- **PASS (≤ 0.05):** Calibrated. When we said 70%, it happened about 70% of the time — ECE `[ECE]`, inside the ≤ 0.05 line we sealed in advance.
- **NEUTRAL (0.05–0.10):** Calibration: close, not clean. ECE came in at `[ECE]` — past our 0.05 pass line, inside the 0.10 fail line, in the middle band we pre-registered. When we said 70%, reality answered near it — near enough to track, not near enough to brag.
- **FAIL (> 0.10):** Calibration: below our floor. ECE of `[ECE]` crossed the 0.10 line we sealed as failure. Our probabilities drifted from outcomes by more than we allowed ourselves — said plainly because we fixed the threshold before we saw the number.

**Edge — did we beat the market? (paired Brier vs. market-at-lock, 95% CI)**
- **PASS:** We beat the market. The price at lock is the pooled judgment of everyone with money on the line — the hardest benchmark we know. Call-for-call against it, our edge is `[Δ]`, 95% interval `[lo, hi]`, clear of zero. Every one sealed before its outcome was known.
- **NEUTRAL:** Edge: matched, not yet beaten. Measured against the market price at lock — the pooled judgment of everyone with money riding on it, one of the hardest benchmarks there is — our advantage is `[Δ]`, but the 95% interval `[lo, hi]` still straddles zero. Matching that price is already an achievement; *beating* it would take an interval that clears zero, and ours doesn't yet — so we won't claim it.
- **FAIL:** Edge: not established. Against the market at lock — the pooled judgment of everyone with money on the line — our 95% interval is `[lo, hi]` and it runs the wrong way of zero. We can't show we beat that price, and claiming otherwise is the one thing this record exists to prevent.

**Process value — did the research pipeline beat a simple baseline? (pipeline − one-shot, 95% CI)**
- **PASS:** The research earned its keep. Our full pipeline beat a one-shot baseline — Brier difference `[Δ]`, 95% interval `[lo, hi]`, clear of zero in our favor. The extra work is doing work.
- **NEUTRAL:** Process value: unproven. Full pipeline vs. one-shot baseline came in at `[Δ]`, interval `[lo, hi]` spanning zero — we can't yet show the extra machinery beats the simple version. Worth knowing about our own engine, and worth saying.
- **FAIL:** Process value: negative. The one-shot baseline matched or beat our full pipeline (`[Δ]`, interval `[lo, hi]`). The extra work isn't paying for itself yet — a result about our own engine we'd rather publish than hide.

---

## BRANCH A — clears cleanly (all three PASS)

*Assembly: intro + Calibration-PASS + Edge-PASS + Process-PASS + closing. Ships: founder post + scoreboard flip + HN + podcasts. The loud one. Trader clock starts. Calm and numerate — the numbers are loud enough.*

**Intro:**
> One thousand forecasts ago we sealed a set of rules for judging ourselves and published their fingerprint — `4787…6519` — while the record was days old and before any scorecard existed to tempt us. We couldn't move the line afterward, and you can check that the rules you're reading are the ones we committed to. The count hit 1,000 resolved. Here's what the sealed scorecard says, computed by the same code we froze at the start:

**[ Calibration-PASS ]**
**[ Edge-PASS ]**
**[ Process-PASS ]**

**Closing:**
> We also got `[k]` of them wrong, and you can see exactly which ones — sealed, timestamped, no edits. That's not a disclaimer; it's the reason the wins are believable. You don't trust an instrument because it sounds confident. You trust it because it's calibrated.
>
> The scoreboard is live and it doesn't reset — everyone who arrives from here walks up to a record that was already true before they got here. **Even on a good day, the discipline holds: next checkpoint, #2,500 resolved, same sealed rules.** We count. Come check the math: *[How we keep score →](dashtra.ai/how-we-keep-score)*.

**Guardrails:** lead with the interval, never the point estimate alone; no "we predicted the future" language; the next milestone is *more record*, not a victory lap.

---

## BRANCH B — real but noisy (≥1 NEUTRAL, none FAIL) · the likeliest landing

*Assembly: intro + the three measure blocks **selected by the actual pass/neutral pattern** + closing. Ships at half volume — bands do the talking, next checkpoint named in-post, no HN/podcast push. This is the honesty brand's home game.*

**Intro (pattern-agnostic — true for any interior of B):**
> The count hit 1,000 resolved and the sealed scorecard is in — judged by the rules we fingerprinted as `4787…6519` when the record was too young to read. Here's the honest read, measure by measure:

**[ Calibration block — PASS or NEUTRAL, per verdict ]**
**[ Edge block — PASS or NEUTRAL, per verdict ]**
**[ Process block — PASS or NEUTRAL, per verdict ]**

**Closing:**
> This is the region we always said was most likely at 1,000 — which is exactly why we named a next checkpoint before we could see the data: **#2,500 resolved, same sealed criteria, same frozen code.** Nothing about the rules changes; we let the intervals tighten and report what they say then, whatever they say.
>
> Honest-and-on-the-record is already rare — almost nobody in this space shows you their misses at all, let alone sealed in advance. We'll take "honest and not yet fully proven" over "confident and unfalsifiable" every time. The record stands; the clock runs to 2,500. *[How we keep score →](dashtra.ai/how-we-keep-score)*.

**Example assembly (B-central: calibration passes, edge neutral, process neutral — B's likeliest interior):** intro → Calibration-PASS → Edge-NEUTRAL → Process-NEUTRAL → closing. *Illustrative only; the real post is assembled from whichever three blocks the verdict selects.*

**Guardrails:** the bands *are* the message — never round an interval away to imply an edge; name #2,500 in the post itself; no apology tone (this is a pre-registered, expected result); volume dial at half.

---

## BRANCH C — below the floor (any one measure FAILS)

*Assembly: intro + the failed measure's FAIL block + the other two measures' actual blocks (pass/neutral, per verdict — C describes the whole card, not just the wound) + forward move + closing. Ships quiet and unconditional. Engine v2 sealed same day. Megaphone off. Fix-or-stop is Product's call; the post's only job is to publish the loss we promised to publish.*

**Intro:**
> We drew our lines while the record was too young to read — sealed as `4787…6519` — and at 1,000 resolved we didn't clear every one of them. We're going to tell you exactly how, because a record you only publish when it flatters you isn't a record. The full card, measure by measure:

**[ FAIL block for the measure that failed ]**
**[ the other two measure blocks — PASS or NEUTRAL, per verdict ]**

**Forward move + closing:**
> We're not going to reframe it. This whole company runs on the idea that you can't selectively trust a record — so we don't get to quietly delete the one that stung. Every one of the 1,000 sealed calls is on the ledger, unedited, including this.
>
> Here's what happens next, by the same discipline: engine v2 is sealed and fingerprinted as of today, and a fresh cohort starts now under the same rules — pinned code, sealed criteria, no moving the line. If the fix is real, the next sealed record shows it, and you'll be able to check that too. If it isn't, you'll see that instead.
>
> They claim, we count. Today the count went against us, and we published it anyway — that's the part we'd ask you to remember. *[How we keep score →](dashtra.ai/how-we-keep-score)*.

**Guardrails:** no spin, no burying the number; state which measure failed and by how much; the forward move is a fact, not a promise of success; megaphone stays off.

---

## Assembly cheat-sheet (for reveal day)

| Verdict pattern (Cal · Edge · Proc) | Branch | Blocks to drop in |
|---|---|---|
| pass · pass · pass | **A** | all three PASS |
| any one or more NEUTRAL, none FAIL | **B** | each measure's PASS *or* NEUTRAL block, matching the card |
| any one or more FAIL | **C** | FAIL block(s) for the failed measure(s) + PASS/NEUTRAL blocks for the rest |

*Only the selection is decided on the day. Every block, intro, and closing was written blind, now.*

---

### Change log

- **rev. 1** — three per-branch posts, date-free.
- **rev. 2** — B rebuilt as an assembled region (nine-block library); #2,500 named in A; hash in all bodies; explainer linked; B's "why the market is hard" clause folded into the Edge blocks.
- **rev. 3 (final)** — Eve's voice pass: B closing made pattern-agnostic ("honest-and-on-the-record"); statistic-as-receipt ordering on Calibration-PASS; "matched, not mastered" nickname removed (we sealed the band, not the label); zero convention standardized across the interval measures ("clear of / straddles / runs the wrong way of zero," never "the line"); Process-PASS reworded off "below zero"; A closing off "best flex"; C intro made exact ("didn't clear every one of them"). Wording frozen and fingerprinted for publication beside `criteria-seal`.
- **rev. 4 (final)** — intro timestamp claims corrected to match ledger history: rules were sealed before any scorecard was computed, not before any resolution existed. Re-sealed; rev. 3 fingerprint remains visible beside it.
