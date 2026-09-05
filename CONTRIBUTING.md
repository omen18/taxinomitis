# Contributing to Machine Learning for Kids

For help with building the Machine Learning for Kids code, see `DEVELOPMENT.md`.

We welcome contributions, but request you follow these guidelines.

 - [Raising issues](#raising-issues)
 - [Worksheets](#worksheets)
 - [Feature requests](#feature-requests)
 - [Pull-Requests](#pull-requests)
 - [Coding Standards and Verification](#coding-standards-and-verification)
 - [Commit Message Conventions](#commit-message-conventions)

This project adheres to the [Contributor Covenant 1.4](http://contributor-covenant.org/version/1/4/).

By participating, you are expected to uphold this code. Please report unacceptable
behavior to the project lead at dale.lane@uk.ibm.com

## Raising issues

Please raise any bug reports on the [project's issue tracker](https://github.com/ibm/taxinomitis/issues). Be sure to
search the list to see if your issue has already been raised.

A good bug report is one that make it easy for us to understand what you were
trying to do and what went wrong.

## Worksheets

Project worksheets are managed in a separate repository. If you'd like to report a problem with one of the project worksheets, submit changes, or suggest or contribute a new project worksheet, please do that in the [taxinomitis-docs](https://github.com/IBM/taxinomitis-docs) repository.

## Feature requests

For feature requests, please raise them on the [project's issue tracker](https://github.com/ibm/taxinomitis/issues).

## Pull-Requests

If you want to raise a pull-request with a new feature, or a refactoring
of existing code, it may well get rejected if you haven't discussed it in an issue on the [project's issue tracker](https://github.com/ibm/taxinomitis/issues) first.

## Coding Standards and Verification

Please ensure your changes adhere to the repository standards:

1. **Linting**: Run the linter inside `mlforkids-api`:
   ```bash
   cd mlforkids-api
   npm run lint
   ```
2. **Compilation**: Ensure TypeScript compiles cleanly:
   ```bash
   npm run compile
   ```
3. **Tests**: Ensure tests pass:
   ```bash
   npm test
   ```

## Commit Message Conventions

We recommend following the [Conventional Commits](https://www.conventionalcommits.org/) specification:

- `feat`: Introduces a new feature
- `fix`: Patches a bug
- `docs`: Documentation changes
- `style`: Changes that do not affect the meaning of the code (white-space, formatting)
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to the build process or auxiliary tools/libraries
