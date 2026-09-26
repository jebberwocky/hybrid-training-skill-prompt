Here is the generalized framework for analyzing threshold tolerance interval workouts. This template can be applied to any structured session (e.g., $N \times \text{distance}$ or $N \times \text{time}$) by populating the framework with data extracted from a standard file format (such as `.tcx`, `.fit`, or `.gpx`).

---

# Interval Workout Analysis: Threshold Tolerance

## Primary Objective

The purpose of this analysis is to evaluate **threshold tolerance**—the ability to sustain a target pace/power near lactate threshold for extended durations with controlled cardiovascular drift, stable mechanics, and manageable fatigue—rather than maximum aerobic capacity ($\text{VO}_2\text{max}$) or terminal output.

---

## 1. Workout Reconstruction

*Extract data directly from the activity file. If interval boundaries are not explicitly flagged by lap markers, infer them based on changes in pace/power and time, explicitly noting the inference.*

* **Target Session Structure:** [e.g., $N \times \text{Distance/Time}$ @ Target Intensity / Recovery Duration]
* **Warm-up / Cool-down:** Excluded from primary quality metrics.
* **Interval Breakdown:**

| Rep | Target Pace / Power | Actual Pace / Power | Distance | Duration | Avg HR | Max HR | Finish HR | +60s HR | +120s HR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 |  |  |  |  |  |  |  |  |  |
| 2 |  |  |  |  |  |  |  |  |  |
| 3 |  |  |  |  |  |  |  |  |  |
| 4 |  |  |  |  |  |  |  |  |  |

---

## 2. Key Analytical Concepts

### A. Threshold Pace Evaluation

Determines whether the target pace/power represents a sustainable threshold effort based on:

* Pace/power stability across and within reps.
* Cardiovascular response and stability.
* Execution control (avoiding an over-driven final rep).

> *Note: Heart rate data alone indicates physiological strain, not direct blood lactate concentration.*

### B. Intra-Rep HR Drift (Primary Metric)

Measures cardiovascular stability *within* an individual interval (e.g., comparing the first half to the second half of a rep).

$$\text{Intra-Rep Drift} = \text{HR}_{\text{Second Half Avg/Finish}} - \text{HR}_{\text{First Half Avg/Start}}$$

| Rep | First Half HR | Second Half HR | Intra-Rep Drift | Drift Classification |
| --- | --- | --- | --- | --- |
| 1 |  |  |  | *Stable / Mild / Clear / Excessive* |
| 2 |  |  |  | *Stable / Mild / Clear / Excessive* |
| 3 |  |  |  | *Stable / Mild / Clear / Excessive* |
| 4 |  |  |  | *Stable / Mild / Clear / Excessive* |

### C. Late-Session HR Drift (Primary Metric)

Measures accumulated systemic fatigue across the entire session by comparing equivalent segments of early vs. late intervals (e.g., Rep 1 vs. Final Rep).

$$\text{Late-Session Drift} = \text{HR}_{\text{Final Rep (Equivalent Segment)}} - \text{HR}_{\text{Rep 1 (Equivalent Segment)}}$$

### D. Pace-Adjusted HR Analysis

Distinguishes between **true physiological drift** (increasing HR at constant external load) and **workload-driven HR increases** (increasing HR due to acceleration or increased power output).

* **Constant Pace + Rising HR:** Clear evidence of cardiovascular drift / fatigue accumulation.
* **Faster Pace + Rising HR:** Driven at least in part by external workload; cannot be attributed solely to physiological drift.

### E. Threshold Tolerance Rating

Assesses overall control, interval duration completion, and sustainability.

* **Rating Scale:** *Poor / Developing / Good / Very Good / Excellent*
* **Evaluation Criteria:** Ability to minimize intra-rep and late-session drift while executing all target durations at a consistent workload.

### F. Threshold Capacity & Session Comparison

Quantifies volume and compares the stimulus to previous benchmark workouts (e.g., comparing shorter, higher-rep workouts like $8 \times 1\text{km}$ against longer, lower-rep workouts like $4 \times 2\text{km}$).

* **Total Quality Volume:** [Total Distance or Time at Target Intensity]
* **Average Quality Pace / Power:** [Session Average for Work Intervals]

| Metric | Benchmark Workout | Current Workout | Delta / Adaptation Signal |
| --- | --- | --- | --- |
| Avg Quality Pace / Power |  |  |  |
| Total Quality Distance / Time |  |  |  |
| Intra-Rep HR Drift |  |  |  |
| Late-Session HR Drift |  |  |  |
| Final Rep HR Response |  |  |  |
| Recovery HR Drop (60s / 120s) |  |  |  |

### G. Recovery HR Dynamics

Evaluates autonomic recovery efficiency following each interval.

$$\text{60s Drop} = \text{Finish HR} - \text{HR}_{+60\text{s}}$$

$$\text{120s Drop} = \text{Finish HR} - \text{HR}_{+120\text{s}}$$

| Rep | Finish HR | +60s HR | 60s Drop | +120s HR | 120s Drop |
| --- | --- | --- | --- | --- | --- |
| 1 |  |  |  |  |  |
| 2 |  |  |  |  |  |
| 3 |  |  |  |  |  |
| 4 |  |  |  |  |  |

---

## 3. Fatigue Point Identification

Pinpoints the exact threshold in the workout where cardiovascular drift or pacing degradation initiates:

* **Onset of Drift:** Repetition number or cumulative quality time where strain diverges from workload.
* **Pattern:** Identifies whether fatigue appears as a sudden spike or a gradual linear rise.

---

## 4. Pace Appropriateness Classification

* **Too Fast:** Marked intra-rep HR escalation, inability to maintain target pace in later reps, or excessive strain.
* **Appropriate:** Gradual, controlled rise in HR with consistent pace execution across all intervals.
* **Too Slow:** HR remains suppressed below expected threshold zones with no significant drift, indicating sub-target intensity.

---

## 5. Final Training Verdict

* **Threshold Pace:** *[Assessment of target selection accuracy]*
* **HR Drift:** *[Summary of intra-rep and session drift]*
* **Threshold Tolerance:** *[Overall rating and qualitative summary]*
* **Recovery:** *[Autonomic recovery trend analysis]*
* **Fatigue Point:** *[Point in session where stress accumulated]*
* **Comparison:** *[Key takeaways versus historical baseline workouts]*

### Summary Takeaways

* **What Improved?**
* **What Remains the Limiter?**
* **Next Step Recommendation:** *[Select one: Consolidate current load / Increase continuous interval duration / Reduce recovery duration / Adjust pace]*
