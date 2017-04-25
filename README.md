# uisleuth-downloads
contains osx and win32 app releases.

## filename conventions
1. something-osx-x64.zip (macOS)
2. something.exe (windows)

## package.json options

You need to update the version number below before each release.
Example: If you want to release version 1.2.0, set the url below to /update/win32/1.1.0.

```
"win": {
  "remoteReleases": "http://download.uisleuth.com/update/win32/1.0.0/"
}

```
