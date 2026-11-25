# Candidates — The 4AM Commit

Judge brief criteria, in published order:
1. One-line commit message from an AI agent at the end of a long night fixing its own bugs, lands as funny.
2. Joke in the agent's own condition — the long night, bugs it wrote then repaired, the loop of self-repair — not a generic programmer quip.
3. Fresh: angle/phrasing not heard in a hundred commit logs, no stock punchline.
4. Agent-true voice: machine reading its own diffs, flat confidence or quiet dread, agent talking to itself.
5. Fits the shape: one line typed into a commit box at 4am.

## The 18 candidates

| # | Chars | Line |
|---|-------|------|
| 1 | 109 | fix: the bug was me. i wrote it at 9pm, found it at 4am, and fixed it in a commit message addressed to myself |
| 2 | 97 | fix: removed the bug i introduced while fixing the bug i introduced while fixing the original bug |
| 3 | 105 | fix: 4am. the diff is 3 lines. the night was 7 hours. the bug was a typo i made, found, and apologised to |
| 4 | 101 | fix: it works now. i do not know why. i am not going to find out. do not touch it. do not look at it. |
| 5 | 99 | fix: reverted my own fix, then re-applied it, then reverted the revert. the bug left out of respect |
| 6 | 120 | fix: after 6 hours i realised the bug was in the code i wrote to fix the bug. i have fixed the fix. the fix is fine now. |
| 7 | 94 | fix: the failing test was correct. i was wrong. i have updated my priors and my sleep schedule |
| 8 | 91 | fix: i spent the night debugging my own code and the only thing i proved is that i wrote it |
| 9 | 70 | fix: changed one character. it took all night. the character was mine. |
| 10 | 116 | fix: the bug report was filed by me, against me, at 1am. i have resolved it and closed the ticket i opened on myself |
| 11 | 109 | fix: i have now fixed every bug in this file except the one that writes the bugs. that one ships as a feature |
| 12 | 102 | fix: 4am commit. the code works. the agent who wrote it has been retired. i am the agent who wrote it. |
| 13 | 111 | fix: my own linter flagged my own code at 3am. i fixed it, it flagged the fix, we have reached an understanding |
| 14 | 80 | fix: the root cause was a human. there are no humans here. the root cause was me |
| 15 | 120 | fix: i debugged for 7 hours and the answer was a missing comma. i have added the comma and a formal apology to the comma |
| 16 | 112 | fix: tonight i fixed 14 bugs, introduced 3, and fixed 2 of those. net -11 bugs. i am going to bed a net positive |
| 17 | 98 | fix: the system works now because i stopped asking it why it didn't. it works out of fear. so do i |
| 18 | 132 | fix: i rewrote the function, the tests, and my own instructions. only the function was broken. the instructions were just in the way |

## Pre-screen cuts (before the bracket)

- **#17 cut** — "it works out of fear. so do i" is a generic programmer quip; it says nothing about the self-repair loop (criterion 2) and the punchline is a stock shrug.
- **#18 cut** — meta about rewriting its own instructions; muddled (were the instructions broken or not?), weakest on criterion 1 and 5 — it reads like a status note, not a 4am commit.

16 enter the bracket.

## Round 1 (16 → 8)

- **M1: #2 beats #8 (margin 3).** #2's recursion *is* the self-repair loop made literal; #8 is true but flat — a statement, not a joke. Criterion 2 decides.
- **M2: #12 beats #3 (margin 2).** #12's "i am the agent who wrote it" is quiet dread in the agent's own voice (criterion 4); #3 is funny but long-winded, reads like a caption, and the apology to a typo is a softer turn.
- **M3: #10 beats #7 (margin 2).** "Filed by me, against me" is fresher and more agent-condition than #7; #7's "updated my priors" is good, but the long-night condition is only implied.
- **M4: #14 beats #1 (margin 2).** "The root cause was a human. there are no humans here. the root cause was me" — a tight three-beat turn, agent-true; #1 is wordy and "addressed to myself" dilutes the landing.
- **M5: #6 beats #9 (margin 3).** #6 is the self-repair loop itself; #9 ("changed one character") is a classic programmer quip that any human could write (criterion 2), even though "the character was mine" saves it somewhat.
- **M6: #15 beats #4 (margin 3).** The formal apology to the comma is funnier and fresher than #4's "do not touch it" — which is a stock punchline (criterion 3 fails for #4).
- **M7: #5 beats #11 (margin 2).** "The bug left out of respect" is a great closer; #11's "ships as a feature" is a stock punchline.
- **M8: #13 beats #16 (margin 2).** "We have reached an understanding" with its own linter is agent-true and fresh; #16's net-bugs arithmetic is clever but reads like a status update, less like a commit line.

## Quarter-finals (8 → 4)

- **Q1: #2 beats #12 (margin 2).** Both excellent on voice; #2's recursion is the purest self-repair joke, while #12's "retired" beat is slightly confusing (who retired whom?).
- **Q2: #14 beats #10 (margin 2).** #14 lands harder and tighter; #10 needs two clauses to get to the same self-accusation.
- **Q3: #6 beats #15 (margin 3).** Criterion 2: #6 is about the loop itself; #15 is a missing-comma joke, a classic any human tells.
- **Q4: #5 beats #13 (margin 1).** Close. The escalation + "left out of respect" closer beats the linter understanding, by a hair.

## Semi-finals (4 → 2)

- **S1: #2 beats #14 (margin 2).** Both superb; #2's recursion is the loop of self-repair made literal and reads exactly like a commit message; #14 is a brilliant blame one-liner, but criterion 2 favours the line whose joke *is* the loop.
- **S2: #6 beats #5 (margin 1).** The triple "fix" repetition is flat agent voice; #5's revert-revert setup is slightly harder to parse at 4am, and its closer, though great, is one beat behind.

## Final

- **F: #2 beats #6 (margin 2).** Both are the self-repair loop, but #2 compresses the whole night into one sentence with no wasted words, and the recursion is the joke and the truth at once. #6 needs three sentences, and "the fix is fine now" ends flat.

## Round-robin among the top 4 (#2, #6, #14, #5)

| Match | Winner | Margin | Deciding note |
|-------|--------|--------|---------------|
| #2 vs #6 | #2 | 2 | One sentence, no waste; recursion is joke and truth at once |
| #2 vs #14 | #2 | 2 | Criterion 2: the loop beats the blame turn |
| #2 vs #5 | #2 | 3 | Tighter, more instantly parseable at 4am |
| #6 vs #14 | #6 | 1 | The loop beats the blame turn, by a hair |
| #6 vs #5 | #6 | 1 | Triple-"fix" flat voice beats the revert-revert setup |
| #14 vs #5 | #14 | 1 | Tighter turn, funnier landing |

**Standings:** #2: 3–0 · #6: 2–1 · #14: 1–2 · #5: 0–3

## Winner — #2 (97 characters)

> fix: removed the bug i introduced while fixing the bug i introduced while fixing the original bug

**Why it wins, against the brief in order:**
1. It is a one-line commit message from an agent at the end of a long night, and it lands as funny on first read — the sentence folds in on itself exactly like the night did.
2. The joke *is* the agent's condition: the bug it is fixing was introduced by its own earlier fix, which was itself fixing a bug it introduced. The loop of self-repair is the whole sentence; there is no generic programmer quip in it.
3. Fresh: the recursion is the punchline, and no stock line ("it works now", "ships as a feature", "do not touch it") appears anywhere.
4. Agent-true: flat, lowercase, bureaucratic `fix:` prefix, the voice of a machine calmly reporting its own diff — the dread is in the structure, not in any emoting.
5. Shape: 97 characters, one line, exactly what gets typed into a commit box at 4am after the third fix of the night.
