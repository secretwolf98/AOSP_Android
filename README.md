# AOSP_Android

AOSP Nougat
===========

Getting Started
---------------

To get started with Android for Nook HD/HD+, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

    repo init -u git://github.com/secretwolf98/AOSP_Android.git -b aosp-7.1

Then to sync up:

    repo sync

Choose a target:

    lunch aosp_[ovation|hummingbird]-[eng|userdebug|user]

Please refer to the [AOSP Guide](https://source.android.com/source/building.html) for further building instructions.
