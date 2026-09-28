# Handoff 3: Messages to send

Send each message with its attachment. Everything is labeled **DEMO MODE - synthetic data**.

---

## To Person 1 (attach `demo_ledger.csv`)

Hi! Handoff 3 (the synthetic demo ledger) is ready for your seed. The CSV has 10 synthetic students with initial answer, initial assessment, supported misconception, published intervention (INT-01), retry answer, and retry assessment. It includes Omar, Lina, Adam, Sara and Yousef; the other five are clearly synthetic aliases (Synthetic-01 to Synthetic-05).

By the approved rubric it has exactly **6 correct initial answers** and **9 correct retry answers**, so the app should calculate **60% → 90%, +30 percentage points** from the paired data. One student (Synthetic-05) is still struggling after retry, so we don't imply everyone was fixed. Please have the dashboard compute the percentages from the data, not from typed text.

Please check:
1. Adam and Synthetic-05 have the supported misconception (both link zero velocity to zero acceleration). Omar's bare "0 m/s²" does not, as in Handoff 2.
2. All rows are labeled synthetic and none uses real student data.
3. You control what becomes live or published. I'm not touching app code, schema, or live services.

---

## To Person 2 (attach `intervention_draft.md`)

Hi! Here is the teacher intervention draft (INT-01): a 60-90 second explanation of v = 0 versus a = g downward at the top of a throw, with one simple visual description and one Socratic prompt. It's a draft. The teacher should review and publish the final version through your interface, and Person 1 enforces approval in the live service. It's labeled DEMO MODE - synthetic data. Please keep that label visible. Please don't show student names or answers on the shared view.

---

## To Person 3 (attach `student_safe_wording.md`)

Hi! Here is the student-safe wording and the retry prompt for the demo: the retry prompt, the approved hint, and short feedback lines for each retry result. None of it contains the answer key. Please avoid words like "mastered", because one correct retry doesn't prove lasting mastery, and don't show other students' answers or names. Keep the DEMO MODE - synthetic data label visible.

---

*Next from me: Handoff 4 (pitch notes and rehearsal observations, Day 6).*
