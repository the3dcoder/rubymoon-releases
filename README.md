# Ruby Moon releases

Signed firmware images and content packs for Ruby Moon, a Moon-themed learning companion for young children on the Xteink X4 e-paper reader.

This repository holds release artifacts only. Each Ruby Moon device checks the signed `catalog.json` published from here on GitHub Pages, verifies every download against the release keys built into its firmware, and only installs an update after a grown-up confirms it on the device.

Nothing here runs on its own; a file that isn't signed with a Ruby Moon release key is ignored by the device.
