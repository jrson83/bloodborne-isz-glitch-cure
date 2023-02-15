# Contributing

When contributing to this repository, please make sure to read through these guidelines. Note that no matter how you contribute, your participation is governed by our
[Code of Conduct](CODE_OF_CONDUCT.md).

## Table of Contents

- [Submit a bug report or feature request](#submit-a-bug-report-or-feature-request)

## Submit a bug report or feature request

Please use the GitHub [issue tracker](https://github.com/jrson83/bloodborne-isz-glitch-cure/issues) to submit bug reports and feature
requests.

### Submission checklist

1. Check the [open issues](./?q=is%3Aissue) to ensure you are reporting a new issue

## Submit a Pull Request

Once you're done making the changes, you can now open a pull request (PR). Go to the forked repository in GitHub and select your feature branch. Click the 'Pull Request' button and fill out the form.

While naming your Pull Request, make sure to read the following [commit message guidelines](#commit-message-format).

## Commit message format

We use [Interactive Commitizen CLI](https://cz-git.qbb.sh/) (czg) to generate standardized commit messages following the [Conventional Commits](https://www.conventionalcommits.org) specification.

### Commit message header

```
<type>(<scope>): <short summary>
  │       │             │
  │       │             └─⫸ Summary in present tense. Not capitalized. No period at the end.
  │       │
  │       └─⫸ Commit Scope: workspace|docs
  │
  └─⫸ Commit Type: feat|fix|refactor|chore|revert
```

The `<type>` and `<summary>` fields are mandatory, the `(<scope>)` field is optional.

<details>
  <summary>Click here to see a more detailed description on the commit message format.</summary>

#### Type

Must be one of the following:

- **feat:** A new feature
- **fix:** A bug fix
- **refactor:** A code change that neither fixes a bug nor adds a feature
- **chore:** Other changes that don't modify src or test files
- **revert:** Reverts a previous commit

#### Scope

The scope should be the name of the npm package affected (as perceived by the person reading the changelog generated from commit messages).

The following is the list of supported scopes:

- `workspace`
- `docs`

#### Summary

Use the summary field to provide a succinct description of the change:

- use the imperative, present tense: `change` not `changed` nor `changes`
- don't capitalize first letter
- no dot (.) at the end

#### Body

Just as in the **summary**, use the imperative, present tense: “change” not “changed” nor “changes”. The body should include the motivation for the change and contrast this with previous behavior.

#### Footer

The footer should contain any information about **Breaking Changes** and is also the place to reference GitHub issues that this commit **Closes**.

**Breaking Changes** should start with the word `BREAKING CHANGE:` with a space or two newlines. The rest of the commit message is then used for this.

> A detailed explanation of Conventional Commits messages can be found at [Conventional Commits examples](https://www.conventionalcommits.org/en/v1.0.0/#examples).

</details>
