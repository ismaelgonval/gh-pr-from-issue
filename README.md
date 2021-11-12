# GitHub CLI extension - **pr-from-issue**

## Summary

Extension for [GitHub CLI](https://github.com/cli/cli) that generates **pull requests from issues**.

## Requirements

- [**GitHub CLI**](https://github.com/cli/cli) configured in your system. (version `2.0.0` or higher)
- **Bash** (Supports **Windows**, **Mac** and **Linux**)

## Install

You can **install** this extension just running this command from your terminal:

```sh
gh extension install ismaelgonval/gh-pr-from-issue
```

## Usage

After installing this extension in the GitHub CLI client, you can get create a PR from an issue:

```sh
gh pr-from-issue [ISSUE_NUMBER]
```

This will open a new pull request in draft mode with the same title and labels.
It also adds a `Closes #[ISSUE_NUMBER]` directive in the description, this links
the PR with the issue and closes it when merged.
