# Contributing

> Adapted from [frc6506/docs](https://github.com/frc6506/docs/blob/master/CONTRIBUTING.md

First, please note that you will need to create your own branch or fork as the master branch is protected.  Creating your own workspace helps prevents conflicts and gives the various GitHub Actions time to inspect your work before you work goes live.

## Issues

Check out the issues list

## Pull Requests

## Spellcheck

[![Spellcheck Action](https://github.com/frc6506/frc6506.github.io/actions/workflows/spell.yml/badge.svg)](https://github.com/frc6506/frc6506.github.io/actions/workflows/spell.yml)

An automatic spell checker runs as a GitHub Action.  Note that at this time, there are no other writing inspectors used.  Although slightly finicky, the VS Code extension [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) can help to catch misspelled words.

### Word Whitelist

> The word whitelist was adapted from [frc6506/docs - extension settings](https://github.com/frc6506/docs/blob/master/.vscode/settings.json) and [frc6506/docs - spell check action word list](https://github.com/frc6506/docs/blob/master/.github/workflows/config/.wordList.txt)

The word white list is located at `.github/workflows/config/.wordList.txt`.  Please keep it neatly formatted in alphabetical order.  The VS Code extension [Permute Lines](https://marketplace.visualstudio.com/items?itemName=earshinov.permute-lines) adds the command `Sort Lines Ascending` to the Commands Pallet ([Ctrl] + [Shift] + [P]) for easier sorting.

## Markdown Information

[Introduction to markdown](https://www.markdownguide.org/getting-started/)

[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

## Markdown

[![Markdown Linter](https://github.com/frc6506/frc6506.github.io/actions/workflows/markdownwonLinter.yml/badge.svg)](https://github.com/frc6506/frc6506.github.io/actions/workflows/markdownwonLinter.yml)
An automatic markdown linter inspects the all markdown files.  You can use the VS Code extension [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) to help you out in VS Code.

Also checkout the VS Code extension [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) for a live preview in VS Code.

### Rules

[Rules List](https://github.com/DavidAnson/markdownlint/blob/main/doc/Rules.md})

### Ignored Rules - and Current Implementation

MD013 - The line length is ignored.  It is recommend you enable word wrap.
MD028 - Two separate block quotes may now be placed next to each other.
MD029 - Numbered lists may either use all 1s as number place holders or actually number the lists in order.
MD033 - Inline HTML is currently permitted, but please avoid using it too much.
MD036 - Allow top level text to be emphasized, even when not part of a paragraph.  Headings should still use the normal pound sign (`#`) designation, but this allows the italics updated on line to not be flagged.

## Compress Images

![Compress Images](https://github.com/frc6506/docs/workflows/Compress%20Images/badge.svg)
Nonprofits get free space, but the compress images action should be running anyways.

[Site Index](https://frc6506.github.io/docs/index)

## Generic Information of about GitHub Pages

> More information will be added on our [documentation website](https://frc6506.github.io/docs/)

> The version of this file on our [documentation website](https://github.com/frc6506/docs/blob/master/CONTRIBUTING.md) may be more up to date

[Basic Overview of what GitHub pages is](https://pages.github.com/)

[Introduction to Jekyll](https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll)

[Basic Overview of how this repository is setup](https://nicolas-van.github.io/easy-markdown-to-github-pages/)

<br>

_Updated 20220206T1230 PT_
