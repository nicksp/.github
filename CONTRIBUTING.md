# Contributing

I am really excited that you are interested in contributing. Please make sure to read through the following guide.

## Issues

I use GitHub issues to track bugs. Please ensure your description is clear and has sufficient instructions to be able to reproduce the issue.

## Pull Requests

I actively welcome your pull requests for bug fixes.

> [!NOTE]
> If you don't know how to send a pull request, I recommend reading [this guide](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) first.

1. Fork the repo and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. Update the documentation if required.
4. Ensure the test suite passes.
5. Make sure your code lints.

### Commit convention

I use [Conventional Commits](https://www.conventionalcommits.org/) for commit messages, which allows the changelog to be auto-generated based on the commits. Please read through the guide if you aren't familiar with it already.

Only `fix:` and `feat:` will be presented in the changelog.

For typo or document changes, use `chore:` or `docs:` respectively.

### Guidelines

When sending a pull request, make sure your PR's title also follows the [commit convention](#commit-convention).

If your PR fixes or resolves an existing issue, please add the following line in your PR description (replace `123` with a real issue number):

```markdown
fix #123
```

This will let GitHub know the issues are linked, and automatically close them once the PR gets merged. Learn more in [the guide](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword).

Multiple commits in a single PR are fine. I'll use `Squash and Merge` when merging, so there's no need to rebase or force push.

## License

By contributing to this project, you agree that your contributions will be licensed under its LICENSE file in the root directory.
