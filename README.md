
# Repro Steps

```
$ bazel build :main
INFO: Analysed target //:main (0 packages loaded).
INFO: Found 1 target...
ERROR: /Volumes/code/other/bazel-experiment-ijar-issue/BUILD:2:1: Building libmain.jar (1 source file) failed (Exit 1)
error: error reading bazel-out/darwin-fastbuild/genfiles/external/selenium_java/jar/_ijar/jar/external/selenium_java/jar/selenium-java-3.8.1-ijar.jar; error in opening zip file
Target //:main failed to build
Use --verbose_failures to see the command lines of failed build steps.
INFO: Elapsed time: 0.181s, Critical Path: 0.03s
FAILED: Build did NOT complete successfully
```
