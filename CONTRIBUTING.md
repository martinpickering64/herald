# How to contribute

- participate in discussions on GitHub issues
- contribute by submitting pull requests with code changes.

## General feedback and discussions?

Start a discussion on the [issue tracker](https://github.com/martinpickering64/herald/issues).

## Bugs and feature requests?

❗ **IMPORTANT: If you want to report a security-related issue, 
please see the `Reporting security issues and bugs` section below.**

Before reporting a new issue, try to find an existing issue if one already exists. 
If it already exists, upvote (👍) it. 
Also, consider adding a comment with your unique scenarios and requirements related to that issue.  
Upvotes and clear details on the issue's impact help us prioritize the most important issues to be 
worked on sooner rather than later. 
If you can't find one, that's okay, we'd rather get a duplicate report than none.

If you can't find an existing issue, log a new issue.

## Reporting security issues and bugs

See [SECURITY.md](./SECURITY.md).

## How to submit a PR

We are always happy to see PRs for bug fixes as well as new features.
To help you here a few guidelines to follow when you prepare to contribute:

### Finding an issue to work on

To try and avoid  targetting a PR on areas that we have no plans for further expandsion a 
list of issues are highlighted, which may be a good place to contribute to. 
These issues are marked with the 'help wanted' label. Find this list of issues at 
[here](https://github.com/martinpickering64/herald/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22+-label%3AWorking).

If you would like to make a contribution to an area not documented here, first open an 
issue with a description of the change you would like to make and the problem it solves 
so it can be discussed before a pull request is submitted.

### Before writing code

To avoid solving an issue in a way, which either wouldn't fit into hearld because of how 
it's designed or it would change herald in a way that is not something we'd like to do, 
we encourage you to discuss the preferred design with us first. 
To do so, file a new `design proposal` issue, link to the issue you'd like to 
address, and provide detailed information about how you'd like to solve a specific problem. 
We triage issues periodically and it will not take long for us to engage with you on that proposal.
When you get an agreement from us that the design proposal you have is solid, then go ahead and prepare the PR.
To file a design proposal, look for the relevant issue in the `New issue` page or simply 
click [this link](https://github.com/martinpickering64/herald/issues/new?assignees=&labels=Design%20Proposal&template=design-proposal.md).

### Before submitting the pull request

Before submitting a pull request, make sure that it checks the following requirements:

* You find an existing issue with the "help-wanted" label or discuss with us to agree on adding a new issue with that label
* You post a high-level description of how it will be implemented and receive a positive acknowledgement from us before getting too committed to the approach or investing too much effort in implementing it.
* You add test coverage following existing patterns within the codebase
* Your code matches the existing syntax conventions within the codebase
* Your PR is small, focused, and avoids making unrelated changes

If your pull request contains any of the below, it's less likely to be merged.

* Changes that break backward compatibility
* Changes that are only wanted by one person/company. Changes need to benefit a large enough community
* Changes that add entirely new feature areas without prior agreement
* Changes that are mostly about refactoring existing code or code style
* Very large PRs that would take hours to review. For larger work areas, please discuss with us to find ways of breaking it down into smaller, incremental pieces that can go into separate PRs.

### During pull request review

A core contributor will review your pull request and provide feedback. 
To ensure that there is not a large backlog of inactive PRs, the pull request will be marked 
as stale after four weeks of no activity. After another week, it will be closed.

### Resources to help you get started

Here are some resources to help you get started on how to contribute code or new content.

* ["Help wanted" issues](https://github.com/martinpickering64/herald/labels/help%20wanted) - these issues are up for grabs. Comment on an issue if you want to create a fix.

### Submitting a pull request

If you don't know what a pull request is read this article: <https://help.github.com/articles/using-pull-requests>. 
Make sure the repository can build and all tests pass. 
Familiarize yourself with the project workflow and our coding conventions. 

### Tests

* Tests need to be provided for every bug/feature that is completed.
* Tests only need to be present for issues that need to be verified by QA (for example, not tasks)
* If there is a scenario that is far too hard to test there does not need to be a test for it (_"Too hard" is determined by the team as a whole_).

### Feedback

Your pull request will now go through extensive checks. 
Please be patient. 
Update your pull request according to feedback until it is approved by us. 
After that, we may adjust the branch you merge into based on the expected release schedule.

## Code of conduct

See [CODE-OF-CONDUCT.md](./CODE-OF-CONDUCT.md)