
[![][Fontbakery]](https://theseunbadejo.github.io/nsibidi-libre/fontbakery/fontbakery-report.html)
[![][Universal]](https://theseunbadejo.github.io/nsibidi-libre/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://theseunbadejo.github.io/nsibidi-libre/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://theseunbadejo.github.io/nsibidi-libre/fontbakery/fontbakery-report.html)
[![][Shaping]](https://theseunbadejo.github.io/nsibidi-libre/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftheseunbadejo%2Fnsibidi-libre%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftheseunbadejo%2Fnsibidi-libre%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftheseunbadejo%2Fnsibidi-libre%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftheseunbadejo%2Fnsibidi-libre%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftheseunbadejo%2Fnsibidi-libre%2Fgh-pages%2Fbadges%2FUniversal.json

Agu Display is an EGWU axis variable font with three main decorative styles at 0, 20 and 60. With origins in the Ekpe secret society's Nsibidi pictographs, Agu Display brings the ancient mystique of Nsibidi symbols to life with inspiration from a rich West African heritage, extending from Cross River to Cameroon. 

From the Uzo, Ala to Osisi masters, let Agu Display take you on a winding path through time, merging tradition with contemporary style in a unique typographic adventure as your words dance with history!

![Nsibidi Libre](documentation/NL1.gif)
![image](https://github.com/theseunbadejo/nsibidi-libre/assets/47482372/48aa6778-4bd4-4c2a-be45-9363e00960aa)

## About

Agu Display was designed by Seun Badejo and released in 2024. It features stylistic influences from the popular Kablammo and Jokerman fonts with decorative influences from Nsibidi and Neo-Nsibidi. 

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://theseunbadejo.github.io/nsibidi-libre.

## Changelog

When you update your font (new version or new release), please report all notable changes here, with a date.
[Font Versioning](https://github.com/googlefonts/gf-docs/tree/main/Spec#font-versioning) is based on semver. 
Changelog example:

**26 May 2021. Version 2.13**
- MAJOR Font turned to a variable font.
- SIGNIFICANT New Stylistic sets added.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
