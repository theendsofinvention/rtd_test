#Changelog
## And another test ...
* This is just for the lulz
## (unreleased)
### Other
* Working on it. [etcher]
## 2018.10.28.1 (2018-10-28)
### Changes
* Update empty extended commit msg description (#128) [etcher]
## 2018.10.27.1 (2018-10-27)
### Dependency update
* Build(deps): bump pytest from 3.9.2 to 3.9.3. [dependabot[bot]]
  Bumps [pytest](https://github.com/pytest-dev/pytest) from 3.9.2 to 3.9.3.
  - [Release notes](https://github.com/pytest-dev/pytest/releases)
  - [Changelog](https://github.com/pytest-dev/pytest/blob/master/CHANGELOG.rst)
  - [Commits](https://github.com/pytest-dev/pytest/compare/3.9.2...3.9.3)
## 2018.10.26.1 (2018-10-26)
### Changes
* Update empty extended commit msg description (#124) [etcher]
### Dependency update
* Build(deps): bump hypothesis from 3.79.3 to 3.80.0. [dependabot[bot]]
  Bumps [hypothesis](https://github.com/HypothesisWorks/hypothesis) from 3.79.3 to 3.80.0.
  - [Release notes](https://github.com/HypothesisWorks/hypothesis/releases)
  - [Commits](https://github.com/HypothesisWorks/hypothesis/compare/hypothesis-python-3.79.3...hypothesis-python-3.80.0)
## 2018.10.25.1 (2018-10-25)
### New
* Add timing (#120) [etcher]
  * chg: change logging time format
  * new: add timing to all major functions
### Fix
* Fix release description env var (#121) [etcher]
  * fix: dev: make sure the OS env vars are set
  * fix: dev: fix tests
  * chg: dev: update reqs
  * fix: AV does not accept empty vars
  * fix: dev: fix tests
## 2018.10.24.1 (2018-10-24)
### Fix
* Fix release description (#114) [etcher]
  * fix: fix release description
  Set an OS environ variable that'll be used to assign the release
  long description instead of relying on the commit extended message
  only.
  Fixes #108
  * fix: dev: simplify code
## 2018.10.23.4 (2018-10-23)
### Dependency update
* Build(deps): bump hypothesis from 3.79.0 to 3.79.2 (#112) [dependabot[bot]]
  Bumps [hypothesis](https://github.com/HypothesisWorks/hypothesis) from 3.79.0 to 3.79.2.
  - [Release notes](https://github.com/HypothesisWorks/hypothesis/releases)
  - [Commits](https://github.com/HypothesisWorks/hypothesis/compare/hypothesis-python-3.79.0...hypothesis-python-3.79.2)
## 2018.10.23.1 (2018-10-23)
### Dependency update
* Build(deps): bump pytest from 3.9.1 to 3.9.2. [dependabot[bot]]
  Bumps [pytest](https://github.com/pytest-dev/pytest) from 3.9.1 to 3.9.2.
  - [Release notes](https://github.com/pytest-dev/pytest/releases)
  - [Changelog](https://github.com/pytest-dev/pytest/blob/master/CHANGELOG.rst)
  - [Commits](https://github.com/pytest-dev/pytest/compare/3.9.1...3.9.2)
## 2018.10.22.1 (2018-10-22)
### Dependency update
* Build(deps): bump elib-run from 2018.10.17.1 to 2018.10.21.1. [dependabot[bot]]
  Bumps [elib-run](https://github.com/etcher-be/elib_run) from 2018.10.17.1 to 2018.10.21.1.
  - [Release notes](https://github.com/etcher-be/elib_run/releases)
  - [Commits](https://github.com/etcher-be/elib_run/compare/2018.10.17.1...2018.10.21.1)
## 2018.10.21.4 (2018-10-21)
### Dependency update
* Build(deps): bump elib-run from 2018.9.9.1 to 2018.10.17.1 (#103) [dependabot[bot]]
  Bumps [elib-run](https://github.com/etcher-be/elib_run) from 2018.9.9.1 to 2018.10.17.1.
  - [Release notes](https://github.com/etcher-be/elib_run/releases)
  - [Commits](https://github.com/etcher-be/elib_run/commits/2018.10.17.1)
## 2018.10.21.3 (2018-10-21)
### Dependency update
* Build(deps): bump hypothesis from 3.78.0 to 3.79.0. [dependabot[bot]]
  Bumps [hypothesis](https://github.com/HypothesisWorks/hypothesis) from 3.78.0 to 3.79.0.
  - [Release notes](https://github.com/HypothesisWorks/hypothesis/releases)
  - [Commits](https://github.com/HypothesisWorks/hypothesis/compare/hypothesis-python-3.78.0...hypothesis-python-3.79.0)
## 2018.10.21.2 (2018-10-21)
### Dependency update
* Build(deps): bump wheel from 0.32.1 to 0.32.2. [dependabot[bot]]
  Bumps [wheel](https://github.com/pypa/wheel) from 0.32.1 to 0.32.2.
  - [Release notes](https://github.com/pypa/wheel/releases)
  - [Changelog](https://github.com/pypa/wheel/blob/master/docs/news.rst)
  - [Commits](https://github.com/pypa/wheel/compare/0.32.1...0.32.2)
## 2018.10.21.1 (2018-10-21)
### Fix
* Remove existing graph files (#105) [etcher]
## 2018.10.15.1 (2018-10-15)
### Fix
* Revert latest elib_run update. [etcher]
  shutil.which is broken for me, that'll need a bit more work
## 2018.10.14.2 (2018-10-14)
### Changes
* Strip down console logging verbosity. [etcher]
## 2018.10.14.1 (2018-10-14)
### Changes
* Add support for site package data files (#100) [etcher]
  * chg: add support for site-package data files
  * chg: dev: update reqs
  * chg: dev: linting
## 2018.10.01.1 (2018-10-01)
### Fix
* Pytest arg fix (#97) [etcher]
  * fix pytest args for latest click
  * fix tests for new version of click
  * update reqs
## 2018.09.16.2 (2018-09-16)
### Changes
* Disable autopep8 (#95) [etcher]
  * disable autopep8
  * chg: dev: linting
  * chg: dev: linting
  * chg: dev: update reqs
## 2018.09.12.1 (2018-09-12)
### Changes
* Update pyinstaller (#91) [etcher]
  * use pyinstaller 3.4 for freezing
  * update reqs
## 2018.09.09.2 (2018-09-09)
### Fix
* Fix freeze (#90) [etcher]
  * fix pyinstaller installation for freezing
  * fix pyinstaller timeout
  * add a bit of logging
  * fix tests for freezing
  * linting
## 2018.09.02.4 (2018-09-02)
### Changes
* Prepush order (#88) [etcher]
  * update reqs should happen first
  * dev: remove unused entry in .gitignore
## 2018.09.02.3 (2018-09-02)
### Fix
* Fix conftest.py (#87) [etcher]
  * fix conftest.py
  * fix: fix fixtures names in conftest.py
  * update reqs
## 2018.09.02.2 (2018-09-02)
### Fix
* Fix missing req in setup.py (#86) [etcher]
## 2018.09.02.1 (2018-09-02)
### New
* Add graphs (#85) [etcher]
  * add graphs command
## 2018.08.31.3 (2018-08-31)
### Other
* Update reqs (#84) [etcher]