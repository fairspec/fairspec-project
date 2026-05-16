# Fairspec

Meta-repository that ties together all Fairspec repos. Each subdirectory listed below is its own git repository, gitignored from this meta-repo.

## Repos

- `fairspec-application`
- `fairspec-cardealer`
- `fairspec-extension`
- `fairspec-python`
- `fairspec-standard`
- `fairspec-typescript`
- `vitest-polly`

## Rules

- **Never commit unless asked to**
- **Never add co-authored by Claude Code to commits!**
- **Never push main or pull requests to origin unless asked to**
- Use `git -C <repo>` instead of `cd <repo> && git` for git commands in nested repos
- Each nested repo has its own `AGENTS.md` with project-specific commands and conventions — read it before working in that repo
