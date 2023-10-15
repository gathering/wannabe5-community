# How to Contribute

❤️  Thanks for looking at this, we appreciate your contributions!

Before you start working on a significant code change,
it’s a good idea to make sure that your approach is likely to be accepted.
The best way to do this is to create a issue of type “Feature Request”
in GitHub where you describe your plans.

Wannabe development aligns its direction with The Gathering/KANDU and will
prioritizing features that directly benefit and enhances The Gathering.

As this project is in a pretty early phase, the rules are fast and loose. All
efforts to contribute are **much appreciated**, and these guidelines are just in
place to try to make it as fruitful and constructive as possible.

We are on slack (and sometimes on discord) so feel free to reach out!

## Repositories
We maintain two primary repositories: one dedicated to [backend code](https://github.com/gathering/wannabe5-backend) and another to [frontend code](https://github.com/gathering/wannabe5-frontend).

## Clone and Provision Environment

1. Make sure you have a GitHub account
2. Fork the [Wannabe5-backend](https://github.com/gathering/wannabe5-backend) and [Wannabe5-frontend](https://github.com/gathering/wannabe5-frontend) repository to your GitHub user or organization.
3. Clone your ${YOUR_GITHUB_USERNAME_OR_ORG}/wannabe5-[frontend|backend] fork and setup the base repository as upstream remote:

Backend:
```bash
git clone https://github.com/${YOUR_GITHUB_USERNAME_OR_ORG}/wannabe5-backend.git
cd wannabe5-backend
git remote add upstream https://github.com/gathering/wannabe5-backend.git
```

Frontend:
```bash
git clone https://github.com/${YOUR_GITHUB_USERNAME_OR_ORG}/wannabe5-frontend.git
cd wannabe5-frontend
git remote add upstream https://github.com/gathering/wannabe5-frontend.git
```

5. Set up your [Development Setup](DEVELOPMENT.md).
6. Check the GitHub issues for good tasks to get started.

## 📦 Create PRs early

We recommend creating a PR as soon as you have "any" partially working code in
your branch. This makes it easier for others to notice your work and
provide them with additional context on what it is and how it (potentially)
relates to what they are working on.