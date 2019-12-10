# Hadoop Training 2019

### Lesson 1 - 大數據 Hadoop 入門

TBD

### Lesson 2

TBD

### Lesson 3

TBD

### Lesson 4

TBD

### Lesson 5

TBD

### Lesson 6

TBD

## Branching/Release Strategy

1. Breaking/nontrivial features first go into named feature branches cut from `dev`
2. When/if a feature branch is chosen to be included in the next release, it is merged into `dev`
3. Release testing happens in `dev`
4. When confirmed/vetted, `dev` is merged into `master`, and `master` becomes the current release.
5. Small fixes explicitly intended for the next release can be PRed directly into `dev` without first needing a feature branch.
tl;dr `master` is always the current release, `dev` is always the current state of the next release. If you want to contribute a PR, we recommend you fork and work in a branch off of `dev`, then PR against `dev`. Project owners will move you into a feature branch if they deem it necessary.
