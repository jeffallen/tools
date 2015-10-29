# CHANGELOG

## 0.0.30
- Fixed the test framework, which had broken in 0.0.28.
- Fixed a race condition with launching flutter apps. The symptom was
  a black screen.

## 0.0.29
- Changed some `sky_tools` commands to enforce that they're run from a project
  root
- Fixed an issue with the starter template

## 0.0.28
- Depend on a more recent version of test, since the old version indirectly
  referenced the now-obsolete VM package dart:profiler.

## 0.0.27
- fixed issues running `sky_tools start` on Windows

## 0.0.26
- Add the --precompiled option to the build command that indicates a script
  snapshot should not be created since the executable will contain the
  precompiled instruction buffer

## 0.0.24
- fixed an issue where the process exit codes were not being set correctly

## 0.0.17
- fixed an issue when running the `sky_tools init` command

## 0.0.16
- update Flutter project template

## 0.0.15
- fix mojo_run command to support sky_engine >= 0.0.27

## 0.0.8+3
- added a dependency to the `sky_tools` package in the generated project template

## 0.0.8+2
- added `sky_tools` as an installable binary

## 0.0.8+1
- tweaks to the Sky project template

## 0.0.8
- added a new `sky_tools` binary
- added an `init` command, used to create a new Sky project
