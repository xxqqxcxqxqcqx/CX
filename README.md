# Corona-X
Corona-X Project Manifest

# Building
Building Corona-X requires ruby version 2 or greater, a bourne-like shell (`bash`, `sh`, etc.), google `repo`, and a working C Compiler capable of building `llvm-clang`.

`repo` can be downloaded with the following command: `curl https://storage.googleapis.com/git-repo-downloads/repo > repo`
Note: See [here](https://code.google.com/p/git-repo/) or [here](http://source.android.com/source/downloading.html) for more information on installing and using repo

T
1. Make a folder to store the source
2. Open up a shell and navigate to the folder from step 1 using `cd`
4. Execute `repo init -u https://github.com/xxqqxcxqxqcqx/Corona-X -b Initial-Development` in the source folder.
5. Now execute `repo sync`. This will download the current Corona-X source tree.
6. Run `. setup.sh` or `source setup.sh` from the build directory
7. Run `make` from the build directory or `buildx` from anywhere
8. Wait for the build to complete. The System will be built into `out/root`.
