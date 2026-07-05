# Squash Commit Message Template

<type>(<scope>): <subject>

<optional body>

Closes #<issue_number>

---

## Type options

- `feat` - new feature
- `fix` - bug fix
- `doc` - documentation only
- `refactor` - code change that neither fixes a bug nor adds a feature
- `chore` - build process, tooling, etc.
- `test` - adding tests

## Scope

Optional, lowercase, e.g. `devcontainer`, `github`, `ci`

## Subject

Imperative mood, no period, ≤50 chars

## Example output after squash

```
feat(devcontainer): add devcontainer configuration

- introduce devcontainer for consistent development environment
- update README with devcontainer usage

Closes #5
```