<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://theme.tekcloud.com/prod/github/tek-logo-round-dark-mode.png" width="100px">
  <source media="(prefers-color-scheme: light)" srcset="https://theme.tekcloud.com/prod/github/tek-logo-round-light-mode.png" width="100px">
  <img alt="Tek Logo" src="https://theme.tekcloud.com/prod/github/tek-logo-round-light-mode.png" width="100px">
</picture>

# Issue Template Guide
![repo linter workflow](https://github.com/tektronix/best-practice-resources/actions/workflows/tek-repo-lint.yml/badge.svg)
> [Link to Github docs](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository)

A brief explanation of issue templates and how to use them.

## Getting Started

If you want to make your own organization wide template, just create a yaml file in this directory that follows [Github's formatting guidelines](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms). You can also use an [existing issue template](https://github.com/tektronix/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.yml) as a starting point.

## Usage

Issue templates made here will appear as options when creating an issue on any *public* repository.

## Repository Checklist

The `new_repo_checklist.yml` template is meant to be used as a way to create checklists on newly created repositories when setting them up. Any new workflows/requirements should be added to that checklist.
