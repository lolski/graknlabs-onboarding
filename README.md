# Hello!

Welcome to Grakn Labs! We're delighted to have you as part of the team.

# Setup Development Tools

## Java 8
https://www.oracle.com/technetwork/java/javase/overview/java8-2100321.html

## Python 3

## Bazel

```
$ brew install bazelbuild/tap/bazel
$ bazel version
bazel version
WARNING: --batch mode is deprecated. Please instead explicitly shut down your Bazel server using the command "bazel shutdown".
Build label: {some bazel version}
Build target: bazel-out/darwin-opt/bin/src/main/java/com/google/devtools/build/lib/bazel/BazelServer_deploy.jar
Build time: Wed Aug 28 14:37:40 2019 (1567003060)
Build timestamp: 1567003060
Build timestamp as int: 1567003060
```
## IntellIJ IDEA + Bazel Plugin

https://www.jetbrains.com/idea/

# Your First Project

## Initialising The Project Structure

```
.circleci
  config.yml
.github
.bazelrc
.gitignore
dependencies
  graknlabs
    dependencies.bzl
  maven
  update.sh
VERSION
WORKSPACE
```