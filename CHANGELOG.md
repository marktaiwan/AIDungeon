# Changelog
All notable changes to AIDungeon will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [[Unreleased]](https://github.com/AIDungeon/AIDungeon/compare/master...develop)

### Added
- This changelog!
- Formal grammars for the noble and knight contexts/prompts.
- Better regex logic to detect terminal states.
- Directory `saved_stories`.
- A few more censored words.
- Feedback for user for the censor command.
- iPython notebook utilities to save/load to Google Drive, and an OOM error workaround.
- install.sh now detects python version and fails if it's not supported.
- Issue and PR template improvements.

### Fixed
- Loading not working on `develop`.
- Loading now print properly.
- [No Save Game on Quit for Loaded Games](https://github.com/AIDungeon/AIDungeon/issues/97)
- install.sh no longer tries calling `apt-get` on distributions without it.
- Arch Linux now works with install.sh (with pyenv is used or python3.6 is set as python3).
- A bug that caused game to crash if given an incorrect game ID to load.

### Changed
- Made `install.sh` more robust.
- Sorted imports.
- Split the model downloading script into `download_model.sh` from `install.sh`.
- User commands are now case-insensitive.
- User commands are now denoted with the prefix `/`.

## [2.0.0] - 2019-12-05

### Added
- AIDungeon 2, which allows players to type in any desired action.

## [1.0.0] - ?

### Added
- AiDungeon Classic, which gives players action options to choose from.
