# Autoflow2 package
[![OS X Build Status](https://travis-ci.org/walles/autoflow.svg?branch=master)](https://travis-ci.org/walles/autoflow) [![Windows Build Status](https://ci.appveyor.com/api/projects/status/oytr7cuefd4tpiqk/branch/master?svg=true)](https://ci.appveyor.com/project/walles/autoflow/branch/master) [![Dependency Status](https://david-dm.org/walles/autoflow.svg)](https://david-dm.org/walles/autoflow)

Format the current selection to have lines no longer than 80 characters using `cmd-alt-q` on macOS and `ctrl-shift-q` on Windows and Linux. If nothing is selected, the current paragraph will be reflowed.

This package uses the config value of `editor.preferredLineLength` when set to determine desired line length.

Unlike the [bundled autoflow package](https://atom.io/packages/autoflow), this
package offers multiple reflow algorithms, check the settings.

# Rebasing on top of upstream
* Rebase `rebase-me-on-upstream-master` atop the updated autoflow `master`
* Rebase `master` atop `rebase-me-on-upstream-master`

# TODO
* Make avoid-short-lines the default algorithm
* Change the name to autoflow2
* Make a release

## DONE
* Set up appveyor CI
* Set up Travis CI
