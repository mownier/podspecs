# mownier specs

This is a custom podspec master repo. The default CocoaPods Master Repo is quite big in terms of size which is more than 300 MB. This is also to get familiar with creating and distributing private libraries using CocoaPods.

**Adding this specs repo to CocoaPods installation**

```
$ pod repo add [REPO_NAME] [REPO_URL]
$ pod repo add mownier-specs https://github.com/mownier/podspecs.git
```

**Linking this specs repo**

```
$ cd ~/.cocoapods/repos/[REPO_NAME]
$ cd ~/.cocoapods/repos/mownier-specs
$ pod repo lint .
```

**Pushing a pod to this repo**

```
$ pod repo push [REPO_NAME] [POD_NAME].podspec
$ pod repo push mownier-specs mylib.podspec
```

