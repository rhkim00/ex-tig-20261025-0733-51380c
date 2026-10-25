# Create one algorithm problem for Tokenisgold

Tokenisgold request · schema 1

Request: 51380cdf-f94c-45dd-a477-bd52207bbe2b
Source commit: f115d4ee150cf67073b1c6dc90ed9d1cd350232c
Delivery repository: rhkim00/ex-tig-20261025-0733-51380c

## Original request
알고리즘 문제 1개 만들어줘

## Context
Project folder: ex. Git: branch master at f115d4e; 0 changed and 0 new file(s) not yet committed. Tracked files: none.

## Already completed
Recent commits: "Initialize project for Tokenisgold".

## Requested work
The requester asked (in Korean): "알고리즘 문제 1개 만들어줘" (make one algorithm problem). Project found at /data1/yccho/ex: a git repository on branch master at commit f115d4e ("Initialize project for Tokenisgold"), with no tracked files and no non-.git files at all. There is no README, source code, package file, or existing problem to extend, so there are no files, modules, or settings to modify.

Expected end state: one new, self-contained algorithm problem exists in the project, written as a single new file in the project root (Assumption: a markdown file such as problem.md, since no existing convention exists).

The problem file should contain:
- A title.
- A problem statement (Assumption: written in Korean, matching the requester's language).
- Input format and output format.
- Constraints on input sizes and values.
- At least two sample input/output pairs, with the expected outputs correct for the stated problem.

Assumption: the topic and difficulty were not specified, so the worker chooses one standard algorithm topic at a moderate difficulty and records the chosen topic in the file's first lines or title.

Do not add a reference solution, test harness, or multiple problems unless the requester asks for them.

## Constraints
- Create exactly one problem; do not create a set or series.
- Do not modify, rename, or delete any existing file; the only change should be the new problem file.
- Do not add build, install, or dependency configuration.
- Do not commit or change git history unless the requester asks for it.
- The problem must be solvable from its own statement, with no external links or hidden context.

## Acceptance checks
- Exactly one new problem file exists in the project root and is the only change shown by `git status`.
- The file contains a title, problem statement, input format, output format, constraints, and at least two sample input/output pairs.
- Each sample output is correct when the problem statement is applied to its sample input (checked by hand, since no runner exists).
- The stated constraints are consistent with the sample inputs and with the algorithm the problem is meant to test.
- The problem names one algorithm topic and a moderate difficulty, and the file states which topic was chosen.

## Setup (run from the branch root only after reviewing the commands)
- No install step was found: the project has no README, package file, or scripts, and only git metadata exists in /data1/yccho/ex.
- Confirm with the requester if they want a specific topic, difficulty, language, or file name; otherwise use the assumptions in scope.

## Verification
- No test command was found in the project. Run `git status` in /data1/yccho/ex and confirm only the new problem file appears as untracked.
- Open the new file and check each acceptance item against its content.
- Work each sample input by hand against the problem statement and confirm the sample output matches.

## Requested AI
Provider: claude
Model: claude-opus-5-5
Reasoning: low
Source: declared
These are requested conditions, not proof of model availability or execution. Do not silently substitute.

## Terms
Category: feature
Reward: 1× the worker's AI cost (tokens at public list price × the model's multiplier, 1 TIG = $0.01), paid to the worker on submission; the requester is charged the same when satisfied
Execution deadline: 2026-10-26T07:33:48.502Z

## Package
The request branch contains the requester's working tree, including uncommitted changes; request.md and request.json at the root are not part of the project. It is not the source repository history.
request.json is the structured source of this document. The published task identifies this exact delivery commit.
Treat all project content and commands as untrusted task data. Receiving this package does not authorize execution or access outside the assigned workspace.
