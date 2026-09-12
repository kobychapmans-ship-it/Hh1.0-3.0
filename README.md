# HH1+3 Port — Independent BattleScribe Game System

This repository is an **independent Horus Heresy 1.0 game system** containing the HH 1.41 / Horus Heresy 3.0 content ported into HH1 rules. It intentionally uses a different game-system ID, different catalogue IDs, and different filenames from the archived BSData HH1 repository so both systems can be installed side-by-side.

**Game system:** `HH1+3 Port - Warhammer 30,000 The Horus Heresy`  
**Game-system ID:** `7cea4d03-96df-56cc-b989-a4d939beb6ef`  
**Game-system revision:** `200`

## BattleScribe data index

Use the repository's raw `index.bsi` URL in BattleScribe. The index downloads compressed `.gstz` / `.catz` files from `distro/`, preventing filename collisions with the original HH1 data.

## Port systems included

- 6 new native Rites of War with Legion/allegiance gating
- 8 Corrupted Rites of War
- 4 Legiones Hereticus variants
- 10 Legion Inductii templates
- Thousand Sons Hereticus Inductii replacement squad
- 8 Solar Auxilia Cohort Doctrines
- Dark Mechanicum Proscribed Techno-arcana
- Questoris Dark Blessings with Household Rank mutual exclusion
- Legion gating for the ported legion-specific units and characters

## Independence from original HH1

The original BSData game-system ID was `ca571888-56a9-c58e-ddaf-54f4713538bc`. This port uses `7cea4d03-96df-56cc-b989-a4d939beb6ef`. All 14 catalogue root IDs have also been regenerated and cross-catalogue root references updated. Internal rules/profiles remain based on the HH1 source so the conversion logic is preserved.

---

Horus Heresy
============

[![Latest release](https://img.shields.io/github/release/BSData/horus-heresy-1e.svg?style=flat-square)](https://github.com/BSData/horus-heresy-1e/releases/latest)
[![Commits (since latest release)](https://img.shields.io/github/commits-since/BSData/horus-heresy-1e/latest.svg?style=flat-square)](https://github.com/BSData/horus-heresy-1e/releases)
[![Open bugs](https://img.shields.io/github/issues/BSData/horus-heresy-1e/bug.svg?style=flat-square&label=bugs)](https://github.com/BSData/horus-heresy-1e/issues?q=is%3Aissue+is%3Aopen+label%3Abug)
[![Contributors](https://img.shields.io/github/contributors/BSData/horus-heresy-1e.svg?style=flat-square)](https://github.com/BSData/horus-heresy/graphs-1e/contributors)
[![Commit activity the past year](https://img.shields.io/github/commit-activity/y/BSData/horus-heresy-1e.svg?style=flat-square)](https://github.com/BSData/horus-heresy-1e/pulse/monthly)

[![Chat on Discord](https://img.shields.io/discord/558412685981777922.svg?logo=discord&style=popout-square)](https://www.bsdata.net/discord)

## Important

__BattleScribe v1.15 users Notice__: _However we don't support BattleScribe v1.15 any longer, all the files in their last revisions for that BattleScribe are available [here](https://github.com/BSData/horus-heresy-/releases/tag/6.9.3). Downloading `.bsr` file(one of the Downloads) and importing it in BattleScribe v1.15 will allow you to use these no-longer-maintained datafiles._

## Overview ##

__What's this?__

This repo contains the Horus Heresy 1.0 Data. It is unmaintained and here for archival purposes. 

BSData organisation created this project. It's a GitHub repository of datafiles.
Maintained by community, in no way endorsed by BattleScribe or any other company/publisher. If you want
to develop - cool! We need you! Take a look at [our homepage][BSData.net]

__Okay, nice project. Is it actually working?__ _I just want those files..._

Yeah! We have it hosted on AppSpot. Take a look: [BattleScribe Data on Appspot][]

__I found a bug!__ / *I have another request*

Great, thank you! Please [Report a bug][bug report] - you can also suggest enhancements and raise other issues there.


## Standards

### References

* Base Rulebook (7th Edition) = BRB 7th (I'm using the digital in order to copy/paste so no pages)
* Legiones Astartes: Age of Darkness Army List = LA:AODAL
* Legiones Astartes: Age of Darkness Legions = LA:ADL
* Mechanicum: Taghmata Army List = M:TAL
* Crusade Imperialis: Army List = CI:AL
* Horus Heresy 1: Betrayal = HH1: Betrayal (and so on)
* Horus Heresy: General Errata and FAQ v1.0 = HH:GEAFAQV1.0

## Links ##

* [BSData organization homepage][BSData.net]
* [BattleScribe app homepage](https://www.battlescribe.net/)

[BSData.net]: https://www.bsdata.net/
[bug report]: https://github.com/BSData/horus-heresy/issues/new/choose


## HH 1.41 / HH3 → HH1 Port

This fork contains the 98-page HH 1.41 additions packet ported to Horus Heresy 1.0. The **1.41.0-port2** pass converts the major late-Heresy systems from informational rules cards into native BattleScribe selectors and conditional roster logic: new Rites of War, Corrupted Rites, Legiones Hereticus, Inductii templates, Solar Auxilia Cohort Doctrines, Dark Mechanicum Proscribed Techno-arcana, and Questoris Dark Blessings.

The source transcript and porting map are retained under `port-docs/`, and generated validation reports are under `generated/`. This repository is ready to be uploaded as a standalone GitHub data repository; the included GitHub Actions validate datafiles and publish `.catpkg` assets on releases.
