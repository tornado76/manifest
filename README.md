PureStock
=====================

Getting Started
---------------

To build PureStock from source, you'll need to be familiar with
[Git and Repo](http://source.android.com/download/using-repo).


To initialize your local repository, use this command:

	repo init -u https://github.com/PureStock/manifest.git -b mm

Then to sync source, use this command:

	repo sync

After syncing is done, use these commands to build:

    1.) . build/envsetup.sh
    2.) lunch
    3.) pick device
    4.) make otapackage -j8
