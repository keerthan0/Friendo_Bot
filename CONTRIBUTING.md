# Contributing
Before contributing, please either claim an existing open issue or create a new issue to discuss your proposed changes with the owners of this repo before making any changes.

The overall goal for this project is provide an easy platform fo people to learn how to program, use Discord.py, and contribute to an open source project, please do not be afraid
to propose any feature at all that could add to this project. Most reasonable proposed changes will be accepted as long as they follow our guidelines.

# Fork
Create your own fork of this repo that you will make your changes on.
# Creating your feature
Always base your changes off the `develop` branch, it is the most up to date.

# Pull Request
Once you are done with your changes, you can open a pull request to our develop branch. You should be able to assign a reviewer, preferably assign the repo owner to review your changes.

Please do no make a pull request without first testing your changes on a discord server and do not make a pull request to master, if it is completely unable to run the pull request is likely to not be merged.

# Code Of Conduct
All contributions must be fairly SFW and not be overly offensive to others. Please just use best judgement. If you are unsure if your feature is appropriate, feel free to open an
issue and we can discuss it.
[MASTER]

# A comma-separated list of package or module names from where C extensions may
# be loaded. Extensions are loading into the active Python interpreter and may
# run arbitrary code.
extension-pkg-whitelist=

# Specify a score threshold to be exceeded before program exits with error.
fail-under=10.0

# Add files or directories to the blacklist. They should be base names, not
# paths.
ignore=CVS

# Add files or directories matching the regex patterns to the blacklist. The
# regex matches against base names, not paths.
ignore-patterns=

# Python code to execute, usually for sys.path manipulation such as
# pygtk.require().
#init-hook=

# Use multiple processes to speed up Pylint. Specifying 0 will auto-detect the
# number of processors available to use.
jobs=1

# Control the amount of potential inferred values when inferring a single
# object. This can help the performance when dealing with large functions or
# complex, nested conditions.
limit-inference-results=100

# List of plugins (as comma separated values of python module names) to load,
# usually to register additional checkers.
load-plugins=

# Pickle collected data for later comparisons.
persistent=yes

# When enabled, pylint would attempt to guess common misconfiguration and emit
# user-friendly hints instead of false-positive error messages.
suggestion-mode=yes
