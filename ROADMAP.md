# H2 2023

Given our mode of operation and the fact that we are highly affected by current needs of teams, our H2 roadmap serves mainly us a guideline of where our interests lie and where we'd like to focus our efforts. We view our adaptability as one of our main strengths but it also means we have to be flexible when it comes to our planning. If you already know of things you'd like our involvement for in H2 2023, please let us know - we're happy to adjust accordingly. We're here for you ❤️

## Drive GitHub Observability Usage Internally

Whenever applicable, every project we start in H2 2023 should have a Grafana Dashboard associated with it that tracks relevant metrics for the project. Each project issue should have a link to the dashboard, description of the metrics we care about and the expected outcomes.

Additionally, we'd like to use GitHub Observability to identify more workflows that would benefit from PL Self-Hosted Runners.

## Release Gateway Conformance v1

In H2 we want to conclude IPDX's active development of Gateway Conformance. Ideally, we'd like to attract Gateway implementation maintainers to become active contributors to the project. We're going to continue to serve as maintainers, review PRs and provide guidance.

To be able to call Gateway Conformance ready for this, we should:
- achieve test coverage parity with Kubo sharness tests
- improve DX/UX around test expectations and names
- start running Gateway Conformance against a gateway external to PL

In terms of promotion of Gateway Conformance, we'd like to:
- give a talk about Gateway Conformance during IPFS Camp
- continue support of using Gateway Conformance in project Rhea

As stretch goals for the Gateway Conformance initiative, we identified:
- closer integration with specs repository/IPIP process
- creation of dashboard encompassing all gateway implementations

## Increase PL Self-Hosted Runners Relevance

With the recent cost-reduction effort in the PL self-hosted runners space the project is well positioned to serve the needs of PL developers already. As of now there are 2 areas that we'd like to look more closely into:
- windows runners (we already had them set up at the beginning so it's just a matter of resurrecting the configuration)
- decreasing boot time (currently the runners take up to 2 minutes to boot up)

## Expand IPDX Comms

We want to continue living close to our developers. That's why we're going to continue releasing **What's new in GitHub?** issues on a monthly basis. What's more, we'd like to start a new regular newsletter about productivity tips. Finally, we'd like to start tracking [developer happiness](https://github.blog/2023-06-08-developer-experience-what-is-it-and-why-should-you-care/) among IP Stewards. To begin with, we're going to prepare surveys for IP Stewards developers that are going to be issued on a regular basis.

When it comes to external comms, we'd like to actively participate in IPFS Camp and GitHub Universe conferences.

## Release Unified CI 2.0

In August, we're going to release new version of Unified CI with Go 1.21 support. With that release, we'd like to transition to [Unified CI 2.0](https://github.com/protocol/.github/issues/514) which should encompass all the learning that we gathered by running Unified CI in its' current form for years. This includes but is not limited to:
- versioning Unified CI
- embracing reusable workflows
- centralising auomerge functionality
- allowing configurability through dot files
- simplifying enrollment with invite to deploy strategy

All of the above will make Unified CI more robust, easier to manage and it will increase it chances to last for another couple of years. Moreover, it will open up doors for even more automation across hundreds of repositories, like using dependabot for Unified CI updates for example.

## Immerse Into the Day to Day of IP JS Developer

As one of the most underresourced projects within IP Stewards group, we think it is the best target for our research. We want to embed with the team for a while to uncover areas of potential DX improvements. By the end of this excercise we want to have a concrete, prioritised list of improvements that would make life of a IP JS developer easier.

## Improve the Day to Day of Kubo/Boxo Developer

We've been focusing on Kubo/Boxo developers in H1 2023. In H2, we'd like to work on the work items that we identified throughout the process. The main projects we envision are:
- create a general solution for identifyin flaky tests within Go ecosystem
- automate CHANGELOG update reminders
- fix the shortcomings of testing and coverage at the cross section of Kubo and Boxo
- deprecate sharness tests
- execute kuboreleaser in GitHub Actions

## Explore DX of Building on IPFS Stack

Through our work on Gateway Conformance we discovered that building on IPFS stack is not easy, even for people close to the ecosystem. We'd like to start a standalone project that would help us explore this further. The very rough game plan is:
1. Start a simple project that cuts through all the layers of IPFS stack (working idea - decentralised DropBox).
2. Consume the publicly available documentation to implement the project.
3. Document usability sharp edges and documentation shortcomings.
4. Contribute usability fixes to the IPFS stack.

Our thinking is that this exercise could attract more active contributors to the IPFS stack thus reducing strain on IP Stewards.

This is a project that sparks joy for Laurent 💖

## Increase GitHub Security

We want to continue building up our partnership with RSS by continuous collaboration on Security Guides for Software Engineers. Moreover, we'd like to explore the possibility of:
- deploying dependabot for updating GitHub Actions to all PL repositories
- enabling Code Scanning with default settings in all PL repositories

## R&D

We want to continue bringing innovation and improvement to our development stack. To be able to do that, we need to be up-to-date with the latest tech in the field. We'll definitely continue exploring AI tooling throughout the rest of the year and evaluate its' relevance for our projects. Moreover, we'd like to gain practical experience with GitHub merge queues by integrating them in GitHub Management workflows.
