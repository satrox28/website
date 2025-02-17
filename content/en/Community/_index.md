---
title: Community
linkTitle: "Community"
type: docs
---

## GitHub

The [Kyverno source code](https://github.com/kyverno/kyverno/) and project artifacts are managed on GitHub in the [Kyverno](https://github.com/kyverno) organization.

## Slack Channel

Join the Kubernetes Slack workspace at [https://slack.k8s.io/](https://slack.k8s.io/) and then search for the [#kyverno](https://slack.k8s.io/#kyverno) channel.

If you already have access to the Kubernetes Slack workspace simply select "sign in" at [https://slack.k8s.io/#kyverno](https://slack.k8s.io/#kyverno).

## Community Meetings

To attend our community meetings, join the [Kyverno group](https://groups.google.com/g/kyverno). You will then be sent a meeting invite and will have access to the agenda and meeting notes. Any member may suggest topics for discussion.

### Community Meeting

This is a monthly meeting for the broader community in which upcoming features and road map discussions take place:

- Monthly on the second Thursday at 9:00 AM PST
- [Agenda and meeting notes](https://docs.google.com/document/d/10Hu1qTip1KShi8Lf_v9C5UVQtp7vz_WL3WVxltTvdAc/edit#)

### Contributors Meeting

This is a weekly forum for Kyverno contributors and maintainers to discuss project delivery and implementation topics such as feature designs, fixes, code, and documentation:

- Weekly every Wednesday at 9:00 AM PST
- [Agenda and meeting notes](https://docs.google.com/document/d/1kFd4fpAoHS56mRHr73AZp9wknk1Ehy_hTB_KA7gJuy0/)

## Get in touch

If you are unable to attend a community meeting, feel free to reach out anytime on the [Kyverno Slack channel in the Kubernetes workspace](https://slack.k8s.io/#kyverno), or the Kyverno [mailing list](https://groups.google.com/g/kyverno).

We love hearing from our community!

## Contributing

Thanks for your interest in contributing! We welcome all types of contributions and encourage you to read our [contribution guidelines](https://github.com/kyverno/kyverno/blob/main/CONTRIBUTING.md) for next steps.

The project contributors use a combination of [GitHub discussions](https://github.com/kyverno/kyverno/discussions), [GitHub Wiki](https://github.com/kyverno/kyverno/wiki) for design documents, and the [#kyverno-dev Slack channel](https://kubernetes.slack.com/archives/C032MM2CH7X) for notes on the development environment, project guidelines, and best practices.

## Join Kyverno Adopters

Kyverno is a CNCF incubating project and is growing fast. To qualify for the [graduation level](https://github.com/cncf/toc/blob/main/process/graduation_criteria.md#graduation-stage) the CNCF requires production usage by multiple end users.

The goal of this adopters program is to gather real-world usage examples and help Kyverno graduate. We hope to achieve this by learning from the existing and new adopters of Kyverno who are willing to share their stories with CNCF.

To participate, fill out the [Kyverno adopters form](https://docs.google.com/forms/d/e/1FAIpQLSe1IBSxDFn_iAAq9vd0nQdjKbapvgGyM8j2IX_z4xSCu-OSNg/viewform?usp=sf_link).

## Project Governance

This document highlights the roles and responsibilities for the Kyverno community members. It also outlines the requirements for anyone who is looking to take on leadership roles in the Kyverno project.

**Note:** Please make sure to read the CNCF [Code of Conduct](https://github.com/cncf/foundation/blob/master/code-of-conduct.md).

### Project Roles

**Contributors**:

These are individuals who have made multiple contributions to the project; by authoring PRs, commenting on issues and pull requests, or participating in community discussions on Slack or the mailing list.

**Code Owner**:

These are individuals who remain as active contributors who have good experience and knowledge of the project. They are expected to proactively manage issues and pull requests without write access.

**Maintainer**:

Maintainers are individuals who go beyond the status of code owner who have shown good technical judgement in feature design/development in the past. Maintainers have overall knowledge of the project and features in the project. They can read, clone, and push to the repository. They can also manage issues, pull requests, and some repository settings.

**Admin**:

These are persons who have full access to the project, including sensitive and destructive actions like managing security or deleting a repository. Admins can read, clone, and push to this repository. They can also manage issues, pull requests, and repository settings, including adding collaborators.

| Role         | Responsibilities                                                      | Requirements                                                                                  | Defined by                                                                                                                   |
| ------------ | --------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Contributors | None                                                                  | Made at least five (5) contributions to the project.                                          | CONTRIBUTORS.md                                   |
| Code Owner   | Active contributions, assist maintainers, review and approve contributions. | Made at least ten (10) significant contributions and appointed by 2 maintainers. Highly experienced and active reviewer + contributor to a subproject.                         | Maintainers, [CODEOWNERS](https://help.github.com/en/articles/about-code-owners), GitHub organization member.                                           |
| Maintainer   | Code Owner, monitor project growth, set direction and priorities for a subproject. | Highly experienced and active contributor + Kyverno Certification + Voted in by Kyverno maintainers. | Voted in by the Kyverno maintainers, listing in `MAINTAINERS.md`, GitHub organization member, and repository owner. |

#### Contributors

Contributors are community members who have made some contribution in the past to one or more subprojects. They can have issues and PRs assigned to them.

**Checklist before becoming a Contributor**

- Have at least five (5) PRs successfully merged for any repositories under the Kyverno organization
- Member of the kyverno channel on Kubernetes and/or CNCF Slack
- Attended one (1) Contributors Meeting as documented
- Registered for the Kyverno [mailing list](https://groups.google.com/g/kyverno)

**Privileges of a Contributor**

- Listed in the `CONTRIBUTORS.md` file in at least one (1) organization repository
- Kyverno contributor badge issued

#### Code Owners

Code Owners are a special type of contributor and have _significantly_ contributed and maintain an _active_ status within the organization. They can have issues and PRs assigned to them and are responsible for providing PR reviews. Unlike Contributors, Code Owners have responsibilities and must maintain an active status defined below to remain a Code Owner.

**Checklist before becoming a Code Owner**

- Have at least ten (10) significant PRs successfully merged for any combination of repositories under the Kyverno organization
- Member of the kyverno channel on Kubernetes and/or CNCF Slack
- Attended five (5) Contributors Meetings as documented
- Registered for the Kyverno [mailing list](https://groups.google.com/g/kyverno)
- Create a pull request to add self to `CODEOWNERS` file in at least one (1) repository
- Attained a minimum of two (2) positive votes from maintainers
- Respond to reviews from maintainers on pull requests

**Responsibilities of a Code Owner**

- Maintain an active status in a three (3) month period to include any of the following:
  - One (1) PR filed
  - Any request for PR review responded to
  - One (1) issue or PR responded to
  - One (1) Slack thread responded to
  - Two (2) attendance at weekly Contributors Meetings

**Privileges of a Code Owner**

- Listed as an organization member
- Listed in `CODEOWNERS` in at least one (1) repository
- Kyverno contributor badge issued
- Have issues assigned to them
- Have PRs assigned to them

**On-boarding Criteria**

- Voted in by a majority of current maintainers, raised in a PR by the proposed member to add themselves to `CODEOWNERS`, during a voting period lasting seven (7) days

**Off-boarding Criteria**

- Voted out by a majority of current maintainers via a GitHub issue during a voting period lasting seven (7) days. A vote may be called by any maintainer after the point at which the responsibilities have not been met. A positive vote will result in removal from `CODEOWNERS` and from organization membership.

<!-- #### Approvers

Approvers are contributors who provide active review and feedback on the issues and PRs. While code review is focused on code quality and correctness, approval is focused on holistic acceptance of a contribution including backwards and forwards compatibility, adhering to API and flag conventions, subtle performance and correctness issues, and interactions with other parts of the system. Approvers are encouraged to be active participants in project meetings, chat rooms, and other discussion forums.

**Checklist before becoming an Approver**

- Consistently monitors project activities such as issues created and new PRs
- Has been active on the project for over two months
- Successfully reviewed project codebase for at least one month
- Has an in-depth understanding of the project's codebase
- Sponsored by at least two maintainers

**Responsibilities & Privileges**

- Understands the project goals and workflows defined by maintainers
- Creates new issues according to the project requirements
- Assigns issues to contributors
- Responds to new PRs and issues by asking clarifying questions
- Organizes the backlog by applying labels, milestones, assignees, and projects
- Is readily available to review and approve PRs by making meaningful suggestions
- Applies code of conduct to edit and delete any inappropriate comments on commits, pull requests, and issues -->

#### Maintainers

[Maintainers](https://docs.github.com/en/organizations/managing-access-to-your-organizations-repositories/repository-roles-for-an-organization#repository-access-for-each-permission-level) are the technical authority for a subproject and are considered leaders for the organization as a whole. They must have demonstrated both good judgement and responsibility towards the health of the subproject. Maintainers must set technical direction and make or approve design decisions for their subproject, either directly or through delegation of these responsibilities. Unlike contributors and code owners, maintainers have the highest degree of responsibility and ownership for the project. Maintainer status may be subject to a vote and, if the minimum level of activity is not maintained, may be moved to an _emeritus_ status.

**Checklist before becoming a Maintainer:**

- Proficient in GitHub, YAML, Markdown, and Git
- Exhibits strong attention to detail when reviewing commits and provides generous guidance and feedback
- Helps others achieve their goals with open-source and community contributions
- Understands the workflow of the Issues and Pull Requests
- Makes consistent contributions to the Kyverno project
- Consistently initiates and participates in [Kyverno discussions](https://slack.k8s.io/#kyverno)
- Has knowledge and interest that aligns with the overall project goals, specifications, and design principles of the Kyverno project
- Makes contributions that are considered notable
- Demonstrates ability to help troubleshoot and resolve user issues
- Has achieved the [Kyverno Certification](https://learn.nirmata.com/explore), or demonstrated an equivalent mastery of Kyverno
- Meets or exceeds all the requirements of a Code Owner
- Maintains an active status as a Code Owner for a period of six (6) months

**Responsibilities of a Maintainer**

The following responsibilities apply to the subproject for which one would be an owner and maintainer.

- All the responsibilities of a Code Owner
- Tracks and ensures adequate health of the modules and subprojects they are in charge of
- Ensures adequate test coverage to confidently release new features and fixes
- Ensures that tests are passing reliably (i.e. not flaky) and are fixed when they fail
- Mentors and guides code owners, reviewers, and contributors
- Actively participates in the processes for discussion and decision making in the project
- Merges Pull Requests and helps prepare releases
- Makes and approves technical design decisions for the subproject
- Helps define milestones and releases
- Decides on when PRs are merged to control the release scope
- Works with other maintainers to maintain the project's overall health and success holistically

**Privileges of a Maintainer**

- Privileges of a Code Owner
- Receives a Kyverno Maintainer Badge
- Listed in `MAINTAINERS.md`

**On-boarding Criteria**

- Voted in by a majority of current maintainers, raised in a PR by the proposed member to add themselves to `MAINTAINERS.md`, during a voting period lasting seven (7) days

**Off-boarding Criteria**

- Voted out by a majority of current maintainers via a GitHub issue during a voting period lasting seven (7) days. A vote may be called by any maintainer after the point at which the responsibilities have not been met. A positive vote will result in movement to an _emeritus_ status within `MAINTAINERS.md` and removal from organization membership.

#### Mapping Project Roles to GitHub Roles

The roles used in this document are custom roles mapped according to the [GitHub roles and responsibilities](https://docs.github.com/en/organizations/managing-access-to-your-organizations-repositories/repository-roles-for-an-organization).

| Project Role   | GitHub Role    |
| -------------- | -------------- |
| Contributor    | Triage         |
| Code Owner     | Write          |
| Maintainer     | Maintain       |
| Administrator  | Admin          |

### Off-boarding Guidance

If any of the above roles hasn't contributed in any phases (including, but not limited to: code changes, doc updates, issue discussions) in 3 months, the administrator needs to inform the member and remove one's roles and GitHub permissions.