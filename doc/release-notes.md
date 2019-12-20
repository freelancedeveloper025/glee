*After branching off for a major version release of GleecBTC Core, use this
template to create the initial release notes draft.*

*The release notes draft is a temporary file that can be added to by anyone. See
[/doc/developer-notes.md#release-notes](/doc/developer-notes.md#release-notes)
for the process.*

*Create the draft, named* "*version* Release Notes Draft"
*(e.g. "0.20.0 Release Notes Draft"), as a collaborative wiki in:*

https://github.com/gleecbtc-core/gleecbtc-devwiki/wiki/

*Before the final release, move the notes back to this git repository.*

*version* Release Notes Draft
===============================

GleecBTC Core version *version* is now available from:

  <https://gleecbtccore.org/bin/gleecbtc-core-*version*/>

This release includes new features, various bug fixes and performance
improvements, as well as updated translations.

Please report bugs using the issue tracker at GitHub:

  <https://github.com/gleecbtc/gleecbtc/issues>

To receive security and update notifications, please subscribe to:

  <https://gleecbtccore.org/en/list/announcements/join/>

How to Upgrade
==============

If you are running an older version, shut it down. Wait until it has completely
shut down (which might take a few minutes for older versions), then run the
installer (on Windows) or just copy over `/Applications/GleecBTC-Qt` (on Mac)
or `gleecbtcd`/`gleecbtc-qt` (on Linux).

Upgrading directly from a version of GleecBTC Core that has reached its EOL is
possible, but it might take some time if the datadir needs to be migrated. Old
wallet versions of GleecBTC Core are generally supported.

Compatibility
==============

GleecBTC Core is supported and extensively tested on operating systems using
the Linux kernel, macOS 10.10+, and Windows 7 and newer. It is not recommended
to use GleecBTC Core on unsupported systems.

GleecBTC Core should also work on most other Unix-like systems but is not
as frequently tested on them.

From GleecBTC Core 0.17.0 onwards, macOS versions earlier than 10.10 are no
longer supported, as GleecBTC Core is now built using Qt 5.9.x which requires
macOS 10.10+. Additionally, GleecBTC Core does not yet change appearance when
macOS "dark mode" is activated.

In addition to previously supported CPU platforms, this release's pre-compiled
distribution provides binaries for the RISC-V platform.

Notable changes
===============

Credits
=======

Thanks to everyone who directly contributed to this release:


As well as to everyone that helped with translations on
[Transifex](https://www.transifex.com/gleecbtc/gleecbtc/).
