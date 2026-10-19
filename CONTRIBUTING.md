# Contributing

Thanks for taking the time to look at this project.

## Workflow

1. Open an issue first for anything bigger than a typo, so we agree on the approach.
2. Fork, create a branch from `main` (`feat/short-name` or `fix/short-name`).
3. Keep commits small and use [Conventional Commits](https://www.conventionalcommits.org/).
4. Run the checks locally before pushing:

   ```bash
   pip install pre-commit
   pre-commit install
   pre-commit run --all-files
   ```

5. Open a pull request using the template. CI must be green.

## Rules

- No secrets, `.env` files or real personal data. Test data is synthetic.
- Behaviour changes come with tests.
- Decisions that are expensive to reverse get an ADR in `docs/adr/`.
