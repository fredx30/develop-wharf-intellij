## DevEnv for Wharf with Jetbrains IDEs

This repo is meant to keep track of a decent set of defaults for Iver-Wharf development with a set of jetbrains IDEs. To
get started run `git clone --recursive --jobs 8 git@github.com:fredx30/develop-wharf-intellij.git Wharf` then open the
project in Goland or Webstorm.

Any other day at work run `git pull --recurse-submodules` to pull updates on all modules.

See [Iver-Wharf Project](https://github.com/iver-wharf) on GitHub.com

See [Iver-Wharf Docuemntation](https://iver-wharf.github.io/#/development/getting-started) on iver-wharf.github.io

See [Iver-Wharf Notes](https://iver-wharf.github.io/wharf-notes/impulse) on neuron/impulse

## File watchers

Where possible these will be tied in to binaries in the wharf-web or wharf-api repos.

#### - *.md

Remark (Semi integrated into Jetbrains IDEs)

#### - .js & .ts & .html

Eslint (Plugin)

#### - .go

Revive

#### - .scss & .css

Stylelint (Plugin)