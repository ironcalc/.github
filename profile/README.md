# IronCalc

The democratization of spreadsheets 

[![Discord chat][discord-badge]][discord-url]

[discord-badge]: https://img.shields.io/discord/1206947691058171904.svg?logo=discord&style=flat-square
[discord-url]: https://discord.gg/zZYWfh3RHJ

<https://www.ironcalc.com>

# ROADMAP

> [!WARNING]  
> This is work-in-progress. IronCalc in developed in the open. Expect things to be broken and change quickly until version 0.5

Major milestones:

* MVP (_Minimum Viable Product_), version 0.5.0
* Stable, version 1.0.0

## Version 0.5 or MVP (mid September 2024)

Version 0.5 includes the engine, javascript and nodejs bindings and a web application

Features of the engine include:

* Read and write xlsx files
* API to set and read values from cells
* Implemented 192 Excel functions
* Time functions with timezones
* Prepared for i18n but will only support English
* Wide test coverage

UI features of the web application (backed by the engine):

* Enter values and formulas. Browse mode
* Italics, bold, underline, horizontal alignment
* Number formatting
* Add/remove/rename sheets
* Copy/Paste extend values
* Keyboard navigation
* Delete/Add rows and columns
* Resize rows and columns
* Correct scrolling and navigation

## Version 1.0 or Stable

Minor milestones in the ROADMAD for version 1.0.0 (engine and UI):

* Implementation of arrays and array formulas
* Formula documentation and context help
* Merge cells
* Pivot tables
* Define name manager (mostly UI)
* Update main evaluation algorithm with a support graph
* Dynamic arrays (SORT, UNIQUE, ..)
* Full i18n support with different locales and languages
* Python bindings
* Full test coverage


