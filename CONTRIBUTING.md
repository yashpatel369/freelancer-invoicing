# Contributing

## Working agreement

- Branch from `main` using this name format: `feature/<issue-number>-short-name`
- Write commit messages like `feat: add login form` or `fix: correct tax rounding`. The word before the colon says what kind of change it is:
  - `feat:` a new feature
  - `fix:` a bug fix
  - `chore:` setup or maintenance
  - `test:` adding or changing tests
  - `docs:` documentation only
- Every change goes through a pull request that links its issue (write "Closes #12" in the PR description)
- `main` is protected: no direct pushes, and all automated checks must pass before merging
- Definition of done for every issue:
  - Acceptance criteria are met
  - Tests are added
  - Automated checks are green
  - Docs are updated if behaviour changed

## Pull request checklist

- [ ] Linked issue
- [ ] Tests added or updated
- [ ] No secrets or real personal data committed
- [ ] Screenshots included for UI changes
- [ ] Database migration included and reversible (if the schema changed)