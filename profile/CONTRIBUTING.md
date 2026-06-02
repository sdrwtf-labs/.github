# Contributing to sdrwtf-labs

Welcome! Thank you for contributing to our infrastructure and projects. Please follow these guidelines to keep our repository history clean and meaningful.

## Commit Message Guidelines

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification. Each commit message should consist of a **header**, an **optional body**, and an **optional footer**.

### Header Format
`<type>(<scope>): <short description>`

### Types
- `feat`: A new feature.
- `fix`: A bug fix.
- `docs`: Documentation only changes.
- `style`: Changes that do not affect the meaning of the code (white-space, formatting).
- `refactor`: A code change that neither fixes a bug nor adds a feature.
- `perf`: A code change that improves performance.
- `test`: Adding missing tests or correcting existing tests.
- `chore`: Changes to the build process or auxiliary tools (e.g., `.gitignore`, CI config).
- `ci`: Changes to our CI/CD configuration files and scripts.

### Examples
* `feat(semaphore): add smtp configuration to env`
* `fix(db): resolve postgres connection timeout`
* `docs(readme): update vm installation instructions`
* `ci(runner): update github runner docker image`
* `chore(deps): update docker compose plugin`

### Rules
1. **Use the imperative mood:** "add feature" instead of "added feature" or "adds feature".
2. **Keep it simple:** The header should ideally be under 50 characters.
3. **Breaking Changes:** If your change introduces a breaking change, add an exclamation mark after the type: `feat!(api): change endpoint structure`.
