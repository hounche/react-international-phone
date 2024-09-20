# How to contribute

You need to fork a repository and implement changes inside the forked repo. After that, you can create a PR to the `development` branch.
More info about forking and branching you can find on [GitHub Docs](https://docs.github.com/en/get-started/quickstart/contributing-to-projects).

## Before opening a PR

- Make sure that new features are covered by tests.
- Run tests by `pnpm test` command and make sure that they are passing.
- Lint and format code by running `pnpm lint` and `pnpm format`.
- Build package by `pnpm build` and make sure that build is working.
- Test documentation by `pnpm docs:test`.

## Commit titles

Commit titles should correspond to [convention](https://www.conventionalcommits.org/en/v1.0.0/).
This is needed for the commit analyzer and automatic release functionality 🙏

💡 You can use `pnpm cm` command to commit your changes

Examples:

- fix(CountrySelector): add type="button" to selector button
- docs(validation): add phone-validation page to docs
- test(PhoneInput): fix undo/redo tests flaky crash

### Thank you for considering contributing :)
