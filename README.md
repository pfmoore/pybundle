Python application bundler
==========================

A script to bundle a Python application with its dependencies
and an embedded Python distribution, all together in a single
standalone directory.

The script depends on the launchers from the [pylaunch](https://github.com/pfmoore/pylaunch)
project to wrap the application in a "proper" Windows exe. The
script embeds copies of the launchers, so it works standalone.
