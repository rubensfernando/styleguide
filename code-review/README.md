# Code Review

> menuqr code review best practices.

## TOC

1. [Pull requests](#pull-requests)
2. [Reviewing](#reviewing)
3. [Shipping](#shipping)
4. [Common sense](#common-sense)

## Pull requests

* [1.1](#1.1) <a name='1.1'></a> Always before opening a pull request make sure you run CSS and JavaScript linting.

> This will avoid micro reviews based on code syntax.

* [1.2](#1.2) <a name='1.2'></a> Everytime you open a pull request make sure to let everyone on the team know.

> Use our `NS - Front End` Skype chat room or even our `#front-end` channel on Slack.

* [1.3](#1.3) <a name='1.3'></a> Always before opening a pull request make sure the commit history is clean and easy to understand.

> Interactive rebase is our best friend and we should use it to enforce meaningful SCM history.

* [1.4](#1.4) <a name='1.4'></a> Name your pull request following the same pattern used in commits by our [SCM](https://github.com/menuqr/styleguide/tree/master/scm#change-type) section.

> This will make easier to understand what is this pull request about.

**[⬆ back to top](#toc)**

## Reviewing

* [2.1](#2.1) <a name='2.1'></a> When reviewing code, make sure you add coments to specific line numbers.

> [GitHub has a nice feature to comment on the diff of pull requests](https://help.github.com/articles/commenting-on-the-diff-of-a-pull-request).

* [2.2](#2.2) <a name='2.2'></a> When reviewing code, make sure you mention the author and other team members involved on the implementation you're reviewing.

> [GitHub's issue mentions are awesome](https://github.com/blog/957-introducing-issue-mentions).

* [2.3](#2.3) <a name='2.3'></a> After reviewing the code, if you think it's ready to ship, add a comment followed by one of these emojis: :sheep:, :rocket:, :ship: or :shipit:.

**[⬆ back to top](#toc)**

## Shipping

* [3.1](#3.1) <a name='3.1'></a> A branch can be merged only if it has one or more emojis, from different authors, indicating it's ready to ship.

> This way we ensure that the code is going to be reviewd by at least two team members before going to production.

* [3.2](#3.2) <a name='3.2'></a> After merging a branch, make sure you hit <kbd>Delete branch</kbd> button on GitHub's interface.

> It will help keeping things clean.

**[⬆ back to top](#toc)**

## Common sense

* [4.1](#4.1) <a name='4.1'></a> Use your common sense when reviewing code. Avoid pointless discussions, [bikeshedding](http://en.wikipedia.org/wiki/Parkinson%27s_law_of_triviality) and drama.

> This is probably the hardest one. Just try to be professional and kind.

**[⬆ back to top](#toc)**
