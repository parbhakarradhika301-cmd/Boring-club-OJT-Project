# Contributing to Boring Club Portfolio

Welcome to the Boring Club team! As part of the Dev Agency Distributed Workflow, we enforce a strict Git workflow to simulate a real-world agency contributing to a shared codebase.

## Branching Strategy

The `main` branch is **protected**. You cannot push directly to `main`.
All new features, bug fixes, and project additions must be done in a separate branch.

1. **Create an Issue:** Start by taking a task from our Kanban board.
2. **Branch Naming:** Create a new branch off `main` using the format `feature/<your-feature>` or `fix/<your-fix>`.
   ```bash
   git checkout main
   git pull origin main
   git checkout -b feature/add-project-2
   ```

## Development Workflow

1. **Write Code:** Make your changes. Keep them focused on the task.
2. **Commit Often:** Use clear, descriptive commit messages.
   ```bash
   git commit -m "feat: add gradient hover effect to project cards"
   ```
3. **Push to Remote:**
   ```bash
   git push origin feature/add-project-2
   ```

## Pull Requests (PRs)

1. Open a PR on GitHub comparing your feature branch to `main`.
2. **Description:** Clearly describe what your PR does and link it to the relevant Kanban board issue.
3. **Reviewers:** You **must** assign at least one other team member to review your code.
   - *Rupak, Radhika, Shahil, Anuj, Abhishek* - everyone is responsible for reviewing.

## Code Review Process

- **Reviewers:** Check for clean code, no console errors, and that it matches our UI/UX design system (glassmorphism, no Tailwind, pure CSS).
- **Approval:** A PR requires at least **1 approval** before it can be merged.
- **Merge:** Once approved, the PR author should "Squash and merge" or "Rebase and merge" to keep the main history clean.

## CI/CD (Simulated)

- Ensure `npm run dev` builds locally without any syntax errors before opening your PR.
- Do not check in `node_modules`.

Thank you for contributing to our digital excellence!
