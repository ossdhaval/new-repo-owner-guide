# new-repo-owner-guide
Starting your own open source project?? This repo lists important aspects to keep in mind when starting a new repo and links to the relevant material.

Content on this repo tends to over simplify concepts to make them easy to understand. Links will be provided if you want to deep dive.

- [Day 1](#day-1): Checklist that will help cover basic needs of any repo
- [Level UP](#level-up): When you are not the only one contributing to the repository. You have contributors, community, team working together.

## Day 1

### README

Bare minimum README should contain:

- What does this repo contain? (code, samples, guides etc)
- How to use it? (installation instructions, links to binaries and how to download)
- Thank you note for your contributors

[Advanced README items]()

### Licensing

- What does a license do: It controls how others use your code. For example, Can they sell your code and earn money? 
- Understand the [free](https://www.gnu.org/philosophy/free-sw.en.html) Vs [Open source](https://opensource.org/definition-annotated) software
- Your GH repo can live without a license. It is not mandatory to have license, but in that case you don't have any claim on the contents of your repo. 
- GH let's you choose a license when you start a new repo. 
- Most widely used licenses:
  - no license or Unlicense
  - Apache (middle ground)
  - MIT (permissive)
  - GNU (restrictive)

For quick understanding, check this [video](https://www.youtube.com/watch?v=nFU8KoSgEmk&list=PLPR_9YriEawHVezQrZ1djlQwp16EdI5cl).

### Branch protections

  - Protect your `main` branch by enabling following restrictions on it.
    - `Require a pull request before merging`
    - `Require linear history`
    - `Require PR approval`

### Contribution guide

  - What coding standards you follow
  - Describe the PR flow. Does your repo needs PRs to be reviewed?

### Security policy

  -  What is someone is inspecting your code and finds a security flaw. How do they report it?

### Documentation

  -  Create repo based markdown documentation.

### Collaboration

- `GitHub discussions` is excellent collaboration tool that is available to you from day one. Many large open source projects use them as their main tool for community collaboration, for instance [Janssen Project](https://jans.io/discussions). Don't wait till you create Slack, Discord for your project. Just start with GitHub discussions with zero time investment. 

## Level Up

### Level Up your README 

#### Badges



#### Quick links

#### Mention security policy

### Automation

#### ReleasePlease

#### Sonarcloud

#### Security analysis (snyk)

#### auto labeling

#### Branch clean up

#### Mandate documentation declaration, test cases, 

#### Connect with messaging tools

### Dependabot

### SBOM and analysis reports

### Semantic Releases and Tags

### Contribution process

#### Triage

#### labeling strategy

### Code owners

### PR and Issue templates

### ossfuzz

### Static Documentation 

### Good practises certified

### Who is using your software (Repo analytics)


