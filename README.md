# Epp Discrete Math 5th Solutions

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

***You can find the PDF file on the Releases page on the right 👉👉👉👉👉***

## About

> ***It soon became clear that the unconscious instincts for logic and language which had enabled me to succeed were not shared by the large majority of my students.*** - Susanna Epp (author of [Discrete Mathematics with Applications, 5th edition](https://www.amazon.com/Discrete-Mathematics-Applications-Susanna-Epp-ebook/dp/B07M87BWRC))

[Bjarne Stroustrup on the importance of Mathematics and Computer Science fundamentals](https://www.youtube.com/watch?v=-QxI-RP6-HM)

Solutions to Susanna Epp's [Discrete Mathematics 5th Edition](https://www.amazon.com/Discrete-Mathematics-Applications-Susanna-Epp-ebook/dp/B07M87BWRC)

**This is much gentler than [MIT Math for CS](https://github.com/spamegg1/Math-for-CS-solutions), and covers the same material.**

## Contact

Please feel free to [open a discussion](https://github.com/spamegg1/Epp-Discrete-Math-5th-solutions/discussions) if you spot an error or a typo!

Contact me: `spamegg1` on Discord, or [on Slack](https://join.slack.com/t/spamegg/shared_invite/zt-1vhzofzrl-ucBjeQEQkl9Ol3wpvL9VPw), or [on Matrix](https://matrix.to/#/!GQFJgtvxFByBVixTAi:matrix.org?via=matrix.org)

## Contributing

Only edit the `Epp.tex` source file, I use Github Actions to compile and release the PDF file automatically.

So, you do not have to include your compiled PDF in your pull requests.

### Compiling locally

You don't need to do this for contributing, Github actions will take care of it for you on pull requests.

But if you are compiling locally, you'll need:

- a full [TeXlive](https://www.tug.org/texlive/) installation (you do need the *full* thing, I use some rare / obscure packages), and
- since I am using [minted](https://github.com/gpoore/minted) for syntax highlighting some code, you'll have to pass the [`-shell-escape` argument](https://tex.stackexchange.com/questions/598818/how-can-i-enable-shell-escape#598819) to `latexmk` for the compilation.

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
