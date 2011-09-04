# OpenDingux kernel merged with Qi Hardware

The OpenDingux kernel started as a fork of the Qi Hardware kernel for the Ben NanoNote, which uses very similar Ingenic SoC as its core. The fork never diverged very far from its origin and we exchanged many patches in both directions. Therefore we decided it is easier to do development in a single place. We selected the [http://projects.qi-hardware.com/index.php/p/qi-kernel/](git repository at Qi Hardware) as that single place.

The interesting branches are "jz-*version*", where *version* is the Linux kernel version that the branch is based on. The Dingoo specific instructions are in the file README-A320 at the top of the source tree.
