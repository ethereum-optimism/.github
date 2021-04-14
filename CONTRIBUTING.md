# Contributing

🎈 Thanks for your help improving the project! We are so happy to have you!

🚨 Before making any non-trivial change, please first open an issue describing the change to solicit feedback and guidance. This will increase the likelihood of the PR getting merged.

In general, the smaller the diff the easier it will be for us to review quickly.

Please note that we have a [Code of Conduct](#code-of-conduct), please follow it in all your interactions with the project.

# Pull Request Process

## Steps for the PR author

We recommend using the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) format on commit messages.

Before opening a PR:

1. Ensure that tests pass and code is lint free. You can run `yarn test` and `yarn lint` locally to check.
1. Update the README.md if your changes invalidate or extend its current content.
1. Include tests for any new functionality.
1. Ensure each section of the [Pull Request Template](./PULL_REQUEST_TEMPLATE.md) is filled out. Delete any sections that are not relevant.

Unless your PR is ready for immediate review and merging, please mark it as 'draft' (or simply do not open a PR yet).

**Bonus:** Add comments to the diff under the "Files Changed" tab on the PR page to clarify any sections where you think we might have questions about the approach taken.

### Response time:
We aim to provide a meaningful response to all PRs and issues from external contributors within 2 business days.

## Steps for PR Reviewers

### For all PRs

Reviewers should submit their review with either `Approve` or `Request changes` options (not `Comment`).

If the reviewer selects `Request changes`, they should clearly indicate which changes they require in order to approve.

If the reviewer selects `Approves`, they should either:
1. immediately merge it, or
2. indicate what further review they deem necessary (and from whom).

We further distinguish between two classes of PR those which modify production code (ie. smart contracts, go-ethereum), and those which do not (ie. dev tooling, test scripts, comments).

### For PRs which modify production code

The reviewer's job is to check that the PR:

1. Conforms to the specification (WIP, soon to be published here), or has an issue describing the additional functionality which a code owner has approved.
2. Is appropriately tested.
3. Does not introduce security issues.

#### Merge Criteria

1. All CI checks MUST pass.
1. At least 2 code owners must approve.
1. In the case of very simple changes, a single code owner may choose to merge at their discretion.

### For PRs which modify non-production code

For PRs which do not modify production code (ie. test, dev tooling),

The reviewer's job is to check that the PR:

1. Is correct.
1. Is desirable.

#### Merge Criteria

1. All CI checks MUST pass.
1. At least one code owner must approve.

## Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, gender identity and expression, level of experience,
nationality, personal appearance, race, religion, or sexual identity and
orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or
advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic
  address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable
behavior and are expected to take appropriate and fair corrective action in
response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or
reject comments, commits, code, wiki edits, issues, and other contributions
that are not aligned to this Code of Conduct, or to ban temporarily or
permanently any contributor for other behaviors that they deem inappropriate,
threatening, offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces
when an individual is representing the project or its community. Examples of
representing a project or community include using an official project e-mail
address, posting via an official social media account, or acting as an appointed
representative at an online or offline event. Representation of a project may be
further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported by contacting the project team at contributing@optimism.io. All
complaints will be reviewed and investigated and will result in a response that
is deemed necessary and appropriate to the circumstances. The project team is
obligated to maintain confidentiality with regard to the reporter of an incident.
Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good
faith may face temporary or permanent repercussions as determined by other
members of the project's leadership.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4,
available at [http://contributor-covenant.org/version/1/4][version] and from the [Angular Seed Contributing Guide][angular-contrib].

[homepage]: http://contributor-covenant.org
[version]: http://contributor-covenant.org/version/1/4/
[angular-contrib]: https://github.com/mgechev/angular-seed/blob/master/.github/CONTRIBUTING.md
