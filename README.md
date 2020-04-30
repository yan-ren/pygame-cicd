# Pygame_playground
[![Build Status](https://travis-ci.org/yan-ren/pygame-cicd.svg?branch=release)](https://travis-ci.org/yan-ren/pygame_cicd)

## Bugs
- need to build include fonts audio img
- pygame.font.SysFont(None, 25) error
- import need reformat

## CI/CD
- one cx-build.py per project, release from release branch with tag indicating which project(with version) is released
- build only on release branch
- build executable for linux and windows
- deploy build on github releases

## Reference
- Creating single release with multiple build artifacts on github
    - https://github.com/travis-ci/travis-ci/issues/10230
- Auto tag build for github release
    - https://stackoverflow.com/questions/28217556/travis-ci-auto-tag-build-for-github-release
