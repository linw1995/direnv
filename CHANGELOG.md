
n.n.n / 2025-10-22
==================

  * fix(use_flake): ensure clean layout directory
  * Merge pull request #1483 from direnv/dependabot/go_modules/golang.org/x/mod-0.27.0
  * Merge pull request #1489 from direnv/dependabot/github_actions/actions/setup-go-6.0.0
  * Merge pull request #1491 from direnv/dependabot/github_actions/actions/setup-python-6.0.0
  * build(deps): bump actions/setup-python from 5.6.0 to 6.0.0
  * build(deps): bump actions/setup-go from 5.5.0 to 6.0.0
  * Merge pull request #1481 from RubikCubed/aliases
  * update gomod2nix
  * build(deps): bump golang.org/x/mod from 0.25.0 to 0.27.0
  * Merge pull request #1484 from direnv/dependabot/github_actions/actions/checkout-5
  * Merge pull request #1486 from djmattyg007/fix-hook-doc
  * Fix header hierarchy of powershell section in hook documentation
  * build(deps): bump actions/checkout from 4 to 5
  * Merge pull request #1479 from direnv/shell
  * make it clear which commands are aliases in help output
  * Merge pull request #1451 from lost-melody/feat-prune-outdated
  * Merge pull request #1460 from suzuki-shunsuke/chore-add-exe-to-windows-binaries
  * Merge pull request #1462 from direnv/dependabot/github_actions/cachix/install-nix-action-31
  * Merge pull request #1476 from antoineco/fix/respect-logfmt-dash
  * shell/{bash,zsh}: don't block SIGINT why evaluating .envrc
  * fix(config): disable status logging with '-'
  * Merge pull request #1473 from direnv/gha-link
  * fix(README): add missing link to GitHub Actions
  * Merge pull request #1468 from injust/typo
  * Merge pull request #1470 from direnv/release-v2.37.1
  * Release v2.37.1
  * Merge pull request #1469 from jeremyschlatter/issue-1463
  * fix regression in displaying export errors
  * Fix `heuritic` typo
  * build(deps): bump cachix/install-nix-action from 30 to 31
  * chore: add the file extension `.exe` to windows binaries
  * Merge pull request #1457 from direnv/merge-when-green-joerg
  * fix changelog extraction
  * Merge pull request #1456 from direnv/merge-when-green-joerg
  * Merge pull request #1455 from direnv/release-v2.37.0
  * prepare-release: don't pass --delete-branch
  * Release v2.37.0
  * Merge pull request #1454 from direnv/automate-release
  * ci/nix: don't fail ci fast
  * flake.nix now provides the reference go version
  * address all new golangci linter issues
  * migrate to version 2 of golangci lint
  * build tests/dist with nix-fast-build instead of impure runs
  * drop golang caching from nix build again
  * Merge pull request #1453 from direnv/automate-release
  * also enable actions/cache for golang inside the nix build
  * enable magic-nix-cache
  * go: enable caching
  * make workflows ready for merge queue
  * Makefile: pass version/repository as arguments to prepare-release script
  * CONTRIBUTING: update release process
  * add a `make help` task to list all commands
  * automate release creation
  * feat (prune): remove outdated hashes
  * Merge pull request #1449 from direnv/export-gha
  * refactor: better error handling for Dump and Error
  * feat(direnv export gha): stenghten export format
  * docs: add github-actions page
  * man: re-generate manpages
  * man: document sub-commands
  * fix: accept true as valid DIRENV_DEBUG value (#1365)
  * refactor "export pwsh" using verbatim envvar names and verbatim strings (#1448)
  * update gomod2nix
  * chore(deps): bump golang.org/x/mod from 0.24.0 to 0.25.0
  * Merge pull request #1426 from jeremyschlatter/error-message-newline
  * Merge pull request #1444 from albertocavalcante/add-windows-arm64
  * feat: add windows arm64 target
  * chore(deps): bump actions/setup-go from 5.4.0 to 5.5.0
  * delete duplicate ansi escape code
  * chore(deps): bump actions/setup-python from 5.5.0 to 5.6.0
  * add trailing newline to error messages
  * Merge pull request #1423 from ddribin/master
  * Do not include the patch level in the Python venv name
  * Merge pull request #1421 from merrickluo/patch-1
  * Merge pull request #1424 from timbertson/nix-tmp
  * use_nix: always restore special variables
  * doc: fix link to guix manual
  * Merge pull request #1416 from direnv/prepare-release
  * document how to make it a release
  * Merge pull request #1415 from direnv/prepare-release
  * Release v2.36.0
  * Revert "Release v2.36.0"
  * Merge pull request #1414 from direnv/prepare-release
  * Release v2.36.0
  * Add `use_flox` to stdlib.sh (#1372)
  * Revert "Use PROMPT_COMMAND shortcut found in zoxide" (#1413)
  * Merge pull request #1412 from SuperSandro2000/patch-1
  * Use PROMPT_COMMAND shortcut found in zoxide
  * Merge pull request #1382 from jamesboehmer/jamesboehmer/1176-update
  * update gomod2nix
  * build(deps): bump golang.org/x/mod from 0.19.0 to 0.21.0
  * layout_python: make python version check more readable
  * A more universal fix for the python 3.14 `find_spec` deprecation warning
  * Merge pull request #1410 from direnv/fix-linting
  * fix golang lint error
  * Merge pull request #1351 from alexandear-org/internal-cmd-typos
  * Merge pull request #1353 from gemmaro/guix/watch
  * Merge pull request #1384 from bigpick/upgrade-go-1.24
  * Merge pull request #1409 from direnv/tempdir
  * use_nix: unset TMPDIR variables
  * install.sh: fix empty array error (#1406)
  * build(deps): bump actions/setup-python from 5.4.0 to 5.5.0
  * docs: note direnv version for log_{format,filter} (#1369)
  * optionally authenticate against github api during install (#1337)
  * assert minimum powershell version (#1385)
  * man: Correct duplicate usage of 'with' in the direnv(1) (#1394)
  * Don't give an error when the current directory doesn't exist (#1395)
  * build(deps): bump github.com/BurntSushi/toml from 1.4.0 to 1.5.0 (#1403)
  * Add `.envrc` to `.gitignore` (#1397)
  * build(deps): bump actions/setup-go from 5.3.0 to 5.4.0
  * build(deps): bump cachix/install-nix-action from 30 to 31
  * stdlib: use_guix: Enable the watching of Guix related files.
  * add support to fully reproducible guix shells (#1392)
  * chore: cleanup comments
  * chore: dont upgrade version.txt yet
  * chore: remove golangci-lint version debug
  * feat: nix go1.24?
  * feat: nix go1.24?
  * chore: debug golangci-lint vers
  * chore: revert golangci.yml
  * chore: add missing brews
  * fix: FileTime pointer for golangci-lint
  * docs: go version
  * fix: remove gomod2nix pkgs inherit, back to 1.24
  * fix: downgrade to 1.22
  * fix: downgrade to 1.23
  * feat: Upgrade go 1.20->1.24
  * build(deps): bump actions/setup-python from 5.3.0 to 5.4.0
  * build(deps): bump actions/setup-go from 5.2.0 to 5.3.0
  * fix: escape newlines in generated vimscript (#1347)
  * README: list mise as an alternative
  * build(deps): bump actions/setup-go from 5.1.0 to 5.2.0
  * ci(mergify): upgrade configuration to current format (#1355)
  * feat: logging filter (#1336)
  * fix typos in const, comments, and CHANGELOG
  * build(deps): bump actions/setup-python from 5.2.0 to 5.3.0
  * build(deps): bump actions/setup-go from 5.0.2 to 5.1.0
  * Release v2.35.0
  * build(deps): bump cachix/install-nix-action from 29 to 30
  * build(deps): bump cachix/install-nix-action from V28 to 29
  * docs: Add version requirement for load_dotenv option (#1326)
  * ✏️ Fix broken link (#1327)
  * build(deps): bump cachix/install-nix-action from V27 to 28
  * build(deps): bump actions/setup-python from 5.1.1 to 5.2.0
  * feat: add opam support (#1298)
  * Update elvish docs (#1305)
  * build(deps): bump actions/setup-go from 5.0.1 to 5.0.2
  * build(deps): bump actions/setup-python from 5.1.0 to 5.1.1
  * update gomod2nix
  * build(deps): bump golang.org/x/mod from 0.18.0 to 0.19.0
  * stdlib: enable flakes when use flake is used (#1299)
  * test: Fix Murex python-layout test (#1293)
  * Flake check (#1294)
  * Change Guix link to its package search. (#1268)
  * chore: remove repetitive words (#1271)
  * fix: close tmp file (#1272)
  * update gomod2nix
  * build(deps): bump golang.org/x/mod from 0.17.0 to 0.18.0
  * fix release script
  * build(deps): bump github.com/BurntSushi/toml from 1.3.2 to 1.4.0 (#1283)
  * build(deps): bump cachix/install-nix-action from 26 to 27
  * build(deps): bump actions/setup-go from 5.0.0 to 5.0.1
  * update gomod2nix
  * build(deps): bump golang.org/x/mod from 0.16.0 to 0.17.0
  * stdlib: export GOBIN for layout_go (#1286)
  * build(deps): bump actions/setup-python from 5.0.0 to 5.1.0
  * add NuShell into list of supported shells (#1260)
  * stdlib: update layout_python to resolve deprecation warning (#1176)
  * update gomod2nix
  * build(deps): bump golang.org/x/mod from 0.15.0 to 0.16.0
  * build(deps): bump cachix/install-nix-action from 25 to 26 (#1252)
  * direnv edit: editor when EDITOR not found, closes #1246 (#1247)
  * Fix using PWD in .env files (#1052)
  * Release v2.34.0
  * Avoid use of regex in bash hook output (#1043)
  * stdlib: use_flake: don't keep old generations around (#1089)
  * Update zsh syntax in internal/cmd/shell_zsh.go (#1075)
  * Add shell setup instructions for oh-my-zsh (#1070)
  * stdlib: use_node: strip leading v from version (#1071)
  * fixup! Fix: `use_julia` should not set LD_LIBRARY_PATH (#900)
  * Fix: `use_julia` should not set LD_LIBRARY_PATH (#900)
  * docs: document XDG_DATA_HOME (#1185)
  * feat: add Murex support (#1242)
  * Update nixpkgs (#1243)
  * update gomod2nix
  * build(deps): bump golang.org/x/mod from 0.14.0 to 0.15.0
  * Merge pull request #1067 from Janik-Haag/master
  * feat: hide env diff (#1234)
  * Revert "feat: hide env diff (#1233)"
  * feat: hide env diff (#1233)
  * README.md, man pages: it's typos (#1230)
  * Merge pull request #1229 from Maxim-Durand/master
  * Merge branch 'direnv:master' into master
  * added Upper case when needed to commands descriptions.
  * made 'direnv export' non private and improved its description to show supported shells
  * refactored supported shell to use a map instead of switch case. Added
  * build(deps): bump cachix/install-nix-action from 24 to 25
  * Merge pull request #1226 from Maxim-Durand/master
  * refactored assertEqual method to explicitely specify what value is the expected
  * added go test for systemd exporter
  * added parsing and formatting for systemd exporter
  * added first version of value sanitization (not tested yet)
  * added systemd shell for export
  * Update stdlib.sh to avoid deprecation warning (#1221)
  * build(deps): bump github/codeql-action from 2 to 3
  * build(deps): bump actions/setup-go from 4.1.0 to 5.0.0
  * build(deps): bump actions/setup-python from 4.7.1 to 5.0.0
  * fix: support Bash 5.1 array PROMPT_COMMAND (#1208)
  * feat: allow to disable warn timeouts (#1209)
  * Merge pull request #1191 from Jasha10/Jasha10-patch-1
  * Update installation.md for Gentoo (#1206)
  * build(deps): bump cachix/install-nix-action from 23 to 24
  * update gomod2nix
  * build(deps): bump golang.org/x/mod from 0.13.0 to 0.14.0
  * fix: add missing deps for release in go.mod
  * Release v2.33.0
  * update gomod2nix
  * build(deps): bump github.com/mattn/go-isatty from 0.0.19 to 0.0.20
  * Merge pull request #1198 from direnv/add-watch-print-command
  * add watch-print command
  * make: add missing source dependencies
  * drop duplicate flake-utils input
  * direnv.toml.1.md: add examples for $HOME expansion
  * feat: alias `direnv disallow` to deny (#1182)
  * Remove redundant nil check in `CommandsDispatch` (#1166)
  * Don't prompt to allow if user explicitly denied (#1158)
  * update gomod2nix
  * build(deps): bump golang.org/x/mod from 0.12.0 to 0.13.0
  * readme: Update autoenv section (#1184)
  * man/direnv-stdlib: fix obsolete opam-env example (#1170)
  * add a Nushell section to `hook.md` (#1175)
  * Merge pull request #1171 from bamsammich/master
  * build(deps): bump actions/setup-python from 4.7.0 to 4.7.1 (#1179)
  * make pwsh tests work in nix env
  * update NixOS installation instructions
  * all pwsh tests added
  * file rename
  * powershell tests
  * update docs
  * powershell support
  * use new non-overlay interface in gomod2nix
  * Merge pull request #1102 from direnv/dependabot/go_modules/github.com/mattn/go-isatty-0.0.19
  * go.mod: bump go version
  * update-gomod2nix: update correct file
  * build(deps): bump github.com/mattn/go-isatty from 0.0.14 to 0.0.19
  * switch to gomod2nix
  * update vendorHash
  * build(deps): bump github.com/BurntSushi/toml from 1.2.0 to 1.3.2
  * add support for armv7l platform (#1162)
  * find rc file from DIRENV_FILE; find allowPath for loadedRC (#1157)
  * `direnv status --json` (#1142)
  * build(deps): bump cachix/install-nix-action from 22 to 23
  * build(deps): bump actions/checkout from 3 to 4
  * README: add light commercial support
  * build(deps): bump actions/setup-go from 4.0.1 to 4.1.0
  * update vendorHash
  * build(deps): bump golang.org/x/mod from 0.5.1 to 0.12.0
  * ci/update-vendor-hash: add nix_path
  * Merge pull request #1151 from direnv/joerg-ci
  * update-vendor-hash: switch to nix-build
  * update-vendor-hash: make it directory independent
  * update-vendor-hash: don't rely on NIX_PATH for importing nixpkgs
  * ci: fix update-vendor-hash path
  * build(deps): bump actions/setup-go from 3.4.0 to 4.0.1
  * mergify: fix the merge conditions
  * fix: quote tcsh $PATH, to avoid failure on whitespace (#1139)
  * Print correct path in source_env log message (#1144)
  * Merge pull request #1148 from Mic92/cachedirtag
  * automatically update vendor hashes for dependabot updates (#1145)
  * nix: add python to the test environment
  * stdlib: create CACHEDIR.TAG inside .direnv
  * Merge pull request #1146 from Mic92/nixpkgs-bump
  * fix macos build
  * add mergify configuration (#1147)
  * fix elvish test
  * fix new shellcheck errors
  * update niv
  * update nixpkgs
  * nix: fix homepage quoting and set meta.mainProgram
  * dist: shrink the binaries by ~33%
  * doc: show how to run tests (#1137)
  * build(deps): bump actions/checkout from 3.5.2 to 3.5.3 (#1118)
  * build(deps): bump actions/setup-python from 4.3.0 to 4.7.0 (#1131)
  * build(deps): bump cachix/install-nix-action from 20 to 22 (#1124)
  * (docs) Fix broken links in installation.md (#1110)
  * Update direnv.toml.1.md (#1099)
  * Release v2.32.3
  * Fix incorrect escape sequences during Loads under git-bash (#1085)
  * Add Windows installation with winget (#1096)
  * doc: link 12factor webpage for more clarity (#1095)
  * Skip some tests for IBM Z mainframe's z/OS operating system (#1094)
  * build(deps): bump actions/checkout from 3.5.0 to 3.5.2 (#1090)
  * Fix golangci-lint issues (#1086)
  * build(deps): bump actions/checkout from 3.3.0 to 3.5.0 (#1080)
  * build(deps): bump cachix/install-nix-action from 19 to 20 (#1068)
  * added fetchurl manpage link to README.md
  * build(deps): bump cachix/install-nix-action from 18 to 19 (#1059)
  * build(deps): bump actions/checkout from 3.1.0 to 3.3.0 (#1047)
  * website: add Plausible analytics
  * stdlib: use_guix: Switch to guix shell. (#1045)
  * Stat the already open rc file rather than another path based one on it (#1044)
  * Remove deprecated io/ioutil uses (#1042)
  * Spelling fixes (#1041)
  * Appease Go 1.19 gofmt (#1040)
  * pass BASH_PATH to make, matches the nixpkgs derivation (#1006)
  * stdlib/layout_python: exclude patchlevel from $python_version (#1033)
  * build(deps): bump actions/setup-go from 3.3.1 to 3.4.0 (#1023)
  * Release v2.32.2
  * Minor typo fix (#1013)
  * installer.sh: make direnv executable for all
  * test: remove mentions of DIRENV_MTIME (#1009)
  * install.sh: can specify direnv version (#1012)
  * build(deps): bump actions/setup-python from 4.2.0 to 4.3.0 (#997)
  * build(deps): bump cachix/install-nix-action from 17 to 18 (#999)
  * build(deps): bump actions/checkout from 3.0.2 to 3.1.0 (#998)
  * build(deps): bump actions/setup-go from 3.3.0 to 3.3.1 (#1003)
  * fix(test): use lowercase -d flag for base64 decoding of DIRENV_DIFF (#996)
  * Fix broken link (#991)
  * elvish: replace deprecated `except` with `catch` (#987)
  * `$XDG_CONFIG_HOME/direnv/direnv.toml` => add (typically ~/.config/direnv/direnv.toml) (#985)
  * build(deps): bump actions/setup-go from 3.2.1 to 3.3.0 (#983)
  * build(deps): bump actions/setup-python from 4.1.0 to 4.2.0 (#978)
  * build(deps): bump github.com/BurntSushi/toml from 1.1.0 to 1.2.0 (#974)
  * fix path escaping (#975)
  * add quickenv to Related projects (#970)
  * build(deps): bump actions/setup-python from 4.0.0 to 4.1.0 (#971)
  * build(deps): bump actions/setup-go from 3.2.0 to 3.2.1 (#972)
  * Merge pull request #969 from gertvdijk/add-stdlib-pyenv-docs
  * Add stdlib's layout_pyenv to docs
  * Sync man/direnv-stdlib.1.md from manual changes to man/direnv-stdlib.1
  * Update layout anaconda to accept a path to a yml file (#962)
  * stdlib: only use ANSI escape on TTY (#958)
  * Release v2.32.1
  * vendor go-dotenv (#955)
  * Support custom VIRTUAL_ENV for layout_python (#876)
  * Release v2.32.0
  * update go-dotenv
  * build(deps): bump actions/setup-go from 3.1.0 to 3.2.0 (#950)
  * Enable ppc64le builds (#947)
  * go: bump golang.org/x/sys for linux/loong64 support (#946)
  * fetchurl: only store 200 responses (#944)
  * Ensure status log messages are printed with normal color (#884)
  * build(deps): bump actions/setup-go from 3.0.0 to 3.1.0 (#943)
  * Clarify handling of .env files (#941)
  * chore: Enable codeql action (#938)
  * chore: Set permissions for GitHub actions (#937)
  * Add convenient aliases for allow/deny commands (#935)
  * build(deps): bump actions/checkout from 3.0.1 to 3.0.2 (#936)
  * Update shell_elvish.go (#896)
  * build(deps): bump actions/checkout from 3.0.0 to 3.0.1 (#933)
  * Expand ~/ in whitelist paths (#931)
  * Merge pull request #874 from direnv/refactor
  * rc: stop using --noprofile --norc
  * rc: prepare stdin earlier
  * rc: install interrupt handler earlier
  * stdlib: factor out stdlib preparation
  * stdlib.sh: remove dependency on tput (#932)
  * fix CI
  * feat: allow conda environment names to be detected from environment.yml (#909)
  * fetchurl: store files as hex (#930)
  * Use setenv in vim to allow non alphanumeric vars (#901)
  * source_up_if_exists: A strict_env compatible version of source_up (#921)
  * build(deps): bump github.com/BurntSushi/toml from 0.4.1 to 1.1.0 (#924)
  * man: clarify paths (#929)
  * source_env: show full path (#870)
  * add: information about bin_path (#920)
  * build(deps): bump actions/checkout from 2.4.0 to 3.0.0 (#922)
  * build(deps): bump cachix/install-nix-action from 16 to 17 (#925)
  * build(deps): bump actions/setup-go from 2.1.5 to 3.0.0 (#923)
  * Treat `mingw*` as windows (direnv/direnv#918) (#919)
  * Merge pull request #910 from mmlb/export-github-actions
  * Add test for export gha
  * Add gha shell for GitHub Actions
  * Sort shells in DetectShell
  * installation.md: Fix Fedora package link (#915)
  * Release v2.31.0
  * Don't load .env files by default (#911)
  * Update direnv-stdlib.1.md
  * `~/.config/direnv/direnvrc` is the default
  * doc: fix the broken link to arch linux (#892)
  * Re-add accidentally deleted comment line (#881)
  * fix version test
  * Release v2.30.3
  * Allow skipping `.env` autoload (#878)
  * stdlib: add `env_vars_required` (#872) (#872)
  * Test whether version.txt contains semantic version (#871)
  * Release v2.30.2
  * version: trim surrounding spaces (#869)
  * build(deps): bump actions/setup-go from 2.1.4 to 2.1.5 (#866)
  * move most code under internal/cmd (#865)
  * Release v2.30.1
  * rc: ignore .envrc and .env if they are not files (#864)
  * Release v2.30.0
  * embed version.txt
  * go mod update
  * Add automatic `.env` load (#845)
  * Resolve symlinks during `direnv deny` (#851)
  * update installer for Apple Silicon (#849)
  * stdlib: use_flake handle no layout dir (#861)
  * embed stdlib.sh (#782)
  * make dist: remove references to Go
  * Release v2.29.0
  * stdlib: add use_flake function (#847)
  * man: rebuild with go-md2man 2.0.1
  * nix: bump nixpkgs (#846)
  * docs(direnv.toml) Add config.toml clarification (#831)
  * build(deps): bump cachix/install-nix-action from 15 to 16 (#842)
  * ci: bump actions
  * docs(install): fix macos links (#841)
  * Corrects stdlib link in Ruby docs (#837)
  * stdlib.sh: Fix removal of temp file (#830)
  * build(deps): bump cachix/install-nix-action from 13 to 14 (#827)
  * build(deps): bump actions/setup-go from 2.1.3 to 2.1.4 (#824)
  * install.sh: add aarch64 support
  * Updated conditional for zsh hook to be more forgiving (#808)
  * Partially Revert "README: FreeNode -> Matrix"
  * README: FreeNode -> Matrix
  * Add -r flag for matching Git branches with a regexp (#800)
  * Add docs about pipenv (#797)
  * Enable syntax hilights to the quick demo code (#752)
  * build(deps): bump cachix/install-nix-action from v12 to v13 (#791)
  * Fixed extra quotes for lower alpha characters (#783)
  * Remove noisy warning about PS1 again (#781)
  * Release v2.28.0
  * Merge pull request #779 from wingrunr21/go_1_16
  * Build for darwin/arm64. Resolves #738
  * Update to go 1.16
  * test: Fix errors for elvish test (#767)
  * tcsh: fix variable escaping (#778)
  * Change DESTDIR to PREFIX in development.md (#774)
  * go: use the /v2 prefix (#765)
  * Relax README's recommendation for nix-direnv (#763)
  * man/direnv.1.md: add FILES section (fix #758) (#759)
  * GNUmakefile: update go-md2man install instruction
  * Release v2.27.0
  * Add/update fish tests (#754)
  * build(deps): bump golang.org/x/mod from 0.4.0 to 0.4.1 (#749)
  * Fix typo "avaible" in install.sh (#750)
  * docs: improve the use_node documentation
  * fixed fish shell hook to work with eval (#743)
  * packaging: stop vendoring the Go code (#739)
  * Merge pull request #740 from zimbatm/nixpkgs-update
  * dist: remove darwin/386
  * golangci-lint: update checks
  * nix: update to nixpkgs@nixos-20.09
  * GNUmakefile: change packaging. DESTDIR -> PREFIX, fish hook (#741)
  * Release v2.26.0
  * updated fish hook support issue (#732)
  * ci: add basic windows CI (#737)
  * test: fix shellcheck usage in ./test/stdlib.bash
  * test: fix use_julia test for NixOS
  * remove dead code: rootDir
  * fix: create temp dir in current working dir for one test (#735)
  * Add `dotenv_if_exists` (#734)
  * stdlib: add watch_dir command (#697)
  * Release v2.25.2
  * v2.25.1
  * stdlib.go: re-generate
  * README: remove old Azure badge
  * build(deps): bump golang.org/x/mod from 0.3.0 to 0.4.0 (#730)
  * Release v2.25.0
  * dist: add linux/arm64 and linux/ppc64
  * Added use_nodenv to stdlib (#727)
  * Fix proposal for  #707, broken direnv compatibility under Windows (#723)
  * fix: layout anaconda <env_name_or_prefix> (#717)
  * Add on_git_branch command to detect whether a specific git branch is checked out (#702)
  * Release v2.24.0
  * Update README.md
  * direnv_load: avoid leaking DIRENV_DUMP_FILE_PATH (#715)
  * Add strict_env and unstrict_env (#572)
  * stdlib: add `use_vim` to source local vimrc (#497)
  * stdlib: add source_env_if_exists (#714)
  * Wording (#713)
  * build(deps): bump actions/checkout from v2.3.3 to v2.3.4 (#709)
  * build(deps): bump cachix/install-nix-action from v11 to v12 (#710)
  * Fix XDG_CACHE_HOME path (#711)
  * rc: make file existence check more robust (#706)
  * Release v2.23.1
  * fix: handle links on Mac when using `allow` (#696)
  * fix: use restored env in exec (#695)
  * stdlib: add basename and dirname from realpath (#693)
  * stdlib.sh: remove tabs
  * dist: compile all the binaries statically
  * Release v2.23.0
  * stdlib: add source_url function (#562)
  * direnv: add fetchurl command (#686)
  * shell: Update Elvish hook to replace deprecated `explode` (#685)
  * go mod update
  * build(deps): bump actions/setup-go from v1 to v2.1.3 (#683)
  * build(deps): bump cachix/install-nix-action from v6 to v11 (#682)
  * build(deps): update actions/checkout requirement to v2.3.3 (#681)
  * ci: add dependabot
  * Release v2.22.1
  * Look for stdlib in DIRENV_CONFIG (#679)
  * re-generate the man pages
  * stdlib: use Bash 3.0-compatible array expansion (#676)
  * Clarify path to direnv.toml (#678)
  * stdlib/use_julia: fix a bug in parameter substitution for empty or (#667)
  * man: update the layout_go documentation
  * stdlib:  adds GOPATH/bin to PATH (#670)
  * Release v2.22.0
  * stdlib: use_julia <version> (#666)
  * stdlib: semver_search (#665)
  * direnv-stdlib.1: add layout julia (#661)
  * README: spelling correction (#660)
  * README.md: add shadowenv to similar projects (#659)
  * docs: remove Snap from the installations
  * OSX -> macOS (#655)
  * Update shell_fish.go to use \X for UTF encoding (#584)
  * Change XDG_CONFIG_DIR to XDG_CONFIG_HOME (#641)
  * Streamline core algorithm of export and exec (#636)
  * test: add failure test-case (#637)
  * Release v2.21.3
  * Replace `direnv expand_path` with pure bash (#631)
  * Fix #594 - write error to fd 3 on Windows (#634)
  * Make direnv hook output work on Windows (#632)
  * Update hook.md to remove ">" typo in Fish instructions (#624)
  * stdlib: `layout go` adds layout dir to GOPATH (#622)
  * direnv-stdlib.1: add layout php (#619)
  * stdlib: add PATH_rm <pattern> [<pattern> ...] (#615)
  * Error handling tuples (#610)
  * re-generate
  * Merge pull request #607 from punitagrawal/master
  * test: elvish: Fix evaluation function
  * stdlib.sh: Re-write grep pattern to avoid shell escape
  * man: Escape '.' at the beginning of line to remove manpage warning
  * stdlib: fix direnv_config_dir usage (#601)
  * direnv version: improve error message (#599)
  * README: fix NixOS link in installation.md (#589)
  * stdlib: add direnv_apply_dump <file> (#587)
  * Simplify direnv_load and make it work even when the command crashes. (#568)
  * docs: fix fish installation instruction
  * test: test for utf-8 compatibility
  * config: add [global] section
  * config: add strict_env option
  * config: fix warn_timeout parsing (#582)
  * Github action for releases
  * config: fix the configuration file selection
  * stdlib: fix shellcheck warnings
  * Release v2.21.2
  * stdlib: revert the `set -euo pipefail` change
  * fixup! direnv allow: create allow dir during migration
  * direnv allow: create allow dir during migration
  * Release v2.21.1
  * shell.nix: add git-changelog to the environment
  * stdlib: fix unused variable in `use node`
  * stdlib: fix unused variable in `source_up`
  * test: add stdlib test skeleton
  * add dist release utility
  * Release v2.21.0
  * fixup! direnv version <version_at_least>
  * direnv version <version_at_least>
  * allow: fix output message. Fixes #558
  * handle SIGINT during export in bash
  * export: display the full RC path
  * formatting: a bit more refactoring
  * ci: use GitHub Actions instead of Azure Pipelines
  * direnv allow: add migration to the new location
  * more formatting cleanup
  * golangci-lint: add to the mix and fix all warnings
  * .gitignore: update the test ignores
  * bug-fix paths when PWD has a symlink in it
  * fixup! stdlib: dotenv: handle undefined variable
  * stdlib: dotenv: handle undefined variable
  * change where the allow files are being stored
  * move xdg into it's own mini package
  * ci: do a round of cleanup
  * stdlib: source files from .config/direnv/lib/*.sh
  * stdlib: be more strict
  * devenv: use go modules
  * warn if PS1 is being exported
  * stdlib: direnv_load can now handle stdout outputs
  * direnv status: also show the config
  * direnv exec: improve the error message
  * mark direnv watch as private
  * shell: fix elvish hook
  * Use `fish_postexec` to make sure direnv hook executed 'after' the directory has changed when using `cd`.
  * fix cmd_watch_list
  * fixup! stdlib: add watch_list command
  * stdlib: add watch_list command
  * watch_file: fix usage
  * stdlib: add layout_julia
  * staticcheck (#543)
  * adds experimental curl based installer (#539)
  * Update README.md (#536)
  * Add link to asdf-direnv. (#535)
  * docs: fix invalid link (#533)
  * Pin nixpkgs to current NixOS 19.09 channel (#526)
  * layout_pyenv: support multiple python versions (#525)
  * stdlib: fix path_add to not leak local variables
  * Watch more than one file at a time. (#524)
  * Update README.md
  * Fix `source_up` docs to explain that search starts in parent directory (#518)
  * site: use jekyll to render the website
  * Merge pull request #505 from eddies/venv-pyenv
  * Adds layout_pyenv
  * layout_python: prefer venv over virtualenv. Do not export VIRUAL_ENV if $python_version is unavailable or a virtual environment does not exist/can't be created
  * stdlib: use venv module for python if available
  * shell: improve zsh hook (#514)
  * Use `fish_preexec` hook instead of `fish_prompt` (#512)
  * Handle failing pipenv on empty file and avoid an extra pipenv execution (#510)
  * github: fix the issue templates
  * Update issue templates
  * rename the configuration to direnv.toml (#498)
  * direnv exec: DIR is always necessary (#493)
  * make: handle when /dev/stderr doesn't exist (#491)
  * Merge pull request #489 from direnv/config-direnv-warn-timeout
  * ci: only release on master
  * config: introduce warn_timeout
  * stdlib: fix source_env when the file doesn't exists (#487)
  * Release v2.20.1 (#486)
  * Release v2.20.0 (#485)
  * Merge pull request #468 from zimbatm/ensure-stderr
  * export: always output something
  * test: fix shellcheck warnings
  * Merge pull request #484 from direnv/azure-pipelines
  * ci: release job
  * ci: replace Travis CI with Azure Pipelines
  * nix: pin nixpkgs
  * stdlib: fix shellcheck SC1090 issues
  * fixup! fix arity mismatch for elvish (#482)
  * fix arity mismatch for elvish (#482)
  * issue template: add target shell (#479)
  * README: Remove duplicate build badge (#465)
  * Fix bash hook (#473)
  * README: add note about auth (#463)
  * Merge pull request #469 from zimbatm/better-tests
  * Use source instead of eval on fish hook
  * Make fish tests work with fish 3.0
  * Fix usage of mktemp in tests
  * test-{bash/zsh}: Make direnv_eval match hook code
  * Add missing tests for zsh as well
  * Fix tests for tcsh
  * Corrects reverse patching when using exec cmd. (#466)
  * Fix for #461 - Perform stricter search for existing Anaconda environments (#462)
  * Doc: change nixos link (#460)
  * Release v2.19.2 (#459)
  * file_times: check Stat and Lstat (#457)
  * Add shell code highlight to example (#456)
  * Release v2.19.1 (#454)
  * Merge pull request #452 from grahamc/lstat
  * file_times: use Lstat as well as Stat
  * test a scenario of where the symlink changes
  * Merge pull request #450 from zimbatm/nix-build
  * fix nix-build
  * test the nix-build
  * Release v2.19.0 (#441)
  * Fix typo in readme (#437)
  * update dependencies (#433)
  * Spelling. (#430)
  * stdlib: fix SC2239 (#432)
  * README: add Snap to the list of distributions (#426)
  * Release v2.18.2 (#418)
  * make: generate direnv.exe on windows (#417)
  * Merge pull request #416 from zimbatm/release-2.18.1
  * Release v2.18.1
  * travis: fix the release process
  * Merge pull request #415 from zimbatm/release-2.18.0
  * Release v2.18.0
  * makefile: generate formatted version code
  * stdlib: add DIRENV_IN_ENVRC (#414)
  * Fix typo in readme. (#412)
  * Merge pull request #407 from zimbatm/direnv-dump-shell
  * direnv dump can now dump to arbitrary shells
  * add a new "gzenv" shell
  * move gzenv into new package
  * shell: introduce a dump capability
  * cleanup the shells
  * Add alias '--version' to version command. Closes #377. (#404)
  * Correctes spelling of openSUSE (#403)
  * testing: elvish 0.12 is released now (#402)
  * Merge pull request #397 from zimbatm/readme-packaging-status
  * README: add packaging status badge
  * README: remove equinox installation
  * direnv show_dump: new command to debug encoded env (#395)
  * Document possibility to unset vars (#392)
  * stdlib: fix typo
  * go dep: update Gopkg.lock
  * make: don't make shfmt a dependency
  * Avoid to add unnecessary trailing semicolon character (#384)
  * add asdf to the list of known projects
  * stdlib.go: re-generate
  * Add PHP layout to stdlib (#346)
  * make: fix formatting
  * README: add build status badge
  * Overhaul the build system (#375)
  * stdlib, layout_pipenv: handle `$PIPENV_PIPFILE` (#371)
  * README: improve the source build instructions
  * Release v2.17.0
  * Merge pull request #369 from direnv/hook-expand-direnv-path
  * stdlib: direnv_load: disallow watching in child
  * hook: pin the direnv path
  * README: add OpenSuSE to the list of distros
  * Revert "use_nix: unset IN_NIX_SHELL"
  * Release v2.16.0
  * default.nix: fix for nix-shell
  * direnv: add support for elvish (#357)
  * Add the usage of source_up to the README (#347)
  * config: allow to disable stdin on eval (#351)
  * default.nix: fix compilation
  * Release v2.15.2
  * .travis-ci.yml cleanup (#342)
  * re-generate the docs
  * Fix lintian warnings (#340)
  * Release v2.15.1
  * fix support for go 1.10 (#339)
  * Release v2.15.0
  * config: add bash_path config
  * Add manpage for config.toml. (#337)
  * Add a TOML configuration file, support whitelisting envrc's regardless of their content's hash (#332)
  * mention emacs-direnv on website sidebar (#330)
  * use_nix: unset IN_NIX_SHELL
  * github: add issue template
  * Add anaconda support (#312)
  * Release v2.14.0
  * direnv edit: run the command through bash
  * direnv version: make public
  * website: update ditto to v0.15
  * update generated files
  * Add support for Pipenv layout (#314)
  * Release v2.13.3
  * update go-dotenv. fixes ''='' issue
  * Release v2.13.2
  * direnv edit: fix path escaping
  * stdlib: fix find_up
  * stdlib: use absolute path in source_up
  * go-dotenv: update to latest master
  * remove ruby as a build dependency
  * Release v2.13.1
  * stdlib: make direnv_layout_dir lazy (#298)
  * Release v2.13.0
  * Permit empty NODE_VERSION_PREFIX variable
  * pwd: Don't use -P to remove symlinks (#295)
  * use the new `dep` tool to manage dependencies
  * restore support for go 1.5
  * remove go 1.5 from the supported releases
  * dotenv: move to vendor folder
  * Fix typo in README.md (#292)
  * README: Add MacPorts to the list of packages (#291)
  * README: add disambiguation section
  * Merge pull request #290 from direnv/direnv_layout_dir
  * stdlib: configurable direnv_layout_dir
  * stdlib: source the direnvrc directly
  * also reload when mtime goes back in time
  * Prevent $HOME path from being striked (#287)
  * Release v2.12.2
  * stdlib layout_python: fixes on no arg
  * Release v2.12.1
  * stdlib path_add: fixes #278
  * README: git clone from HTTPS
  * fix the install from source doc
  * Release v2.12.0
  * Support multiple items in path_add and PATH_add (#276)
  * https screencasts
  * add a configurable DIRENV_WARN_TIMEOUT option (#273)
  * rewrite the dotenv parsing
  * dotenv: support commented lines
  * stdlib watch_file(): escaping fix
  * Only output color if $TERM is not dumb (#264)
  * Rebuild stdlib.go
  * Pass additional args to virtualenv (#261)
  * Fix the watch_file documentation
  * Release v2.11.3
  * Fix/252 node version sorting (#255)
  * Release v2.11.2
  * Typo in MANPATH_add always generates "PATH missing" error
  * Release v2.11.1
  * Release v2.11.0
  * Test direnv with go 1.8 (#254)
  * Add warning about source_env/up
  * Fix go-md2man install instruction
  * Document MANPATH_add
  * stdlib.sh: introduce MANPATH_add <path> (#248)
  * Show the equinox download page
  * Release v2.10.0
  * Commit generated files
  * Add `use guix` and update README to mention GNU Guix (#242)
  * fix tcsh escaping (#241)
  * Build release with Go 1.7
  * Merge pull request #237 from domcleal/fedora
  * Link to Fedora package
  * Use go-md2man to generate the man pages
  * Change communication methods
  * Add more escaping
  * Merge pull request #226 from earthrid/master
  * Fix some typos and reword in a few places
  * Release v2.9.0
  * stdlib, use_nix: fixes watching of files
  * default.nix to build direnv during development
  * Simplify ranges without values
  * Fix `go vet` warnings
  * Added watches for default.nix and shell.nix
  * Merge pull request #212 from direnv/bash-path
  * Merge pull request #220 from f440/permit-empty-NODE_VERSION_PREFIX-variable
  * Permit empty NODE_VERSION_PREFIX variable
  * layout_python: fail properly when python is not found
  * Handle `direnv current` with no argument
  * Document package and binary releases better
  * Build-time bash path
  * Release v2.8.1
  * Fix travis dist release
  * Release v2.8.0
  * Merge pull request #208 from direnv/watch-dotenv
  * Merge pull request #209 from direnv/export-json
  * stdlib: watch for dotenv changes
  * direnv export json: a new universal format
  * refactor shells
  * Remove allow files in tests
  * prune: better desc
  * stdlib: document the `watch` function
  * Merge pull request #153 from avnik/master
  * Merge pull request #206 from nyarly/nyarly-master
  * Adding a .gitkeep so that tests will always work
  * Some general cleanup. Also fixed a bug introduced in edit
  * Fixing "lagging" on first entry
  * Recommend IRC instead of Gitter
  * Adding watch_file() to stdlib
  * Stripped out now obsolete MTIMES code
  * WATCHES passes all tests
  * Fixes to status and export, adds direnv current <path>
  * Switched export to using file times instead of MTIME
  * File times impl working, tested
  * Beginning process of watching multiple files
  * Merge pull request #200 from msabramo/README_add_caveat_that_envrc_must_be_valid_bash_syntax
  * README.md: Caveat that .envrc must be valid bash
  * Change OSX build flags. Fixes #194
  * Merge pull request #192 from JelF/add-gentoo-overlay-to-readme
  * added reference to gentoo go-overlay to readme
  * Merge pull request #191 from miketheman/preserve_bash_exit_code
  * Preserve previous BASH status code
  * Merge pull request #189 from blueyed/README-mention-zsh-autoenv
  * README: mention zsh-autoenv
  * Merge pull request #187 from wilmoore/use-node-fuzzy-selection
  * Add fuzzy matching to `use node` stdlib function
  * compile
  * Merge pull request #185 from wilmoore/add-use-node-to-stdlib
  * add `use node` stdlib docs
  * return 1 instead of exit 1
  * Correct potential false positive load
  * use stdlib function has and write better error message when node is not found
  * Updates per PR review:
  * Add `use node` directive to stdlib
  * Merge pull request #182 from COLDTURNIP/zsh-hook-fix
  * Eliminate syntax ambiguity in zsh hooking script
  * Merge pull request #179 from punitagrawal/master
  * Fix lintian spelling warning
  * Release v2.7.0
  * travis: try to fix the release
  * Add man doc for the `use_nix` stdlib command
  * compiled man/direnv-stdlib.1
  * Merge pull request #178 from camelpunch/patch-1
  * Hyper urgent change
  * Merge pull request #177 from oppegard/patch-1
  * Fix typo
  * Let bash inherit the PATH in the dump test
  * Merge pull request #174 from direnv/misc-cleanup
  * stdlib: remove unecessary escaping
  * stdlib: typo
  * stdlib: fix shellcheck offenses
  * stdlib: look for direnvrc in XDG_CONFIG_HOME/direnv
  * go fmt
  * Merge pull request #172 from gfxmonk/nix
  * Merge pull request #161 from fernandomora/master
  * Add use_nix() helper to stdlib
  * Update repo urls to point to the new org
  * Release v2.6.1
  * Ditto update to v0.12
  * Merge pull request #169 from gerhard/missing-file-source-env
  * Notify if referenced .envrc is missing
  * source_env handles missing .envrc gracefully
  * Use gitter for chat
  * Similar project: Environment Modules
  * Merge pull request #163 from p0deje/fix-vim-unlet
  * Empty variable as unloading in Vim
  * Added SHELLOPTS to ignored vars
  * README tweaks
  * Merge pull request #160 from neanias/patch-1
  * Corrected spelling mistake in deny command
  * Release v2.6.0
  * Merge pull request #157 from gfxmonk/dump-error
  * Merge pull request #158 from gfxmonk/fish-escaping
  * ignore BASH_FUNC_* variables
  * shell_fish: use single quotes to simplify escaping logic
  * Add new subcommand "prune"
  * Keep path to allowed .envrc
  * Merge pull request #151 from dadooda/patch-1
  * `README.md` fix
  * Merge pull request #149 from toao/master
  * Forward Stdin to allow user input
  * Merge pull request #146 from bbense/tcsh-support
  * Merge pull request #147 from vially/typos
  * Fix some typos
  * Fix typo
  * Added tcsh to docs and minor grammatical correction
  * tcsh support passing all tests but special vars
  * Having test script mostly working stuck on special vars
  * Adapt `direnv exec` to also work on non-env folders.
  * I think I may have a working version of tcsh support. Much more testing is required, but have successfully run a tsch shell using the hook and it appears to work.
  * First pass at tcsh support, hook is wrong
  * Release v2.5.0
  * Unset PYTHONHOME as part of the python layout
  * Don't make virtualenvs relocatable. Fixes #137
  * Merge pull request #136 from zimbatm/python-layout-option
  * Use a different virtualenv per python versions
  * Makes `layout python3` a shortcut for `layout python python3`
  * Allows to specify which version of python to use in layout_python
  * stdlib warning fixes using shellcheck
  * Merge pull request #139 from mashiro/add-global-option
  * Add -g option.
  * Merge pull request #135 from ghickman/patch-1
  * Fix python3 function name
  * Add a python3 layout
  * Regenerated stdlib.go
  * Merge pull request #134 from ghickman/patch-1
  * Remove unnecessary virtualenv options
  * Use Travis to push release builds to github
  * Merge pull request #127 from doloopwhile/symbolic-linked-dir
  * Merge pull request #130 from myfreecomm/master
  * Fix dotenv with explicit .env
  * Release v2.4.0
  * Merge branch 'feature/vim-support'
  * Merge branch 'feature/detect-editor'
  * Try to detect an editor in the PATH if EDITOR is not set.
  * Preliminary support for vim
  * README.md wording
  * Merge branch 'ditto'
  * New site: put the doc inside the project so it stays in sync
  * Resolve symbolic links to load envrc in parent dirs
  * Relax the Shell interface, Escape() is only used internally.
  * layout ruby: share the gem home starting from rubygems v2.2.0
  * Merge pull request #117 from CMCDragonkai/master
  * Support for Cygwin 1. Ensure paths are always forward slashes. 2. Ensure Windows releases have the .exe extension
  * Allow arbitrary number of args in `log_status`
  * stdlib.sh -> s/\t/  /g
  * Adds selected bash executable in `direnv status`
  * Merge branch 'md2man'
  * Fixes lintian warning
  * Doc updates
  * replace ronn by md2man
  * Fixes `make install` to not create a ./bin directory
  * Fixes ruby deprecation warning
  * Log output consistency
  * Allow to disable logging by setting an empty DIRENV_LOG_FORMAT
  * Bump command timeout to 5 seconds
  * Merge pull request #115 from zimbatm/issue-114
  * Fix issue #114 - work for blank envs
  * Add TestEnvDiffEmptyValue
  * Add empty-var and empty-var-unset integration test
  * Merge pull request #113 from punitagrawal/manpage-fix
  * Merge pull request #112 from JaviMerino/master
  * Fix error in manpage
  * typo: informations -> information
  * LICENSE update
  * Move the stdlib into a .sh file to benefit from syntax coloring
  * Refactor layout_perl a bit. Supports nested dirs now.
  * Adds man doc for layout_perl and reorder layouts alphabetically
  * Merge pull request #110 from halkeye/layout_perl
  * layout_perl support (local::lib)
  * Run the EDITOR inside /bin/sh. Fixes #108
  * Merge pull request #107 from HeroicEric/master
  * Fix typo
  * Merge branch 'rel-path-fix'
  * If two paths don't have a common ancestors, don't make them relative.
  * Merge pull request #103 from lmarlow/relative_typo
  * Fix typo of "relative"
  * Merge pull request #102 from take/patch-1
  * Update README.md
  * Release v2.3.0
  * Merge branch 'direnv-exec'
  * Hides warnings of the `virtualenv --relocatable` command
  * doc
  * Overload `direnv exec` to allow a command as it's first argument.
  * Introducing the `direnv exec DIR COMMAND ...` command executor.
  * export diff from the old env, not the current env
  * Merge pull request #99 from gfxmonk/color-output
  * Use $DIRENV_LOG_FORMAT to control log formatting, rather than hard-coding colors
  * Use terminal colours for direnv output
  * Tidy up log output
  * Hides the DIRENV_ variables in the output diff. Fixes #94
  * Makes sure the path used in the allow hash is absolute. See #95
  * Merge pull request #96 from scottjacobsen/master
  * stdlib: `layout python` tries harder to make projects relocatable
  * stdlib: `layout go` now also adds ./bin in the PATH
  * Set the executable bit on direnv.
  * Fixes parse error on the bash hook when evaluated on a single line.
  * Release v2.2.1
  * Refactored the whole export and diff mechanism. Fixes #92 regression.
  * Thanks @gfxmonk for your contributions, it's well appreciated
  * Release v2.2.0
  * man pages recompile
  * Little tool to debug the content of DIRENV_BACKUP
  * Merge branch 'only-diff'
  * Adds documentation for direnv_load in the direnv-stdlib.1 man page
  * Only backup the diff of environments. Fixes #82
  * Fixes issue where env is not restored properly when it couldn't load
  * Renames `direnv apply-dump` to `direnv apply_dump` to follow the convention
  * Merge pull request #90 from gfxmonk/direnv_apply_dump
  * rename direnv_apply_dump -> direnv_load
  * direnv_apply_dump: use $direnv
  * direnv_apply_dump: run the dump command given in <argv>, rather than taking a file containing dump output
  * Add direnv_apply_dump function to stdlib
  * Renames DIRENV_PATH to direnv in the stdlib. It's not exported.
  * Merge pull request #91 from AlphaHydrae/go-install-instructions
  * Added note that the Go language is required for installation (for users that don't use Homebrew)
  * Merge pull request #88 from gfxmonk/include-path-in-auth
  * move test/allow .gitignore to root .gitignore
  * rc.go: include path in fileHash
  * travis-ci: test agains go 1.2 and not against gh-pages
  * Refactored rc, moving the load function into it
  * Add command aliases. `direnv --help` is an alias to `direnv help`
  * Removing a double direnv: prefix in error message
  * all error output exit paths should be prefixed with "direnv:". Fixes #87
  * `direnv edit` should only allow the .envrc if the mtime has changed. Fixes #86
  * manpages re-compilation
  * Stop auto-allowing the test cases
  * Makes the `direnv dotenv` internal command usable with the other shells.
  * Merge pull request #84 from gfxmonk/fix-apostrophes
  * it's -> its
  * Ignore the COMP_WORDBREAKS variable. Fixes #81
  * Adds test for the special DIRENV_CONFIG and DIRENV_BASH configuration vars
  * Avoids potential unwanted globbing in the stdlib
  * Merge pull request #80 from ardecvz/master
  * Quick fix to keep special DIRENV_* variables when direnv activate
  * Merge branch 'stdlib-doc'
  * Better error message when direnv fails loading the .envrc
  * Rewrite the man page for direnv-stdlib(1) and the inline doc. Fixes #76
  * Support more of the dotenv syntax format
  * Fixes typo in the man page
  * go fmt -l -w -s .
  * Release v2.1.0 - fish shell edition
  * Merge pull request #75 from zimbatm/avoid-double-inclusion
  * Makes the zsh hook resistant to double-hooking.
  * Makes the bash hook resistant to double-hooking.
  * More precise direnv allow error message. Fixes #72
  * README.md synched with site's index.md
  * Stop recommending using $0 to detect the shell. Fixes #64.
  * Missing file
  * Merge branch 'fish-support'
  * Added CHANGELOG.md entry for the fish shell
  * Thanks @alanbbr !
  * Removes the fish/cd.fish file for now. The shell hook is probably better.
  * Adds install instructions for the fish shell
  * Threat fish's PATH export specially
  * Ignore environment variables that start with __fish
  * Fixes `direnv hook fish`
  * Try to add a `direnv hook fish` command
  * initial support for fish
  * Added a CHANGELOG.md file.
  * version bump v2.0.1
  * Fixes shell detection in case $0 doesn't contain a path
  * Link build status to the master branch only
  * Add a LICENSE file to the repo
  * travis-ci: test with go 1.0 and 1.1
  * Release v2.0.0
  * Merge pull request #60 from zimbatm/stdlib-cleanup
  * Reworking the doc
  * Didn't find a way to fix that last bug :/ Marking as known issue for now.
  * New failing testcase: the .envrc execution context has the symlink resolved
  * Change the `direnv edit` logic a bit.
  * Make the `direnv stdlib` command public
  * More stdlib doc
  * Proper file touching
  * stdlib: layout go
  * Remove the set_use_prefix() command in the stdlib
  * Stdlib documentation
  * First pass at the prefix-loading idea as described in #40
  * Change `rbenv` to `use rbenv` in the stdlib
  * `make test` should build direnv first
  * Removing old website generation
  * Adds a new `direnv reload` command for convenience
  * Fixes the tests
  * Remove unused code
  * Display relative path to the .envrc
  * Fixes printing of errors
  * Rename direnv.go to main.go
  * Disable timeout notification on `direnv edit`
  * Merge pull request #58 from carlgwilliam/go1
  * invoke bash with --noprofile and --norc
  * Removes unused package that was breaking the build
  * Merge pull request #51 from pwaller/50-freeze-fix
  * Merge pull request #53 from pwaller/timeout
  * Much more elegant solution for freezing: use exec.Output()
  * Add general warning to all commands if they take longer than 2s
  * Fix freezing issue #50
  * Merge pull request #54 from pwaller/49-better-errors
  * Address comments from #54
  * Improvements to error messages to give more context
  * Fixes #52 parse error in the stdlib
  * stdlib's `rbenv` is now only used for setup
  * direnv export cosmetic
  * `make site` to fetch the gh-pages on a sub-folder
  * Initial support for rbenv in the stdlib
  * Make the stdlib rvm command more robust
  * Thanks @pwaller for all your feedbacks
  * Display command arguments in the help
  * Move the version information into the direnv executable.
  * Release scripts
  * Add the version to the command-line help
  * Fixes the bash hook
  * First pass at a usable `direnv help`
  * Move the rc load function to where it makes sense
  * Simplify command dispatch
  * Return the stdlib into the executable. Closes #45
  * Improve env diff output
  * Output refresh
  * Add support for loading .env files in the stdlib.
  * Add the `direnv edit` command. Closes #47.
  * Error of 1
  * Split the commands to one per file
  * Fixes the tests
  * direnv eval/export loop finally fixed
  * Adds DIRENV_BASH to configure the path to bash
  * Consistent quoting in the stdlib
  * Remove unused Config.Error field
  * Remove unused `direnv switch` command
  * Style, thx @pwaller
  * Fixes zsh's hook
  * Removed unused `direnv private load` command
  * Formatting
  * Shell-specific exports
  * Formatting
  * Fixes the tests
  * Simplify shell detection and hooks
  * Rename Context into Config
  * Ignore `go test` results
  * Removes the old libexec/direnv-export files
  * snapshot
  * Change the sourcing logic a little bit
  * Fixes wrong folder use
  * Finally the simple commands are working again.
  * Still WIP but approaching a workable state
  * WIP
  * Run the shell to go conversion when building direnv
  * WIP
  * Use absolute package paths
  * WIP
  * Remove the project's .envrc
  * Shell escape fixes
  * Simplified the IgnoredKey algorithm a bit. Thx @pwaller again.
  * Get rid of our customer bytes buffer. Thanks @pwaller
  * simplified IGNORED_KEYS init, thanks @pwaller
  * Rework the go source file structure
  * Use filepath.EvalSymlinks instead of coding our own
  * WIP
  * WIP
  * Re-implemented direnv-diff and direnv-dump in Go
  * direnv-hook support for non-standard paths
  * Fix the test suite to execute properly
  * Allow undefined variables in the .envrc scripts
  * Make the tests pass for 'scenarios/space dir'
  * PROMPT_COMMAND optimisation
  * Always use source_env to source .envrc files
  * Use set -u
  * Move direnv_find_rc to stdlib
  * Detect changes to .envrc through symlinks on Darwin
  * Merge pull request #32 from pwaller/patch-1
  * Detect changes to .envrc through symlinks
  * Fix spaces in path
  * source_up: Allow custom file as argument
  * New stdlib command: source_up
  * Re-use the stdlib in the export script
  * Handle more corner-cases in expand_path
  * Fixes race in the test-suite as shown in #30.
  * Also show relative path for source_env
  * Merge pull request #29 from jayferd/master
  * Allow for overriding $(DESTDIR), for those of us who prefer $HOME/.local to /usr/local.
  * Show ~paths to make the display shorter
  * If ~/.direnvrc exists, it's loaded in all your envs
  * New util: `path_add VAR ./some/path`
  * direnv-exec: use $DIRENV_LIBEXEC
  * Rework the README.md and link it to the man page
  * `make gh-pages` rework for uncommited changes
  * add `layout ruby` to the .envrc for ronn
  * Doc fix, dangling reference to shell-env
  * Readme formatting
  * Merge pull request #28 from bmc/master
  * Adding a travi-ci badge to the readme
  * Added another missing semi-colon in the ZSH direnv-hook
  * Merge branch 'master' of https://github.com/zimbatm/direnv
  * Fixed eval parsing error in direnv-hook for zsh.
  * trying out travis-ci
  * Fixed eval parsing error in direnv-hook for zsh.
  * whitespace path issue fixed
  * Allow multiple pre_cmd in zsh as in #24
  * Prefix DIRENV_DIR with - to avoid zsh named directories
  * avoid unecessary forks
  * Resolve symlinks before looking up the .envrc
  * Better docs
  * `layout ruby` bugfix
  * Missing generated man page
  * Install manpages in share/
  * direnv-diff can also load the backup from the env
  * Fix env reloading
  * More tests, shows broken behavior on reload
  * Rework direnv-export with better messages and stuff
  * don't backup unused variables
  * Remove the direnv-reload alias
  * Better stdlib doc
  * `make gh-pages`
  * Some doc refinements
  * +1 contributor: Laurie Young
  * +1 contributor: Martin Aumüller
  * Added manpages and `make install`. Finally !
  * and direnv-switch vanishes into /dev/null
  * +bashism in direnv-stdlib
  * Avoid unecessary indirection in direnv-export
  * fix
  * Test updates
  * Makefile added
  * Add bashism, get "inspiration" from the bats project
  * Rename DIRENV_LIBEXEC_DIR -> DIRENV_LIBEXEC
  * source_env: when targeting a directory, it loads .envrc
  * Introducing the `use` command
  * Faster direnv by caching the libexec dir
  * Fix of the fix
  * Only unset direnv-reload if it exists
  * Rework the dump/restore logic. Fixes #22
  * bash for everyone
  * Bug fix: whitespace in path
  * Unrelevant scenario removed
  * Some bashism introduced
  * Finally, adding unit tests to the project
  * stdlib absolute(): don't prefix absolute paths
  * Hook install simplification
  * stdlib: renamed source() to source_env()
  * Merge pull request #21 from aumuell/master
  * compatibility with Linux stat
  * Fix for the new rvm 1.8.3
  * New feature: .envrc auto-reload on change
  * Merge pull request #20 from josh/dont-export-prompt
  * Don't export PROMPT_COMMAND
  * Add inheritable .envrc trough overridden source()
  * More explicit REAMDE
  * ruby layout: prefix the ruby engine before the ruby version
  * Fix for recent versions of rvm
  * Moving executables to libexec/ like git
  * Fix multi-symlink resolution
  * rvm strictness
  * layout ruby: Woops, forgot to also prefix the gem path
  * layout ruby: separate gems by ruby version
  * Be opiniated. A good system should have Bash
  * Don't let Rubinius litter your projects with .rbc files
  * Merge pull request #12 from josh/relative-symlinks
  * Fix `abs_dirname` to work with relative symlinks
  * zsh weirdness documented
  * layout ruby GEM_HOME=$PWD/.direnv/gems
  * Merge pull request #10 from wildfalcon/patch-1
  * Small readability tweak
  * Few spelling and readability tweaks
  * Updated direnv install instruction
  * PROMPT_COMMAND: escaping fix
  * PROMPT_COMMAND: inherit existing PROMPT_COMMAND
  * Add welcoming .envrc to project root
  * Handle `cd //`. Fixes #9
  * Adds `direnv-reload` alias when an .envrc is loaded
  * Fix `rvm` in stdlib for latest rvm versions
  * stdlib: abspath function
  * Fixes path with spaces
  * direnv-hook: avoid detection on non-/proc systems (OSX)
  * direnv-hook utility function
  * Fix direnv dispatcher
  * Restore ruby sh wrappers
  * woops, removes debug line in `direnv`
  * Don't use `realpath -f`, it's a GNU-ism
  * sourcable scenario
  * direnv-stdlib - all utility functions go here
  * rvm: check for install
  * has() which -> type
  * adds ruby layout scenario
  * Now supports rvm
  * add vendor bin in ruby layout
  * export: support for whitespaces in path
  * export: clearer user messages
  * Prefix .envrc finder just in case
  * Use the direnv dispatcher everywhere
  * git-like re-implementation
  * Use SHELLENV_RUBY if there to set the ruby executable path
  * Set $0 for ruby-1.9.2
  * Fixes 1.8 incompatibility. Props to judofyr!
  * Contribute notice
  * README: adds licence section
  * cool hack: pre-load shell-env in sh to rename RUBYOPT
  * Remove dead parse_env test
  * More robust ENV parsing
  * README update
  * Deal with unknown directory
  * Using absolute /usr/bin/env path
  * README example
  * README formatting
  * README.md updates
  * Added a .gemspec
  * Fix README.md rvm usage
  * Updated shell-env
  * shell-env cleanup
  * Ported shell-env to ruby, made it work
  * First credible shell-env impl. Still buggy
  * new project: shell-env

2.37.1 / 2025-07-20
==================

  * fix: regression in displaying export errors (#1469)

2.37.0 / 2025-07-02
==================

  * docs: add github-actions page
  * docs: document sub-commands
  * docs: fix link to guix manual (#1421)
  * docs: re-generate manpages
  * feat(direnv export gha): strengthen export format
  * feat: add windows arm64 target (#1444)
  * fix(powershell): "export pwsh" to resolve PowerShell special character issues (#1448)
  * fix(python): do not include patch level in virtual environment names (#1423)
  * fix(use_nix): always restore special variables (#1424)
  * fix: accept true as valid DIRENV_DEBUG value (#1365)
  * fix: add trailing newline to error messages (#1426)
  * fix: delete duplicate ansi escape code

v2.36.0 / 2025-04-11
==================

  * direnv now requires go 1.24 (#1384)
  * doc: Correct duplicate usage of 'with' in the direnv(1) (#1394)
  * doc: note direnv version for log_{format,filter} (#1369)
  * feat: Add `use_flox` to stdlib.sh (#1372)
  * feat: logging filter (#1336)
  * fix use_nix: unset TMPDIR variables (#1409)
  * fix: A more universal fix for the python 3.14 `find_spec` deprecation warning (#1382)
  * fix: Don't give an error when the current directory doesn't exist (#1395)
  * fix: add support to fully reproducible guix shells (#1392)
  * fix: assert minimum powershell version (#1385)
  * fix: escape newlines in generated vimscript (#1347)
  * fix: fix empty array error in install.sh (#1406)
  * fix: optionally authenticate against github api during install (#1337)
  * fix: use_guix: Enable the watching of Guix related files. (#1353)

2.35.0 / 2024-10-07
==================

  * doc: Add version requirement for load_dotenv option (#1326)
  * doc: change Guix link to its package search. (#1268)
  * doc: fix broken link (#1327)
  * doc: update elvish docs (#1305)
  * feat: add opam support (#1298)
  * fix: add NuShell into list of supported shells (#1260)
  * fix: close tmp file (#1272)
  * fix: direnv edit: use `editor` when EDITOR not found, closes #1246 (#1247)
  * fix: release script
  * fix: stdlib: enable flakes when use flake is used (#1299)
  * fix: stdlib: export GOBIN for layout_go (#1286)
  * fix: stdlib: update layout_python to resolve deprecation warning (#1176)
  * fix: using PWD in .env files (#1052)
  * test: Fix Murex python-layout test (#1293)

2.34.0 / 2024-03-01
==================

  * doc: README.md, man pages: it's typos (#1230)
  * doc: add shell setup instructions for oh-my-zsh (#1070)
  * doc: added fetchurl manpage link to README.md
  * doc: document XDG_DATA_HOME (#1185)
  * doc: update installation.md for Gentoo (#1206)
  * feat: add Murex support (#1242)
  * feat: added systemd shell for export (#1126)
  * feat: allow to disable warn timeouts (#1209)
  * feat: hide env diff (#1223, #1234)
  * feat: made 'direnv export' non private (#1229)
  * fix: `use_julia` should not set LD_LIBRARY_PATH (#900)
  * fix: add missing deps for release in go.mod
  * fix: avoid use of regex in bash hook output (#1043)
  * fix: direnv.toml.1.md: add examples for $HOME expansion
  * fix: stdlib: use_flake: don't keep old generations around (#1089)
  * fix: stdlib: use_node: strip leading v from version (#1071)
  * fix: support Bash 5.1 array PROMPT_COMMAND (#1208)
  * fix: update stdlib.sh to avoid deprecation warning (#1221)
  * fix: update zsh syntax in internal/cmd/shell_zsh.go (#1075)

2.33.0 / 2023-11-29
==================

  * doc: add a Nushell section to `hook.md` by @amtoine in https://github.com/direnv/direnv/pull/1175
  * doc: fix broken links in installation.md by @just1602 in https://github.com/direnv/direnv/pull/1110
  * doc: show how to run tests by @bukzor-sentryio in https://github.com/direnv/direnv/pull/1137
  * doc: update NixOS installation instructions by @Gerg-L in https://github.com/direnv/direnv/pull/1172
  * doc: update direnv.toml.1.md by @Ativerc in https://github.com/direnv/direnv/pull/1099
  * feat: `direnv status --json` by @shivaraj-bh in https://github.com/direnv/direnv/pull/1142
  * feat: add PowerShell Support by @bamsammich in https://github.com/direnv/direnv/pull/1171
  * feat: add mergify configuration by @Mic92 in https://github.com/direnv/direnv/pull/1147
  * feat: add support for armv7l platform in install.sh by @ardje in https://github.com/direnv/direnv/pull/1162
  * feat: add watch print command by @Mic92 in https://github.com/direnv/direnv/pull/1198
  * feat: alias `direnv disallow` to deny by @will in https://github.com/direnv/direnv/pull/1182
  * feat: stdlib: create CACHEDIR.TAG inside .direnv by @Mic92 in https://github.com/direnv/direnv/pull/1148
  * fix: `allowPath` for `LoadedRC` by @shivaraj-bh in https://github.com/direnv/direnv/pull/1157
  * fix: don't prompt to allow if user explicitly denied by @Gabriella439 in https://github.com/direnv/direnv/pull/1158
  * fix: man/direnv-stdlib: fix obsolete opam-env example by @mzacho in https://github.com/direnv/direnv/pull/1170
  * fix: print correct path in source_env log message by @wentasah in https://github.com/direnv/direnv/pull/1144
  * fix: quote tcsh $PATH, to avoid failure on whitespace by @bukzor-sentryio in https://github.com/direnv/direnv/pull/1139
  * fix: remove redundant nil check in `CommandsDispatch` by @Juneezee in https://github.com/direnv/direnv/pull/1166
  * fix: update nixpkgs and shellcheck by @Mic92 in https://github.com/direnv/direnv/pull/1146

2.32.3 / 2023-05-20
==================

  * fix: incorrect escape sequences during Loads under git-bash (Windows) (#1085)
  * fix: skip some tests for IBM Z mainframe's z/OS operating system (#1094)
  * fix: stdlib: use_guix: Switch to guix shell. (#1045)
  * fix: stat the already open rc file rather than another path based one on it (#1044)
  * fix: remove deprecated io/ioutil uses (#1042)
  * fix: spelling fixes (#1041)
  * fix: appease Go 1.19 gofmt (#1040)
  * fix: pass BASH_PATH to make, matches the nixpkgs derivation (#1006)
  * fix: stdlib/layout_python: exclude patchlevel from $python_version (#1033)
  * doc: add Windows installation with winget (#1096)
  * doc: link 12factor webpage for more clarity (#1095)
  * website: add Plausible analytics

2.32.2 / 2022-11-24
==================

  * doc: Add stdlib's layout_pyenv to docs (#969)
  * doc: Fix broken link (#991)
  * doc: Minor typo fix (#1013)
  * doc: `$XDG_CONFIG_HOME/direnv/direnv.toml` => add (typically ~/.config/direnv/direnv.toml) (#985)
  * doc: add quickenv to Related projects (#970)
  * feat: Update layout anaconda to accept a path to a yml file (#962)
  * feat: install.sh: can specify direnv version (#1012)
  * fix: elvish: replace deprecated `except` with `catch` (#987)
  * fix: installer.sh: make direnv executable for all
  * fix: path escaping (#975)
  * fix: stdlib: only use ANSI escape on TTY (#958)
  * fix: test: remove mentions of DIRENV_MTIME (#1009)
  * fix: test: use lowercase -d flag for base64 decoding of DIRENV_DIFF (#996)
  * update: build(deps): bump github.com/BurntSushi/toml from 1.1.0 to 1.2.0 (#974)

2.32.1 / 2022-06-21
==================

  * feat: Support custom VIRTUAL_ENV for layout_python (#876)
  * fix: vendor go-dotenv (#955)

2.32.0 / 2022-06-13
==================

  * feat: Add gha shell for GitHub Actions (#910)
  * feat: Enable ppc64le builds (#947)
  * feat: allow conda environment names to be detected from environment.yml (#909)
  * feat: source_up_if_exists: A strict_env compatible version of source_up (#921)
  * feat: Expand ~/ in whitelist paths (#931)
  * feat: Add "block" and "revoke" as aliases of the "deny" command (#935)
  * feat: Add "permit" and "grant" as aliases of the "allow" command (#935)
  * fix: update go-dotenv
  * fix: fetchurl: store files as hex (#930)
  * fix: fetchurl: only store 200 responses (#944)
  * fix: Ensure status log messages are printed with normal color (#884)
  * fix: Clarify handling of .env files (#941)
  * fix: Update shell_elvish.go (#896)
  * fix: stdlib.sh: remove dependency on tput (#932)
  * fix: Use setenv in vim to allow non alphanumeric vars (#901)
  * fix: install.sh: add information about bin_path (#920)
  * fix: Treat `mingw*` as windows (direnv/direnv#918) (#919)
  * fix: man: clarify paths (#929)
  * fix: installation.md: Fix Fedora package link (#915)
  * Merge pull request #874 from direnv/refactor
  * chore: rc: stop using --noprofile --norc
  * chore: rc: prepare stdin earlier
  * chore: rc: install interrupt handler earlier
  * chore: stdlib: factor out stdlib preparation
  * chore: fix CI
  * chore: source_env: show full path (#870)
  * chore: Sort shells in DetectShell
  * chore: Enable codeql action (#938)
  * chore: Set permissions for GitHub actions (#937)
  * go: bump golang.org/x/sys for linux/loong64 support (#946)
  * build(deps): bump actions/checkout from 2.4.0 to 3.0.0 (#922)
  * build(deps): bump actions/checkout from 3.0.0 to 3.0.1 (#933)
  * build(deps): bump actions/checkout from 3.0.1 to 3.0.2 (#936)
  * build(deps): bump actions/setup-go from 2.1.5 to 3.0.0 (#923)
  * build(deps): bump actions/setup-go from 3.0.0 to 3.1.0 (#943)
  * build(deps): bump actions/setup-go from 3.1.0 to 3.2.0 (#950)
  * build(deps): bump cachix/install-nix-action from 16 to 17 (#925)
  * build(deps): bump github.com/BurntSushi/toml from 0.4.1 to 1.1.0 (#924)

2.31.0 / 2022-03-26
==================

  * Don't load .env files by default (#911)
  * doc: `~/.config/direnv/direnvrc` is the default
  * doc: fix the broken link to arch linux (#892)
  * Re-add accidentally deleted comment line (#881)
  * fix version test

2.30.3 / 2022-01-05
==================

  * Allow skipping `.env` autoload (#878)
  * stdlib: add `env_vars_required` (#872) (#872)
  * Test whether version.txt contains semantic version (#871)

2.30.2 / 2021-12-28
==================

  * FIX: version: trim surrounding spaces (#869)
  * build(deps): bump actions/setup-go from 2.1.4 to 2.1.5 (#866)
  * move most code under internal/cmd (#865)

2.30.1 / 2021-12-24
==================

  * FIX: ignore .envrc and .env if they are not files (#864)

2.30.0 / 2021-12-23
==================

  * Add automatic `.env` load (#845)
  * Resolve symlinks during `direnv deny` (#851)
  * update installer for Apple Silicon (#849)
  * stdlib: use_flake handle no layout dir (#861)
  * embed stdlib.sh (#782)
  * embed version.txt
  * go mod update
  * make dist: remove references to Go

2.29.0 / 2021-11-28
==================

  * stdlib: add use_flake function (#847)
  * docs(direnv.toml) Add config.toml clarification (#831)
  * docs(install): fix macos links (#841)
  * Corrects stdlib link in Ruby docs (#837)
  * stdlib.sh: Fix removal of temp file (#830)
  * install.sh: add aarch64 support
  * Updated conditional for zsh hook to be more forgiving (#808)
  * Add -r flag for matching Git branches with a regexp (#800)
  * Add docs about pipenv (#797)
  * Enable syntax highlights to the quick demo code (#752)
  * Fixed extra quotes for lower alpha characters (#783)
  * Remove noisy warning about PS1 again (#781)

2.28.0 / 2021-03-12
==================

  * Merge pull request #779 from wingrunr21/go_1_16
  * Build for darwin/arm64. Resolves #738
  * Update to go 1.16
  * test: Fix errors for elvish test (#767)
  * tcsh: fix variable escaping (#778)
  * Change DESTDIR to PREFIX in development.md (#774)
  * go: use the /v2 prefix (#765)
  * Relax README's recommendation for nix-direnv (#763)
  * man/direnv.1.md: add FILES section (fix #758) (#759)
  * Add/update fish tests (#754)
  * build(deps): bump golang.org/x/mod from 0.4.0 to 0.4.1 (#749)
  * Fix typo "avaible" in install.sh (#750)
  * docs: improve the use_node documentation

2.27.0 / 2021-01-01
==================

  * fixed fish shell hook to work with eval (#743)
  * dist: remove darwin/386
  * nix: update to nixpkgs@nixos-20.09
  * packaging: stop vendoring the Go code (#739)
  * packaging: change packaging. DESTDIR -> PREFIX, fish hook (#741)

2.26.0 / 2020-12-27
==================

  * updated fish hook support issue (#732)
  * ci: add basic windows CI (#737)
  * test: fix shellcheck usage in ./test/stdlib.bash
  * test: fix use_julia test for NixOS
  * remove dead code: rootDir
  * fix: create temp dir in current working dir for one test (#735)
  * Add `dotenv_if_exists` (#734)
  * stdlib: add watch_dir command (#697)

2.25.2 / 2020-12-12
==================

There was a generation issue in 2.25.1. This release only bumps the version
to do another release.

2.25.1 / 2020-12-11
==================

  * stdlib.go: re-generate (fixes #707)
  * README: remove old Azure badge
  * build(deps): bump golang.org/x/mod from 0.3.0 to 0.4.0 (#730)

2.25.0 / 2020-12-03
==================

  * dist: add linux/arm64 and linux/ppc64
  * Added use_nodenv to stdlib (#727)
  * Fix proposal for  #707, broken direnv compatibility under Windows (#723)
  * fix: layout anaconda <env_name_or_prefix> (#717)
  * Add on_git_branch command to detect whether a specific git branch is checked out (#702)

2.24.0 / 2020-11-15
==================

  * direnv_load: avoid leaking DIRENV_DUMP_FILE_PATH (#715)
  * Add strict_env and unstrict_env (#572)
  * stdlib: add `use_vim` to source local vimrc (#497)
  * stdlib: add source_env_if_exists (#714)
  * Wording (#713)
  * build(deps): bump actions/checkout from v2.3.3 to v2.3.4 (#709)
  * build(deps): bump cachix/install-nix-action from v11 to v12 (#710)
  * Fix XDG_CACHE_HOME path (#711)
  * rc: make file existence check more robust (#706)

2.23.1 / 2020-10-22
==================

  * fix: handle links on Mac when using `allow` (#696)
  * fix: use restored env in exec (#695)
  * stdlib: add basename and dirname from realpath (#693)
  * stdlib.sh: remove tabs
  * dist: compile all the binaries statically

2.23.0 / 2020-10-10
==================

  * stdlib: add source_url function (#562)
  * direnv: add fetchurl command (#686)
  * shell: Update Elvish hook to replace deprecated `explode` (#685)

2.22.1 / 2020-10-06
==================

  * Look for stdlib in DIRENV_CONFIG (#679)
  * stdlib: use Bash 3.0-compatible array expansion (#676)
  * Clarify path to direnv.toml (#678)
  * stdlib/use_julia: fix a bug in parameter substitution for empty or (#667)
  * man: update the layout_go documentation
  * stdlib:  adds GOPATH/bin to PATH (#670)

2.22.0 / 2020-09-01
==================

  * stdlib: use_julia <version> (#666)
  * stdlib: semver_search (#665)
  * direnv-stdlib.1: add layout julia (#661)
  * README: spelling correction (#660)
  * README.md: add shadowenv to similar projects (#659)
  * docs: remove Snap from the installations
  * OSX -> macOS (#655)
  * Update shell_fish.go to use \X for UTF encoding (#584)
  * Change XDG_CONFIG_DIR to XDG_CONFIG_HOME (#641)
  * Streamline core algorithm of export and exec (#636)
  * test: add failure test-case (#637)

2.21.3 / 2020-05-08
==================

  * Replace `direnv expand_path` with pure bash (#631)
  * Fix #594 - write error to fd 3 on Windows (#634)
  * Make direnv hook output work on Windows (#632)
  * Update hook.md to remove ">" typo in Fish instructions (#624)
  * stdlib: `layout go` adds layout dir to GOPATH (#622)
  * direnv-stdlib.1: add layout php (#619)
  * stdlib: add PATH_rm <pattern> [<pattern> ...] (#615)
  * Error handling tuples (#610)
  * Merge pull request #607 from punitagrawal/master
  * test: elvish: Fix evaluation function
  * stdlib.sh: Re-write grep pattern to avoid shell escape
  * man: Escape '.' at the beginning of line to remove manpage warning
  * stdlib: fix direnv_config_dir usage (#601)
  * direnv version: improve error message (#599)
  * README: fix NixOS link in installation.md (#589)
  * stdlib: add direnv_apply_dump <file> (#587)
  * Simplify direnv_load and make it work even when the command crashes. (#568)
  * docs: fix fish installation instruction
  * test: test for utf-8 compatibility
  * config: add [global] section
  * config: add strict_env option
  * config: fix warn_timeout parsing (#582)
  * Github action for releases
  * config: fix the configuration file selection
  * stdlib: fix shellcheck warnings

2.21.2 / 2020-01-28
==================

Making things stable again.

  * stdlib: revert the `set -euo pipefail` change. It was causing too many
    issues for users.
  * direnv allow: fix the allow migration by also creating the parent target
    directory.

2.21.1 / 2020-01-26
==================

Fix release

  * stdlib: fix unused variable in `use node`
  * stdlib: fix unused variable in `source_up`
  * test: add stdlib test skeleton
  * add dist release utility

2.21.0 / 2020-01-25
==================

This is a massive release!

## Highlights

You can now hit Ctrl-C during a long reload in bash and zsh and it will not
loop anymore.

Commands that use `direnv_load` won't fail when there is an output to stdout
anymore (eg: `use_nix`).

Direnv now also loads files from `.config/direnv/lib/*.sh`. This is intended
to be used by third-party tools to augment direnv with their own stdlib
functions.

The `.envrc` is now loaded with `set -euo pipefail`. This will more likely
expose issues with existing `.envrc` files.

## docs

  * Update README.md (#536)
  * Add link to asdf-direnv. (#535)
  * docs: fix invalid link (#533)
  * adds experimental curl based installer (#539)

## commands

  * change where the allow files are being stored
  * direnv status: also show the config
  * direnv exec: improve the error message
  * warn if PS1 is being exported
  * handle SIGINT during export in bash
  * export: display the full RC path instead of a relative one
  * direnv exec: the DIR argument is always required (#493)

## build

  * ci: use GitHub Actions instead of Azure Pipelines
  * staticcheck (#543)
  * use go modules
  * make: handle when /dev/stderr doesn't exist (#491)
  * site: use jekyll to render the website
  * Pin nixpkgs to current NixOS 19.09 channel (#526)

## shells

  * fix elvish hook
  * Use `fish_preexec` hook instead of `fish_prompt` (#512)
  * Use `fish_postexec` to make sure direnv hook executed 'after' the directory has changed when using `cd`.
  * improve zsh hook (#514)

## config.toml

  * rename the configuration from config.toml to direnv.toml (#498)
  * add warn_timeout option. DIRENV_WARN_TIMEOUT is now deprecated.

## stdlib

  * `direnv_load` can now handle stdout outputs
  * stdlib: add layout_julia
  * Handle failing pipenv on empty file and avoid an extra pipenv execution (#510)
  * fix `source_env` behaviour when the file doesn't exists (#487)
  * `watch_file` can now watch multiple files in a single invocation (#524)
  * `layout_python`: prefer venv over virtualenv. Do not export VIRTUAL_ENV if $python_version is unavailable or a virtual environment does not exist/can't be created
  * Adds layout_pyenv (#505)
  * Fix `source_up` docs to explain that search starts in parent directory (#518)
  * fix `path_add` to not leak local variables
  * `layout_pyenv`: support multiple python versions (#525)
  * Add a `direnv_version <version_at_least>` command to check the direnv
    version.
  * `dotenv`: handle undefined variables
  * source files from `.config/direnv/lib/*.sh`
  * stdlib: set `-euo pipefail`

2.20.1 / 2019-03-31
==================

  * ci: try to fix releases

2.20.0 / 2019-03-31
==================

  * CHANGE: Use source instead of eval on fish hook
  * DOC: Remove duplicate build badge (#465)
  * DOC: add note about auth (#463)
  * DOC: change nixos link (#460)
  * FIX: Corrects reverse patching when using exec cmd. (#466)
  * FIX: Perform stricter search for existing Anaconda environments (#462)
  * FIX: arity mismatch for elvish (#482)
  * FIX: avoid reloading on each prompt after error (#468)
  * FIX: improve bash hook handling of empty PROMPT_COMMAND (#473)
  * FIX: improved the tests for bash, zsh, fish and tcsh (#469)
  * MISC: migrated from Travis CI to Azure Pipelines (#484)

2.19.2 / 2019-02-09
==================

  * FIX: file_times: check Stat and Lstat (#457)

2.19.1 / 2019-01-31
==================

  * FIX: watched files now handle symlinks properly. Thanks @grahamc! #452

2.19.0 / 2019-01-11
==================

  * NEW: add support for .env variable expansion. Thanks to @hakamadare!

2.18.2 / 2018-11-23
==================

  * make: generate direnv.exe on windows (#417)

2.18.1 / 2018-11-22
==================

  * travis: fix the release process

2.18.0 / 2018-11-22
==================

A lot of changes!

  * stdlib: add DIRENV_IN_ENVRC (#414)
  * Fix typo in readme. (#412)
  * Merge pull request #407 from zimbatm/direnv-dump-shell
  * direnv dump can now dump to arbitrary shells
  * add a new "gzenv" shell
  * move gzenv into new package
  * shell: introduce a dump capability
  * cleanup the shells
  * Add alias '--version' to version command. Closes #377. (#404)
  * Correctes spelling of openSUSE (#403)
  * testing: elvish 0.12 is released now (#402)
  * Merge pull request #397 from zimbatm/readme-packaging-status
  * README: add packaging status badge
  * README: remove equinox installation
  * direnv show_dump: new command to debug encoded env (#395)
  * Document possibility to unset vars (#392)
  * stdlib: fix typo
  * go dep: update Gopkg.lock
  * make: don't make shfmt a dependency
  * Avoid to add unnecessary trailing semicolon character (#384)
  * add asdf to the list of known projects
  * stdlib.go: re-generate
  * Add PHP layout to stdlib (#346)
  * make: fix formatting
  * README: add build status badge
  * Overhaul the build system (#375)
  * stdlib, layout_pipenv: handle `$PIPENV_PIPFILE` (#371)
  * README: improve the source build instructions

2.17.0 / 2018-06-17
==================

  * CHANGE: hook expands the direnv path. Ensures that direnv can be executed even if the PATH is changed #369.
  * CHANGE: stdlib: direnv_load: disallow watching in child
    Allows the `use nix --pure` scenario in #368
  * README: add OpenSuSE to the list of distros
  * Revert "use_nix: unset IN_NIX_SHELL"

2.16.0 / 2018-05-09
==================

  * NEW: add support for elvish (#356)
  * NEW: config: allow to disable stdin on eval (#351)
  * DOC: Add the usage of source_up to the README (#347)
  * FIX: default.nix: fix compilation

2.15.2 / 2018-02-25
==================

  * FIX: lintian warnings (#340)
  * FIX: release process (#342)

2.15.1 / 2018-02-24
==================

  * FIX: support for go 1.10 (#339)

2.15.0 / 2018-02-23
==================

  * NEW: TOML configuration file! (#332, #337)
  * NEW: support for allow folder whitelist (#332)
  * NEW: add anaconda support (#312)
  * CHANGE: use_nix: unset IN_NIX_SHELL

2.14.0 / 2017-12-13
==================

  * NEW: Add support for Pipenv layout (#314)
  * CHANGE: direnv version: make public
  * FIX: direnv edit: run the command through bash
  * FIX: website: update ditto to v0.15

2.13.3 / 2017-11-30
==================

  * FIX: fixes dotenv loading issue on macOS `''=''`

2.13.2 / 2017-11-28
==================

  * FIX: direnv edit: fix path escaping
  * FIX: stdlib: fix find_up
  * FIX: stdlib: use absolute path in source_up
  * FIX: remove ruby as a build dependency
  * FIX: go-dotenv: update to latest master to fix a parsing error

2.13.1 / 2017-09-27
==================

  * FIX: stdlib: make direnv_layout_dir lazy (#298)

2.13.0 / 2017-09-24
==================

  * NEW: stdlib: configurable direnv_layout_dir
  * CHANGE: stdlib: source the direnvrc directly
  * FIX: permit empty NODE_VERSION_PREFIX variable
  * FIX: pwd: Don't use -P to remove symlinks (#295)
  * FIX: also reload when mtime goes back in time
  * FIX: Prevent `$HOME` path from being striked (#287)
  * BUILD: use the new `dep` tool to manage dependencies
  * BUILD: dotenv: move to vendor folder

2.12.2 / 2017-07-05
==================

  * stdlib layout_python: fixes on no arg

2.12.1 / 2017-07-01
==================

  * FIX: stdlib path_add(), see #278
  * FIX: install from source instructions

2.12.0 / 2017-06-30
==================

  * NEW: support multiple items in path_add and PATH_add (#276)
  * NEW: add a configurable DIRENV_WARN_TIMEOUT option (#273)
  * CHANGE: rewrite the dotenv parsing, now supports commented lines
  * CHANGE: pass additional args to virtualenv (#261)
  * FIX: stdlib watch_file(): escaping fix
  * FIX: only output color if $TERM is not dumb (#264)
  * FIX: the watch_file documentation

2.11.3 / 2017-03-02
==================

  * FIX: node version sorting (#255)

2.11.2 / 2017-03-01
==================

  * FIX: Typo in MANPATH_add always generates "PATH missing" error. (#256)

2.11.1 / 2017-02-20
==================

  * FIX: only deploy the go 1.8 version

2.11.0 / 2017-02-20
==================

  * NEW: stdlib.sh: introduce MANPATH_add <path> (#248)
  * NEW: provide packages using the equinox service
  * CHANGE: test direnv with go 1.8 (#254)
  * FIX: Add warning about source_env/up
  * FIX: go-md2man install instruction

2.10.0 / 2016-12-10
==================

  * NEW: `use guix` (#242)
  * CHANGE: use go-md2man to generate the man pages
  * FIX: tcsh escaping (#241)
  * FIX: doc typos and rewords (#226)

2.9.0 / 2016-07-03
==================

  * NEW: use_nix() is now watching default.nix and shell.nix
  * NEW: Allow to fix the bash path at built time
  * FIX: Panic on `direnv current` with no argument
  * FIX: Permit empty NODE_VERSION_PREFIX variable
  * FIX: layout_python: fail properly when python is not found

2.8.1 / 2016-04-04
==================

  * FIX: travis dist release

2.8.0 / 2016-03-27
==================

  * NEW: `direnv export json` to facilitate IDE integration
  * NEW: watch functionality thanks to @avnik
    Now direnv also reload on associate .env and .envrc changes.
  * NEW: stdlib `watch_file` function thanks to @avnik
    Allows to monitor more files for change.
  * NEW: stdlib `use node` function thanks to @wilmoore
  * NEW: `direnv prune` to remove old allowed files thanks to @punitagrawal
    Only works with newly-generated files since we're not storing the path
    inside of them.

2.7.0 / 2015-08-08
==================

  * NEW: use_nix() helper to stdlib. Thanks @gfxmonk
  * FIX: Added SHELLOPTS to ignored vars. Thanks @fernandomora
  * FIX: Removed shellcheck offenses in the stdlib, better escaping
  * FIX: typos. Thanks @camelpunch, @oppegard

2.6.1 / 2015-06-23
==================

  * FIX: source_env handles missing .envrc gracefully. Thanks @gerhard
  * FIX: Empty variable as unloading in Vim. Thanks @p0deje
  * FIX: Corrected spelling mistake in deny command. Thanks @neanias

2.6.0 / 2015-02-15
==================

  * NEW: tcsh is now supported ! Thanks @bbense
  * CHANGE: `direnv dump` now ignores `BASH_FUNC_` exports. Thanks @gfxmonk
  * CHANGE: Interactive input during load is now possible. Thanks @toao
  * FIX: allow workaround for tmux users: `alias tmux='direnv exec / tmux'`
  * FIX: hardened fish shell escaping thanks to @gfxmonk

Thanks @bbense @vially and @dadooda for corrections in the docs

2.5.0 / 2014-11-04
==================

  * NEW: Use a different virtualenv per python versions for easier version
    switching. Eg: ./.direnv/python-${python_version}
  * NEW: Makes `layout python3` a shortcut for `layout python python3`. Thanks
    @ghickman !
  * NEW: Allows to specify which executable of python to use in `layout_python`
  * CHANGE: `layout python` now unsets $PYTHONHOME to better mimic virtualenv
  * CHANGE: Don't make virtualenvs relocatable. Fixes #137
  * OTHER: Use Travis to push release builds to github

2.4.0 / 2014-06-15
==================

 * NEW: Try to detect an editor in the PATH if EDITOR is not set.
 * NEW: Preliminary support for vim
 * NEW: New site: put the doc inside the project so it stays in sync
 * NEW: Support for Cygwin - Thanks @CMCDragonkai !
 * NEW: Allow to disable logging by setting an empty `DIRENV_LOG_FORMAT`
 * NEW: stdlib `layout perl`. Thanks @halkeye !
 * CHANGE: layout ruby: share the gem home starting from rubygems v2.2.0
 * CHANGE: Allow arbitrary number of args in `log_status`
 * CHANGE: Bump command timeout to 5 seconds
 * FIX: Adds selected bash executable in `direnv status`
 * FIX: man changes, replaced abandoned ronn by md2man
 * FIX: `make install` was creating a ./bin directory
 * FIX: issue #114 - work for blank envs. Thanks @pwaller !
 * FIX: man pages warning. Thanks @punitagrawal !
 * FIX: Multi-arg EDITOR was broken #108
 * FIX: typos in doc. Thanks @HeroicEric and @lmarlow !
 * FIX: If two paths don't have a common ancestors, don't make them relative.
 * FIX: missing doc on layered .envrc. Thanks @take !

2.3.0 / 2014-02-06
==================

 * NEW: DIRENV_LOG_FORMAT environment variable can be used tocontrol log formatting
 * NEW: `direnv exec [DIR] <COMMAND>` to execute programs with an .envrc context
 * CHANGE: layout_python now tries to make your virtualenv relocatable
 * CHANGE: the export diff is not from the old env, not the current env
 * CHANGE: layout_go now also adds $PWD/bin in the PATH
 * FIX: Hides the DIRENV_ variables in the output diff. Fixes #94
 * FIX: Makes sure the path used in the allow hash is absolute. See #95
 * FIX: Set the executable bit on direnv on install
 * FIX: Some bash installs had a parse error in the hook.

2.2.1 / 2014-01-12
==================

The last release was heavily broken. Ooops !

 * FIX: Refactored the whole export and diff mechanism. Fixes #92 regression.
 * CHANGE: DIRENV_BACKUP has been renamed to DIRENV_DIFF

2.2.0 / 2014-01-11
==================

Restart your shells on upgrade, the format of DIRENV_BACKUP has changed and is
incompatible with previous versions.

 * NEW: `direnv_load <command-that-outputs-a-direnv-dump>` stdlib function
 * CHANGE: Only backup the diff of environments. Fixes #82
 * CHANGE: Renames `$DIRENV_PATH` to `$direnv` in the stdlib.
 * CHANGE: Allow/Deny mechanism now includes the path to make it more secure.
 * CHANGE: `direnv --help` is an alias to `direnv help`
 * CHANGE: more consistent log outputs and error messages
 * CHANGE: `direnv edit` only auto-allows the .envrc if it's mtime has changed.
 * CHANGE: Fixes old bash (OSX) segfault in some cases. See #81
 * CHANGE: The stdlib `dotenv` now supports more .env syntax
 * FIX: Restore the environment properly after loading errors.

2.1.0 / 2013-11-10
==================

 * Added support for the fish shell. See README.md for install instructions.
 * Stop recommending using $0 to detect the shell. Fixes #64.
 * Makes the zsh hook resistant to double-hooking.
 * Makes the bash hook resistant to double-hooking.
 * More precise direnv allow error message. Fixes #72

2.0.1 / 2013-07-27
==================

 * Fixes shell detection corner case

2.0.0 / 2013-06-16
==================

When upgrading from direnv 1.x make sure to restart your shell. The rest is
relatively backward-compatible.

 * changed the execution model. Everything is in a single static executable
 * most of the logic has been rewritten in Go
 * robust shell escaping (supports UTF-8 in env vars)
 * robust eval/export loop, avoids retrys on every prompt if there is an error
 * stdlib: added the `dotenv [PATH]` command to load .env files
 * command: added `direnv reload` to force-reload your environment

