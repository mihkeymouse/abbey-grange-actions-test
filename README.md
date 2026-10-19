# The Adventure of the Abbey Grange

*A Sherlock Holmes mystery played through Git.*

You are Sherlock Holmes. Dr. Watson has kept a version-controlled record of a quite remarkable case.

Investigate the evidence, form your deductions and test them through Git.

## How to Play

Explore Watson's records using:

```bash
git log --oneline
git show HEAD
git diff HEAD~1 HEAD
```

New case-files will appear under `case/` as the investigation advances

Write your answer in `deduction.txt`,then commit  and push it.

Once GitHub Actions completes, retrieve the next record using:

```bash
git pull --rebase
```

## Begin the Investigation

Open `deduction.txt` and enter:

```text
G0=START!
```

Then run:

```bash
git add deduction.txt
git commit -m "START!"
git push
```

**The game is afoot!**
