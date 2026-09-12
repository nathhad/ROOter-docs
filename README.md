# ROOter-docs
Documentation for the ROOter GoldenOrb project.

The ROOter GoldenOrb project has traditionally been hosted on individual websites by lead developer Dairyman and several volunteers. The main components are:

- Dairyman's [OfModemsAndMen](https://ofmodemsandmen.com/) page (currently down)
- nathhad's [ATurnOfTheNut autobuilds](https://www.aturnofthenut.com/rooter-autobuilds/) site (which creates and hosts the latest router images)
- carp4's [Autobuild Archive](https://mega.nz/folder/2roRmSgJ#aX--LN6uqA3npPHPfgTiAA), which hosts the history of available autobuilds for each router

The great drawback to this system is that it results in a very high [bus factor](https://en.wikipedia.org/wiki/Bus_factor). Currently the majority of the components of this ecosystem live on three privately run sites, which could disappear at any moment should something bad happen (and as of 2026-09, Dairyman is currently working with the host of the main site to resolve repeated hacking issues). While some components such as the autobuild hardware and the archive necessarily live in a vulnerable paid location, the source code and documentation can be hosted free on any git platform that seems reasonably likely to survive long-term, and can then be forked and maintained should something happen to the team currently running the project.

In addition, the thing most at threat is the working knowledge of the system. Because ROOter, like any OpenWRT variant, is meant for embedded hardware with very limited storage, there is almost no in-line commentary for documentation. It is not an easy ecosystem for a new collaborator to jump into, and it's not always clear where ROOter deviates from base OpenWRT. This repository is meant to include a Wiki that will eventually become working documentation to maintain the system.

At present this project is extremely rudimentary. With time, we hope it will grow and become a useful resource.
