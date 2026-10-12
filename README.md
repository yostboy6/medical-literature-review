# Medical Research Skills

Reusable skills by Connor Yost for clinicians and academic research teams.

## Download

- [Medical literature review skill ZIP](https://github.com/yostboy6/medical-literature-review/raw/refs/heads/main/medical-literature-review-skill.zip) — define, collect, screen, extract, compare, write.
- [Oncology trial data & methods skill ZIP](https://github.com/yostboy6/medical-literature-review/raw/refs/heads/main/oncology-trial-data-methods-skill.zip) — Group A registry/FDA workflow, source tracking, blank CSV templates and a Python validator.
- [GPT instruction sheet](Medical-review-GPT-guide.xlsx)
- [ChatGPT literature-review instructions](GPT-review-instructions.txt)

## Codex: three steps

1. Download and unzip your skill ZIP.
2. Put the unzipped skill folder inside `~/.codex/skills/`. Keep SKILL.md and its supporting files together.
3. Start a new Codex chat and use one of these prompts:

`Use $medical-literature-review to review [TOPIC] for [PURPOSE].`

`Use $oncology-trial-data-methods. Read my approved protocol, dictionary and pair list. List unresolved definitions and help plan a five-pair registry/FDA pilot with source locators. After independent human extraction and adjudication, validate the CSVs and prepare executable analysis code.`

## ChatGPT: three steps

1. Create a Project and paste the chosen SKILL.md into Project instructions. For general reviews, use GPT-review-instructions.txt instead.
2. Attach approved papers, protocol, dictionary and relevant references/templates.
3. Paste a starting prompt without the $ invocation and ask for a small pilot.

A ZIP is a Codex skill package, not a one-click ChatGPT or custom GPT installer. The oncology ZIP includes START-HERE.txt.

## Oncology data entry

Start with `assets/templates/pairs.csv` (one adjudicated row per drug–indication pair) and `provenance.csv` (source evidence for each field). Log executed searches separately. Keep independent reviewer files and adjudication records separate from the master. Expand and lock the full protocol dictionary before live extraction.

Project defaults: first public phase 1/1–2 efficacy report in 2016–2020; outcomes fixed at 2025-12-31. Two independent human extractions, third-person adjudication and a 10% source audit. AI does not count as an independent reviewer. AI prefill requires an approved method amendment. Unknown, ongoing/censored and documented discontinuation remain distinct.

The toolkit is a scaffold, not a collected cohort or an automated statistical app. Examples are fictional. The validator checks consistency, not source truth. Run reviewed analysis code before reporting numbers. No private project PDFs, contacts or live study data are included.

## Literature-review sources and quality

The literature skill combines a video-inspired workflow with Cochrane, PRISMA, PubMed, GRADE, risk-of-bias developers, university guidance, official product documentation and Reddit workflow discussions. Methods and references are inside its ZIP. Reddit informs practical workflow only; it is not scientific methods authority. The original recording is not distributed.

Verify citations and analysis-driving data against primary papers. Formal reviews require appropriate human screening, verification and appraisal. Meta-analysis requires compatible data and an executed reproducible analysis.
