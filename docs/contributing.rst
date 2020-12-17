############
Contributing
############

Help is always appreciated!

In particular, we need help in the following areas:

* Improving the documentation
* Fixing and responding to `DAppNode's GitHub issues
  <https://github.com/ethereum/solidity/issues>`_, especially those tagged as
  `up-for-grabs <https://github.com/ethereum/solidity/issues?q=is%3Aopen+is%3Aissue+label%3Aup-for-grabs>`_ which are
  meant as introductory issues for external contributors.


How to Contribute
=================

When bringing people on as contributors we prefer that they start with an issue tagged [good first issue](https://github.com/dappnode/DNP_BIND/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22). After a contributor has shown they're a good fit and have completed 1 or 2 issues labeled [good first issue](https://github.com/dappnode/DNP_BIND/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) with pull requests that have been accepted feel free of moving on to other issues. We're thrilled to see new contributors. 

If you want to better understand how does the development process works, please refer to our [wiki pages](https://github.com/dappnode/DAppNode/wiki)

In order to get the repositories setup before contributions refer to the [README.md](https://github.com/dappnode/DAppNode/blob/master/README.md) file.

1. *Find a suitable issue*

    If this is your first time look for an issue labeled [good first issue](https://github.com/dappnode/DNP_BIND/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) otherwise look for issues labeled [help wanted](https://github.com/dappnode/DNP_BIND/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) . If another issue jumps out at you please engage on the issue before starting it.

2. *Assign yourself the issue*

    Let us know you're working on it! We hate wasted labour so it's always helpful to know what our community contributors are working on.

3. *Fork and clone [DAppNode](://github.com/dappnode/DAppNode)*

    In general it's a good practice to fork into your own repository. We prefer if issues
    are addressed in a branch with the issue number in its name.
    i.e. `29_this_is_an_issue`

4. *Make contributions*

    Make all the changes needed to address the given issue.

5. *Add testing*

    In general we aim for full test coverage. For this reason most issues completed should include full testing. If you think there should be an exception for your issue please reach out. 

6. *Run previous tests*

    Make sure that the changes that you've made don't break anything! Ensure that running `npm test` and `npm eslint` doesn't throw any new and unexpected errors.

7. *Push all your work*

    At this point the issue should be addressed, new testing should be in place, and all old tests should be passing.

8. *Create a Pull Request*

    At this point you should either have a forked repository with your issue fixes and it is time to put in a PR. Make sure that your PR has something like `addresses #26` or `closes #26` The most important thing is that it has the relevant issue number referenced in the body of the PR.

9. *Make noise!*

    Get in our [Element](https://app.element.io/#/room/#DAppNode:matrix.org) and point to your new PR. Let us know you've tackled your first, third or 90th issue with us. We'll review it and everybody will get a warm feeling of accomplishment.

10. *rinse, repeat*

    Find another issue, get more involved, make noise in our Riot, or find issues we may have missed. You've completed your first step to becoming a contributor. **You're helping to Decentralize the FUTURE**!


If you still have any further questions about contribution feel free to reach out to `@eduadiez:matrix.org`,  `@yalormewn:matrix.org`, `@liondapp:matrix.org`, or just make noise in the `#DAppNode` channel on [Element](https://app.element.io/#/room/#DAppNode:matrix.org).


How to Report Issues
====================

To report an issue, please use the
`GitHub issues tracker <https://github.com/ethereum/solidity/issues>`_. When
reporting issues, please mention the following details:

* Which version of Solidity you are using
* What was the source code (if applicable)
* Which platform are you running on
* How to reproduce the issue
* What was the result of the issue
* What the expected behaviour is

Reducing the source code that caused the issue to a bare minimum is always
very helpful and sometimes even clarifies a misunderstanding.


Workflow for Pull Requests
==========================

In order to contribute, please fork off of the ``develop`` branch and make your
changes there. Your commit messages should detail *why* you made your change
in addition to *what* you did (unless it is a tiny change).

If you need to pull in any changes from ``develop`` after making your fork (for
example, to resolve potential merge conflicts), please avoid using ``git merge``
and instead, ``git rebase`` your branch.

Additionally, if you are writing a new feature, please ensure you write appropriate
Boost test cases and place them under ``test/``.

New features and bugfixes should be added to the ``Changelog.md`` file: please
follow the style of previous entries, when applicable.

Please note that this project is released with a `Contributor Code of Conduct
<https://raw.githubusercontent.com/dappnode/DAppNode/master/CODE_OF_CONDUCT.md>`_.
By participating in this project you agree to abide by its terms.

Thank you for your help!
