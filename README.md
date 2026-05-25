# Quick Start
* The following commands demonstrate how to set up a new Yocto workspace,
* initialize the manifest repository, synchronize all layers, configure
* the build environment, and build/run a reference image.
```
$ mkdir <workspace>                                                 # Create a new workspace directory
$ cd <workspace>                                                    # Enter the workspace
[HTTPS]
$ repo init -u https://github.com/yocto-textbook/manifest.git       # Initialize repo with the manifest
[SSH]
$ repo init -u git@github.com:yocto-textbook/manifest.git           # Initialize repo with the manifest
$ repo sync                                                         # Fetch all layers defined in the manifest
```
