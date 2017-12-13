# Contribution Guide

We welcome and encourage community contributions to Roomify for Accommodations. (RfA)

Please familiarize yourself with the Contribution Guidelines before contributing.

There are many ways to help RfA besides contributing code:

 - Fix bugs or file issues

## Contributing Code

Unless you are fixing a known bug, we **strongly** recommend discussing it with the core team via a GitHub issue or [email](mailto:hello@roomify.us) before getting started to ensure your work is consistent with RfA's roadmap and architecture.

All contributions are made via pull request. Note that **all patches from all contributors get reviewed**. After a pull request is made other contributors will offer feedback, and if the patch passes review a maintainer will accept it with a comment. When pull requests fail testing, authors are expected to update their pull requests to address the failures until the tests pass and the pull request merges successfully.

At least one review from a maintainer is required for all patches (even patches from maintainers).

Reviewers should leave a "LGTM" comment once they are satisfied with the patch. If the patch was submitted by a maintainer with write access, the pull request should be merged by the submitter after review.

## Code Style

Please follow these guidelines when formatting source code:

* All code should adhere to the [Drupal Coding standards](https://www.drupal.org/docs/develop/standards)

## Developer’s Certificate of Origin

All contributions must include acceptance of the DCO:

```text
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.
660 York Street, Suite 102,
San Francisco, CA 94110 USA

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.


Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```

To accept the DCO, simply add this line to each commit message with your name and email address (`git commit -s` will do this for you):

```text
Signed-off-by: Jane Example <jane@example.com>
```

For legal reasons, no anonymous or pseudonymous contributions are accepted ([contact us](mailto:hello@roomify.us) if this is an issue).

## Pull request procedure

To make a pull request, you will need a GitHub account; if you are unclear on this process, see GitHub's documentation on [forking](https://help.github.com/articles/fork-a-repo) and [pull requests](https://help.github.com/articles/using-pull-requests). Pull requests should be targeted at the `master` branch. Before creating a pull request, go through this checklist:

1. Create a feature branch off of `master` so that changes do not get mixed up.
1. [Rebase](http://git-scm.com/book/en/Git-Branching-Rebasing) your local changes against the `master` branch.
1. Ensure that all tests pass - See [Travis](http://travis-ci.org/Roomify/roomify)
1. Accept the Developer's Certificate of Origin on all commits (see above).

Pull requests will be treated as "review requests," and maintainers will give feedback on the style and substance of the patch.

Normally, all pull requests must include tests that test your change. Occasionally, a change will be very difficult to test for. In those cases, please include a note in your commit message explaining why.

## Communication

For bug reports, feature proposals, and discussion, please create an issue on this project.
