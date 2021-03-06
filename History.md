
0.4.1 / 2011-03-13 
==================

  * Fixed bad substitution errors on ubuntu [Alexander Simmerl]

0.4.0 / 2011-02-14 
==================

  * Added `n ls|list` to show versions available
  * Added markers to installed and current versions for `n ls` [davglass]
  * Added `--no-check-certificate` for Github Downloads [davglass]
  * Fixed; moved abort and log up, so they are defined before calling [davglass]
  * Improved error message when tar fails (usually due to invalid version number) [davglass]

0.3.0 / 2011-01-21 
==================

  * Added `n latest` to install (or activate) latest node version released
  * Added `n --latest` to output latest node version released
  * Fixed wafadmin issue, installing lib/node/*. Closes #7

0.2.2 / 2011-01-21 
==================

  * Fixed escape

0.2.1 / 2011-01-21 
==================

  * Installing `node-waf`. Closes #5

0.2.0 / 2011-01-20 
==================

  * Added; display config options when using `n`.
    For example if you install via `n 0.3.5 --debug`,
    then `n` will display `0.3.5 --debug`.

  * Changed; `n <version>` ignores non-n installations

0.1.2 / 2011-01-20 
==================

  * Added `help` alias of `--help`
  * Fixed bash specific substitutions. Closes #1

0.1.1 / 2011-01-13 
==================

  * Fixed `use` with invalid version, added "is not installed"

0.1.0 / 2011-01-05 
==================

  * Added `n as <version> [args ...]`

0.0.4 / 2011-01-05 
==================

  * Added `which` alias of `bin`

0.0.3 / 2011-01-05 
==================

  * Added `n bin <version>` command

0.0.2 / 2011-01-05 
==================

  * Added `-` alias of `rm`

0.0.1 / 2011-01-05 
==================

  * Initial release
