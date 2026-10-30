# The Promise Keepers: Promissory Estoppel in the Supreme Court of India (18 Judgments)

**Team name:** The Promise Keepers

**Team (Section B):** Neha Karanam (23010421084), Nabaparna Kumar (23010421097), Ayushi Shahi (23010421077), Shubhra Singh (23010421115)

**Topic:** The doctrine of promissory estoppel, as applied by the Supreme Court of India to promises made by the State and public bodies.

**Live page:** `index.html` (served through GitHub Pages) | **Data:** `data.xlsx` and `data.csv`

## What we did

We built a dataset of Supreme Court judgments decided between 01-09-2021 and 31-08-2026 in which promissory estoppel is argued against the State or a public body. For every judgment we recorded the citation, date, bench strength, type of case, who brought it, the outcome, who won, the main provision, the issue, the holding in one line, the precedent chiefly relied on, a link to the judgment and the name of the team member who coded it. All dropdown fields follow the controlled vocabulary in the template.

## How we found the judgments

Each team member searched for and selected judgments that fit the topic and the date window. We used the Supreme Court's judgments site and law-reporter databases to find and check cases, and we used legal news sites only to locate them, not as the recorded source. We also followed the precedents cited inside the judgments we read, such as *Motilal Padampat Sugar Mills*, which pointed us to further cases. We aimed to keep a judgment only if the Court considered promissory estoppel in its reasoning, and we used the same wording style for the issue and holding fields so the four coders stayed consistent.

## What the data shows

- **Year chart (`chart1_per_year.png`):** the judgments are spread across all six years, with 2022 the busiest. This reflects where our searching found cases and not the Court's full docket.
- **Outcome chart (`chart2_outcome.png`):** 10 allowed, 7 dismissed and 1 partly allowed. Many allowed matters were appeals brought by the State.
- **Who-won chart (`chart3_who_won.png`):** the State or a public body won 15 of the 18 judgments. Companies won two (*IFGL Refractories* and *CIDCO v. Shishir Realty*) and one judgment was mixed.

Reading the holdings together, a few themes recur. The Court says a promise cannot create a right the statute does not allow. It treats changes to tax and incentive schemes as a matter of legislative or policy power. It lets a proven public interest override a promise. At the same time, the Court has held that promissory estoppel can bind the State, as the *Shishir Realty* and *IFGL* judgments show. The coded precedents also show that the same few earlier decisions, especially *Motilal Padampat Sugar Mills*, are the starting point even when the outcomes differ.

## Limits

Eighteen judgments chosen by four people is a small, non-random sample, so every figure above describes this dataset only. In a few judgments promissory estoppel is one of several grounds, which makes the one-line holding a simplification. Some judgments are linked through law-reporter pages, and we treated the Supreme Court's own copy as the authoritative text.

## Use of AI

We used Claude (Anthropic) as an assistant. It helped us divide the work among four people, suggested leads for finding cases, helped shorten the issue and holding wording, and produced the charts, `index.html` and this README from our data. The case selection, the coding of each judgment and the checking of citations against the judgments are the work of the team members named in the "Coded by" column, and we are responsible for every entry.
