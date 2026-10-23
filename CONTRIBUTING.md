# Contributing to Xfina projects

Thank you for your interest! This is the default guide for every repository in
[xfina-dev](https://github.com/xfina-dev). A repository with its own
`CONTRIBUTING.md` (Xfina, Xfingine, Xfina Data) has the details for building and
testing it; read that one first.

## Never publish real financial data

Every repository here is public. Nothing taken from a real statement belongs in
code, comments, tests, commit messages, issues, pull requests or screenshots:

- names, account, card or customer numbers (even masked), PAN
- real balances, amounts or credit limits
- email addresses, UPI handles, phone numbers, postal addresses
- transaction descriptions copied from a statement

Invent values that keep the shape and drop the content, and describe a bug
structurally ("a name with an honorific lost it") rather than quoting the
statement that showed it.

## Issues

Use the forms on the repository's **Issues** tab: report a problem, request a
feature, or share how you used a tool. Security problems go through the
private route in [SECURITY.md](SECURITY.md) instead.

## Pull requests

1. Fork the repository and branch from `main`.
2. Keep a pull request to one change, with tests where the project has them.
3. Make sure the repository's checks pass locally.
4. Describe what changed and why. Add an entry to `CHANGELOG.md` if the
   repository keeps one.

By contributing, you agree that your work is licensed under the
repository's licence (Apache-2.0).
