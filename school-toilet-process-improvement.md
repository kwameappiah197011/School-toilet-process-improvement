# Case Study: Securing a Pupil Toilet Area During Lesson Time

**Type:** Process improvement (root cause analysis and to-be process design)
**Setting:** Secondary school, Key Stage 3 girls' toilets
**Role:** Business Analyst (self-initiated, drawn from a real situation at my workplace)
**Status:** Proposed process. Not yet piloted or validated with stakeholders.

---

## 1. Problem Statement

> Almost daily, the KS3 girls' toilet is left unlocked after break times and student key use, allowing pupils to hide there during lessons. This causes missed learning, a safeguarding concern, and wasted staff time chasing the issue.

## 2. Stakeholders

| Stakeholder | Interest / impact |
|---|---|
| Teachers | Pupils missing from lessons |
| Reception | Issues keys, receives complaints, owns the key sign-out sheet |
| Site team (3 people) | Responsible for locking before/after breaks |
| Cleaners | Clean after each break, expected to lock afterwards |
| Pastoral / behaviour lead | Owns pupil behaviour and attendance concerns |
| Headteacher's PA | Central record-keeping, reception's line manager |
| Head of site team / cleaning manager | Accountable for staff processes |

## 3. As-Is Process

- Two breaks a day (morning break and lunch).
- Site team opens and locks the toilets before and after each break.
- Cleaners clean after each break and should lock when finished.
- Pupils can sign out a key from reception between lessons if they need the toilet.
- **No step verifies that the door is actually locked after any handover.** Reception accepts a returned key without knowing the state of the door.

### Observations

- Three groups (site team, cleaners, pupils) touch the same door, with no single owner of the final lock.
- Skipping lessons tends to happen around lesson changes (the bell rings every 45 minutes).
- Reception's complaint that staff aren't locking the door was a **claim, not yet a verified fact**. No record existed to confirm or disprove it.

## 4. Root Cause Analysis (5 Whys)

Two branches were identified: staff and pupil key use. The staff branch was analysed first.

| # | Why? | Answer |
|---|---|---|
| 1 | Why can pupils get into the toilet during lessons? | It is left unlocked, either by a pupil who signed out a key or by site team/cleaners. |
| 2 | Why do site team leave it unlocked? | They assume the cleaners will lock it after cleaning. |
| 3 | Why do they assume that? | The routine changed: site team used to lock straight after break, then stopped once cleaners started going in. The change was never formally agreed. |
| 4 | Why do cleaners leave it unlocked? | They assume the site team will come back and lock it. |
| 5 | Why does neither group know who owns the final lock? | Neither group knows who owns the final lock. |

**Root cause:** There is no single named owner for the final lock, and no check that confirms it has been done.

### A loop in the problem

Each group relies on the other to finish the job:

- Site team leave it open because they assume cleaners will lock it.
- Cleaners leave it open because they assume site team will lock it.

"People forget" and "they don't work as a team" were rejected as root causes. They describe people, are hard to prove or fix, and would read as blame in a report. The ownership gap is a process issue that can be fixed.

## 5. To-Be Process

| Step | When | Who | Action |
|---|---|---|---|
| 1 | 11:15 / 2:05 (as pupils go to class) | Site team | Lock the toilets. |
| 2 | By 11:50 (and afternoon equivalent) | Cleaners | Unlock, clean, and **own the final lock**. |
| 3 | After the lesson change (about 12:05) | Site team | Check the toilets, tick the clipboard, lock anything left open. |
| 4 | Key out 10+ minutes during lesson time | Reception | Radio the site team (whoever is free; named backup if no answer) and log it on EVERY, the school's issue-logging system. |
| 5 | End of day | Reception, headteacher's PA | Compare the site team clipboard with the key sign-out sheet; flag inconsistencies. |

### Escalation

- **Staff process lapses** go to the head of site team and the cleaning manager.
- **Pupil behaviour issues** (hiding, missing lessons) go to the pastoral/behaviour lead.

### Design decisions

- **Ownership sits at the end of the cleaners' task**, since they are the last people physically in the room.
- **Site team verifies, cleaners own.** Ownership is not split, but there is a backup to remove a single point of failure.
- **The verification check is timed after the cleaners' deadline** so it doesn't interrupt legitimate cleaning.
- **The 12:05 check does two jobs:** it verifies the lock and coincides with the lesson change, when pupils are most likely to slip away.
- **Event-based triggers** (bell, key out of reception for 10+ minutes) were preferred over count-based ones ("every 10 pupils"), which would need reception to keep a running tally.
- **The clipboard is kept with the site team**, not on the toilet door, so pupils cannot tamper with it.
- **Existing roles and systems are reused** (radios, the PA's record-keeping, EVERY) rather than adding new equipment or roles.

## 6. Reconciliation: Telling the Two Branches Apart

Comparing the site team clipboard with reception's key sign-out sheet lets the two root-cause branches be separated using evidence rather than assumption:

- Found open, **with** a recent key sign-out: likely a pupil left it open.
- Found open, **with no** key sign-out: likely a missed lock by staff.

This shows which cause is bigger, so effort goes where it matters.

## 7. Known Weaknesses and Assumptions

| Weakness / assumption | Mitigation / note |
|---|---|
| Site team may be busy and unable to answer radio calls. | Named backup: if no answer within a few minutes, reception tries the next person. |
| Cleaners are not supervisors; they may not know what to do if they see a pupil go in during the cleaning window. | Needs agreeing with the cleaning manager. |
| Reception may be too busy to notice a key out for 10+ minutes. | Decide who covers when reception is under pressure. |
| Up to about 45 minutes can pass between lesson-change checks. | Cleaner presence (11:15 to 11:50) shortens the unwatched window; the key-out trigger covers the rest. |
| End-of-day reconciliation is good for patterns but slow. | The radio check and 12:05 check provide same-day coverage. |
| Site team may not be able to check at every lesson change. | Prioritise the changes where skipping is most common. |
| This analysis is based on one person's understanding of how each group thinks. | Confirm with site team, cleaners and reception before implementing. |

## 8. Measuring Success

Proposed measures, to be baselined before launch and reviewed after a few weeks:

- **Times found unlocked at the 12:05 check** (per week), before vs after.
- **Key sign-outs not returned within 10 minutes**, and how many were followed up.
- **Reported pupil absences from lessons linked to the toilet area.**
- **Clipboard completion rate** (are checks actually being done and ticked?).
- **Patterns:** day of week, time of day, staff shift, to spot new causes.

Because the problem is currently "almost daily" (an impression, not a measured figure), the clipboard also creates the baseline data that the current process lacks.

## 9. Sample Tick Sheet

| Date | Break | Locked at end of break (site team, initials/time) | Cleaners finished and locked by 11:50 (initials) | Post-lesson-change check: locked? Y/N | Notes |
|---|---|---|---|---|---|
| | | | | | |

## 10. What I Learned

- A symptom ("the door is left open") is not a problem statement. Who is affected, what goes wrong and what it costs are all needed.
- Claims need testing before they are built on.
- Good root causes point at the process, not at people.
- When a step moves between groups, the handover needs redesigning, or the old safety net disappears.
- Naming the weakness of each fix, including my own, makes the final process more testable and more credible.

## 11. Next Steps (if implemented)

1. Validate the as-is process and assumptions with site team, cleaners and reception.
2. Agree ownership and times with the head of site team and cleaning manager.
3. Pilot for 3 to 4 weeks, recording data on the clipboard.
4. Review results against the baseline and adjust.

---

*Note: This case study is based on a real situation but has been generalised. No pupil, staff or school identifiers are included.*
