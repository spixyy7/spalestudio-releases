# SpaleStudio - installers

Binaries only. The source lives in a private repository.

SpaleStudio is installed and kept up to date by SpaleHub.
**[Get SpaleHub](https://spale.pages.dev/download/spalehub)**, sign in, and
install SpaleStudio from its card. The installers on the
[Releases](https://github.com/spixyy7/spalestudio-releases/releases) page are
the ones SpaleHub downloads.

Each release carries:

- `SpaleStudio_<version>_x64-setup.exe`: the installer
- `latest.yml`: how SpaleHub learns that a release exists
- `latest.signed.json`: the same facts, signed. SpaleHub 0.5.1 and later
  install a release only when this signature checks out.

`update-policy.json` in this branch is what an installed copy fetches to find out what a
new version changes - before it downloads anything.
