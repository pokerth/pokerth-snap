# pokerth-snap

Installation:

You need snapd and snapcraft installed. Best is to use the snap variant of snapcraft instead of a Distro specific version:

* if not yet installed install snapd:

  https://snapcraft.io/docs/installing-snapd

* install snapcraft:

  `sudo snap install snapcraft --classic`
  
  https://snapcraft.io/docs/snapcraft-overview

* clone the repository and enter the folder

* run snapcraft:

  `snapcraft`

* agree to install multipass if not installed

  It will then also download a core18 VM in which the whole build process takes place. The build process should result in a snap file.

* Use `snap install --devmode [SnapFile].snap` to install the snap.

* Launch the client with:

  `pokerth`

