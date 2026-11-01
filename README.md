# Rebuttal working document

Beyond Imitation: Filtering On-Policy Distillation by Reasoning Progress

AAAI 2027, submission 11993.

## Review files

The numbering follows the order in the supplied OpenReview PDF:

| Working label | OpenReview reviewer ID | Rating | Confidence | File |
| --- | --- | --- | --- | --- |
| Reviewer 1 | gURK | 5 | 4 | reviewers/reviewer1.tex |
| Reviewer 2 | 4R1c | 5 | 4 | reviewers/reviewer2.tex |
| Reviewer 3 | XU6y | 5 | 4 | reviewers/reviewer3.tex |
| Reviewer 4 | hTMj | 2 | 4 | reviewers/reviewer4.tex |
| Reviewer 5 | YgpD | 6 | 4 | reviewers/reviewer5.tex |

The separate AI Review is retained in reviewers/ai-review.tex. The author's
latest main.tex excludes this appendix from the compiled document.
The Program Chairs' administrative Phase 1 update is not a reviewer report and
is not included.

All review fields, reviewer-supplied references, ratings, and confidence values
are retained. Only PDF extraction artifacts and mathematical typesetting have
been normalized. Reviewer wording, including original spelling, is preserved.
The author's 15 existing responses have been placed beneath their corresponding
weaknesses by matching reviewer ID and comment text, rather than backup order.
The five unanswered weaknesses remain blank for collaborative drafting.
Reviewer 1 also includes the supplied 32-sample results and a concise consolidated
Final Response for Submission. The author confirmed the two datasets as
AIME 2024 (left) and AIME 2025 (right); table headers and the concise final
response now identify both datasets.
The final responses for Reviewers 2-5 and other unwritten boxes remain blank.
The AI appendix also retains blank response boxes. No additional experiments,
truncation analyses, or seed statistics are claimed.
The supplied GPQA-Diamond Markdown table is typeset as a table.

## Edit together in Overleaf

- Use main.tex as the main document and pdfLaTeX as the compiler.
- This revision is on the reviewer1-aime32-20261101 branch; main is unchanged.
- Overleaf does not support switching GitHub branches inside one project.
- To compare this branch with the existing project, create a separate Overleaf
  project using New project > Existing project (.zip) and upload the supplied ZIP.
- The ZIP is a snapshot of this branch and will not automatically sync with it.
- Edit the corresponding reviewers/reviewerN.tex file for each reviewer.
- Edit the text inside each responsebox environment beneath the relevant
  weakness (W1, W2, ...), rebuttal question (Q1, Q2, ...), or overall response.
- Keep the existing responses and fill the blank boxes as further replies
  are drafted.
- Write the final consolidated response for each official reviewer in that
  review's green Final Response for Submission box.

The source OpenReview page is https://openreview.net/forum?id=seo1uoXD9Z .
This working document was transcribed from the PDF supplied by the author.


## Branch provenance

Based on the author's latest main commit b4778ab3f472d8fe2acb574cc3ac57a59080c788.
The author's changes to reviewers 2-4 and the disabled AI appendix are retained.
Changes are reviewer 1's dataset labels and concise result sentence, this
README, the stale AI-appendix reference in the cover text, and one en dash
encoded as a LaTeX double hyphen in reviewer 3 (wording is unchanged).

Official Overleaf documentation:
https://docs.overleaf.com/integrations-and-add-ons/git-integration-and-github-synchronization/github-synchronization#known-limitations
https://docs.overleaf.com/managing-projects-and-files/uploading-a-project#how-to-upload-a-project
