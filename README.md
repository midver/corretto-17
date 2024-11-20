## Corretto JDK

Amazon Corretto is a no-cost, multiplatform,
production-ready distribution of the Open Java Development Kit (OpenJDK).
Corretto is used internally at Amazon for production services.
With Corretto, you can develop and run Java applications
on operating systems such as Linux, Windows, and macOS.

This repository is used to track [OpenJDK upstream tip](https://github.com/openjdk/jdk).
Please look at the branches section for more information on Feature Releases.

The latest binary Corretto 17 release builds can be downloaded from https://github.com/corretto/corretto-17/releases.

Documentation is available at [https://docs.aws.amazon.com/corretto](https://docs.aws.amazon.com/corretto).

### Licenses and Trademarks

Please read these files: "LICENSE", "ADDITIONAL_LICENSE_INFO", "ASSEMBLY_EXCEPTION", "TRADEMARKS.md".

### Branches

_develop_
: The default branch. The branch that consumes development and patches to upstream jdk17u. Corretto builds are generated from this branch.

_upstream-jdk17_
: The branch is similar to master at [openjdk/jdk17](https://github.com/openjdk/jdk17). This branch merges into release branches.

_upstream-jdk17u_
: The branch is similar to master at [openjdk/jdk17u](https://github.com/openjdk/jdk17u). This branch merges into develop.

### OpenJDK Readme
```

# Welcome to OpenJDK 17 Updates!

The JDK 17 Updates project uses two GitHub repositories.
Updates are continuously developed in the repository [jdk17u-dev](https://github.com/openjdk/jdk17u-dev). This is the repository usually targeted by contributors.
The [jdk17u](https://github.com/openjdk/jdk17u) repository is used for rampdown of the update releases of jdk17u and only accepts critical changes that must make the next release during rampdown. (You probably do not want to target jdk17u).

For more OpenJDK 17 updates specific information such as timelines and contribution guidelines see the [project wiki page](https://wiki.openjdk.org/display/JDKUpdates/JDK+17u/).


For build instructions please see the
[online documentation](https://openjdk.java.net/groups/build/doc/building.html),
or either of these files:

- [doc/building.html](doc/building.html) (html version)
- [doc/building.md](doc/building.md) (markdown version)

See <https://openjdk.java.net/> for more information about
the OpenJDK Community and the JDK.
```
