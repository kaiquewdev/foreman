## 0.40.0 (2012-02-24)

* support various quoting styles in .env  [David Dollar]
* remove load_env! as it's made unnecessary by foreman run  [David Dollar]
* Provide a useful error if `foreman check` fails to find a Procfile  [R. Tyler Croy]
* update docs  [David Dollar]

## 0.39.0 (2012-02-07)

* rename bin/runner to bin/foreman-runner  [David Dollar]
* fix tgz release  [David Dollar]
* bundle update hpricot  [John Firebaugh]
* touch up .pkg release tasks  [David Dollar]

## 0.38.0 (2012-02-02)

* bring back single process starting  [David Dollar]
* more attempts at getting ci working with jruby  [David Dollar]
* ignore .rbenv-version  [David Dollar]
* force to binary encoding if supported  [David Dollar]

## 0.37.2 (2012-01-29)

* handle directories with spaces in runner  [David Dollar]
* update docs  [David Dollar]

## 0.37.1 (2012-01-29)

* use binary pipes to better handle UTF-8 data  [David Dollar]
* set up example procfile with UTF-8 item  [David Dollar]
* remove autotest  [David Dollar]
* fix up authors generation  [David Dollar]
* fix up packaging after moving tasks  [David Dollar]
* fix up changelog tasks  [David Dollar]

## 0.37.0 (2012-01-29)

* put an entire line of output inside a single mutex so we don't cross the streams  [David Dollar]
* fix race condition with process termination  [David Dollar]
* allow external custom exporters [Chris Lowder]
* fix the test for an empty string in bin/runner  [Florian Apolloner]
* ensure we have non-nil data, fixes #111  [David Dollar]
* make sure error method exists, fixes #104  [David Dollar]
* clean up chdir usage  [David Dollar]
* normalize platform names  [David Dollar]
* add windows support  [David Dollar]
* add jruby support  [David Dollar]
* pass basedir along to the runner script  [David Dollar]
* harden runner script  [David Dollar]
* add many missing specs  [brainopia]
* clean up fakefs usage in specs  [brainopia]
* runit creates a full path to export directory.  [Fletcher Nichol]

## 0.36.1 (2012-01-18)

* 0.36.1  [David Dollar]
* bump term-ansicolor in gemspec  [David Dollar]

## 0.36.0 (2012-01-17)

* 0.36.0  [David Dollar]
* sync the writer stream  [David Dollar]
* capture stderr as well  [David Dollar]

## 0.35.0 (2012-01-16)

* update rake  [David Dollar]
* 0.35.0  [David Dollar]
* Merge pull request #132 from Viximo/feature/concurrency  [David Dollar]
* Fix export specs  [Matt Griffin]
* Merge branch 'master' of https://github.com/michaeldwan/foreman into feature/concurrency  [Matt Griffin]
* default process concurrency is 0 when concurrency options specified, otherwise default concurrency is 1  [Michael Dwan]

## 0.34.1 (2012-01-16)

* 0.34.1  [David Dollar]
* fix missing start desc  [David Dollar]

## 0.34.0 (2012-01-16)

* 0.34.0  [David Dollar]
* update man page  [David Dollar]
* update docs for -d  [David Dollar]
* Merge pull request #101 from ndbroadbent/foreman  [David Dollar]
* Wrap around to the first colour when all the colours are used  [Craig R Webster]
* run specs in random order  [David Dollar]
* update rspec  [David Dollar]
* pedantry  [David Dollar]
* Set executable bit on runit run scripts.  [Matthijs Langenberg]
* Merge pull request #114 from gburt/master  [David Dollar]
* add more colors  [Gabriel Burt]
* Added option to specify app_root, if executing a Procfile from a shared location  [Nathan Broadbent]

## 0.33.1 (2012-01-16)

* 0.33.1  [David Dollar]
* Merge pull request #129 from fnichol/resolve-home-template  [David Dollar]
* Expand template path under user's home directory.  [Fletcher Nichol]

## 0.33.0 (2012-01-15)

* 0.33.0  [David Dollar]
* Revert "Merge pull request #125 from brainopia/master"  [David Dollar]

## 0.32.0 (2012-01-12)

* 0.32.0  [David Dollar]
* Merge pull request #125 from brainopia/master  [David Dollar]
* Merge pull request #121 from Viximo/feature/run  [David Dollar]
* Return some whitespace that was accidentally removed  [Matt Griffin]
* Steal the run method back from Thor so that it can be used in place for exec for running commands in the foreman environment.  [Matt Griffin]
* Remove old cruft  [brainopia]
* In case someone wants to use bin/runner directly  [brainopia]
* Fix for double fork  [brainopia]
* Use ruby exec which works with escaped cmd and replaces shell  [brainopia]
* Fix foreman to work with cmds containing pipes and redirects  [brainopia]
* Add "exec" action to allow execution of arbitrary commands with the app's environment.  [Matt Griffin]
* tweak readme  [David Dollar]

## 0.31.0 (2012-01-04)

* 0.31.0  [David Dollar]
* make fork more robust  [David Dollar]
* remove unnecessary debug  [David Dollar]
* add more information when shutting down  [David Dollar]
* Merge pull request #110 from lstoll/master  [David Dollar]
* Use different port ranges for each process type  [Lincoln Stoll]

## 0.30.1 (2011-12-23)

* 0.30.1  [David Dollar]
* require thread for mutex  [David Dollar]

## 0.30.0 (2011-12-22)

* 0.30.0  [David Dollar]
* compatibility with ruby 1.8  [David Dollar]

## 0.29.0 (2011-12-22)

* 0.29.0  [David Dollar]
* 0.28.0.pre2  [David Dollar]
* fix pipe error  [David Dollar]
* 0.28.0.pre1  [David Dollar]
* Merge branch 'fork'  [David Dollar]
* wip  [David Dollar]
* wip  [David Dollar]
* wip  [David Dollar]
* wip  [David Dollar]
* wip  [David Dollar]

## 0.27.0 (2011-12-05)

* 0.27.0  [David Dollar]
* add changelog  [David Dollar]
* Merge pull request #103 from csquared/load_env_from_irb  [David Dollar]
* refactor load_env to apply_environment  [Chris Continanza]
* rename load! to load_env!  [Chris Continanza]
* use ./.env as default  [Chris Continanza]
* load contents from env file  [Chris Continanza]
* refactor engine to expose env methods  [Chris Continanza]
* disable email notifications  [David Dollar]
* add travis config  [David Dollar]

## 0.26.1 2011-12-05

* Merge pull request #103 from csquared/load_env_from_irb   [David Dollar]
* refactor load_env to apply_environment   [Chris Continanza]
* rename load! to load_env!   [Chris Continanza]
* use ./.env as default   [Chris Continanza]
* load contents from env file   [Chris Continanza]
* refactor engine to expose env methods   [Chris Continanza]
* disable email notifications   [David Dollar]
* add travis config   [David Dollar]
