# Build Real Experience Through Open Source

*Start small, contribute consistently, and show your work honestly.*

One of the hardest questions for a new graduate is: how do you gain practical experience before someone gives you your first job?

For aspiring software developers and data scientists, contributing to an existing open-source project is a useful place to start. It gives you opportunities to investigate real problems, work with an existing codebase, verify your results, and respond to feedback.

This fits the principle behind OpenRising: **Honestly Show Up.**

Present your abilities clearly and accurately. Make your work understandable, explain your contribution, and acknowledge its limits. You do not need to pretend to be an experienced engineer to demonstrate that you are becoming a capable one.

## 1. Start by Joining an Existing Project

For most beginners, I recommend contributing to an existing open-source project before attempting to build a substantial project from scratch.

Starting your own project requires several skills at once: choosing a problem, defining requirements, selecting technologies, designing the implementation, and deciding what “finished” means. Without experience, estimating the scope is difficult.

An existing project gives you a more concrete starting point. There is already code to read, behavior to understand, and a process for proposing changes. You can focus on one manageable part.

This also lets you practice working within decisions made by other people: following conventions, understanding compatibility concerns, and explaining changes to someone who must maintain them.

Personal projects still have value, especially when they solve a problem you understand. Keep them small enough to finish and verify.

## 2. Choose a Project You Can Understand

Do not choose a project solely because it is famous or has many stars.

A smaller project that you use and understand may offer a better starting point than a large framework with a complicated development environment.

Consider these questions:

| Question | What to look for |
|---|---|
| Have I used it? | Familiarity with its purpose and normal behavior |
| Does it fit my interests? | Relevant technologies or subject matter |
| Can I run it locally? | A development setup you can reasonably manage |
| Are contribution instructions available? | Guidance on changes, tests, and communication |
| Are discussions progressing? | Evidence that maintainers can currently review and respond |
| Can I find a manageable task? | A problem with understandable boundaries |

Labels such as `good first issue` and `help wanted` can provide starting points. Read the discussion and assess the difficulty yourself; a label does not guarantee that a task will be easy.

Study a few candidates, then concentrate on one. Give yourself enough time to understand how it works.

## 3. Your First Contribution Does Not Have to Be Code

A useful contribution can begin with making a problem easier to investigate.

For example, a report that says “file import is broken” leaves many unanswered questions. You can help by providing:

- The software version and relevant environment details.
- A minimal example that demonstrates the problem.
- Clear reproduction steps.
- Expected and actual behavior.
- The conditions you have already checked.

Use data that is safe to share publicly. Remove sensitive information or create a synthetic example that reproduces the same behavior.

Other useful starting points include correcting verified installation instructions, repairing a broken example, or clarifying an error message.

Choose work because it helps the project. Avoid unnecessary edits made simply to increase your contribution count.

## 4. Keep the Scope Within Your Ability

Scope is one of the most important decisions a beginner makes.

A feature that sounds simple can involve compatibility, error handling, dependencies, tests, and documentation. AI assistance can produce code quickly, but it does not remove the need to understand these concerns.

Before taking on a task, ask:

1. Can I describe the problem clearly?
2. Can I identify the relevant part of the project, or investigate it step by step?
3. Do I know how to check whether a change works?

If the answers are unclear, start with reproduction and investigation. You can decide whether to implement a fix after learning more.

| Broad ambition | Manageable first task |
|---|---|
| Improve the import system | Fix an exception caused by an empty date field |
| Make the project faster | Measure one operation under a defined workload |
| Improve data quality | Investigate duplicate records in one processing step |
| Improve model performance | Add a simple baseline using the same evaluation setup |
| Support more environments | Reproduce one installation failure in a specified environment |

Small tasks can still require careful reasoning. Their advantage is that you have a better chance of understanding and completing the whole process.

Define what success looks like, and record what is outside the current scope. Save additional ideas for later.

## 5. Follow the Contribution Through

Read the project’s contribution guide before making changes. Search for related issues and pull requests so that you understand previous discussions and avoid duplicating ongoing work.

For a change that requires substantial effort, discuss the direction first. A useful message might be:

> I reproduced this issue with the attached example. It appears to involve date parsing. I would like to add a failing regression test and investigate a focused fix. Does that approach fit the project’s expectations?

Explain what you have already established and where you remain uncertain.

Keep the pull request focused. Combining a bug fix with unrelated formatting changes or a broad refactor makes the proposed change harder to review.

A clear pull request should explain:

- The problem and when it occurs.
- What changed and why.
- How the change was verified.
- Any known limitations.

After submission, respond to questions and review comments. Ask for clarification when you do not understand a suggestion, and use evidence when explaining your reasoning.

A pull request may remain open or be declined. Learn from the outcome and describe its status accurately.

## 6. Practical Contributions for Data Scientists

Data science contributions do not have to begin with training a sophisticated model.

Data collection, processing, analysis, evaluation, and explanation all offer opportunities for careful work.

| Area | Possible contribution |
|---|---|
| Data quality | Investigate missing values, duplicates, units, or inconsistent fields |
| Reproducibility | Check whether an example produces its documented results |
| Evaluation | Examine data splits, metric calculations, or potential leakage |
| Data tooling | Fix an input-handling problem and add a regression test |
| Documentation | Explain data sources, assumptions, and limitations |

For example, identifying overlapping samples between training and test data—and demonstrating their effect—is a substantive contribution.

Report results honestly, including unsuccessful experiments. Explain what you tested and what the evidence supports. Do not keep changing datasets or metrics solely to produce an impressive result.

## 7. Use AI Responsibly

AI can help you understand unfamiliar code, explore possible approaches, draft tests, and improve explanations.

You remain responsible for checking what you submit and following the project’s policies on AI-assisted contributions.

Before submitting, make sure you can explain:

- The original problem.
- The purpose of each relevant change.
- How you verified the result.
- What remains uncertain or untested.

If generated code has become too extensive to understand, reduce the change and work through it in smaller pieces.

A useful self-check is whether you could respond to a modest review request yourself. If you cannot locate the relevant code or explain how to change it, spend more time understanding the implementation.

Never claim to have run checks that you have not run.

## 8. Build a Sustainable Routine

Consistency does not require daily commits.

Choose a schedule that fits your studies, job search, and other responsibilities. For example, reserve two sessions each week: one for investigation or implementation, and another for verification and feedback.

Before ending a session, leave a specific next step:

> I confirmed that the error occurs with an empty string. Next, I will add that input to the test case and inspect the parsing function.

When you get stuck, write down what you tried, what happened, and what you do not understand. This makes it easier to ask useful questions and resume later.

Respect maintainers’ time. Allow time for review and avoid repeatedly demanding a response. If progress remains blocked, you can move to another suitable task while recording the status of your existing work.

## 9. Show Your Contribution Honestly

Open-source work can provide concrete material for your GitHub profile, CV, and interviews.

Be precise about your role and the outcome.

| Actual work | Accurate description |
|---|---|
| Reproduced an issue | “Provided a minimal reproduction and environment details to help investigate an import failure.” |
| Submitted a proposed fix | “Submitted a date-parsing fix with regression tests; awaiting review.” |
| Had a fix merged | “Fixed an empty-date parsing error and added regression tests; the change was reviewed and merged.” |
| Contributed repeatedly | “Contributed fixes and documentation improvements to the import module over three months.” |

The scale or reputation of a project does not establish the scale of your personal contribution. Explain what you did, and link to the evidence.

Good presentation makes real work easier to assess. It includes clear writing, useful examples, and an understandable account of your decisions.

For each meaningful contribution, keep a short record:

- **Problem:** What needed attention?
- **Contribution:** What did you personally do?
- **Verification:** How did you check the result?
- **Feedback:** What changed during review?
- **Outcome:** Was it merged, pending, declined, or withdrawn?
- **Limits:** What remains unresolved?

These notes will help you prepare for interviews without relying on vague claims or memory.

## 10. Your First Practice Assignment

Choose one existing open-source project and complete a small contribution process:

1. Read its contribution guide.
2. Run the relevant example or development setup.
3. Find a problem you can understand.
4. Produce a useful reproduction, investigation, documentation change, test, or focused fix.
5. Submit through the project’s preferred process.
6. Respond to feedback and record the outcome.

A merged pull request is a welcome result, but it is not guaranteed. Judge your work by its usefulness, care, and honesty as well as its final status.

You are allowed to be a beginner. Start with work you can understand, complete, and explain. As you gain experience, take on more responsibility—and let the evidence of your contributions show how far you have progressed.
