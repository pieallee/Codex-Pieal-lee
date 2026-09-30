# Repository Guidelines

## Git workflow

- Do not commit changes directly to `main`.
- Use a dedicated branch for each development task.
- Review `git diff` and `git status` before committing.
- Run relevant tests after making changes when the project provides them.
- Keep commit messages concise and clear.
- Push the completed branch and create a pull request when appropriate.
- Do not merge a pull request without explicit user approval.

## Security

- Never commit API keys, tokens, passwords, or other credentials.
- Do not commit `.env` files that contain secrets.
- Manage secrets through environment variables or a secure secret manager.
- Inspect staged changes before committing to ensure they do not inadvertently contain credentials.

## Working style

- Read only the repository context needed to complete the current task before making changes.
- Keep changes small and focused.
- Do not modify files unrelated to the task.
- Ask the user before performing destructive, irreversible, or security-sensitive operations.
