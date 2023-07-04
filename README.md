![Titlepage](example-images/slide1.png)
# Leiden University Beamer Theme
A beamer theme that aims to closely mimic [Leiden University](https://www.leidenuniversity.nl/)'s presentation slides as provided in their [house style](https://huisstijl.leidenuniv.nl/en/).

I am by no means a LaTeX expert so please, if you have any suggestions, feel free to create an issue or pull request!

## Getting Started
The Beamer class and, therefore, this theme, can be used with the following installations: pdfLaTeX, LaTeX+dvips, LuaLaTeX and XeLaTeX. It has only been tested through [Overleaf](https://www.overleaf.com).

To get started, I recommended modifying `example.tex` to your liking. Feel free to remove the `README.md` file and the `example-images` directory. These are only required for the text you are currently reading here on GitHub and do not affect the actual presentation in any way.

**For Overleaf**\
It is designed to easily integrate with Overleaf and has, therefore, additionally been made [available as Template on the Overleaf platform](https://www.overleaf.com/latex/templates/leiden-university-beamer-theme/ryfcpypnvzhr). Copying the template that has been made available is the easiest when working on Overleaf.

**For Other Applications**\
This repository can be downloaded as an archive and extracted at the location of your liking.

## Options
### Font
The theme is meant to be used with the Minion Pro font as in use by the university. This font is, however, not allowed to be redistributed. If you have got access to the font yourself, you can add it to your local copy of this repository. The theme expects the font files, if present, to be in TTF format, with filenames 'Minion Pro <Regular/Bold/Italic/Bold Italic>'. If you have got a different format, the way the theme interprets font files can be changed in `beamerthemelu.sty` under font options.

### Class Option
A language can be provided to the beamer class as an option, this will then get passed along to the theme. By default, the theme requires the Babel package as it allows the theme to automatically translate Leiden University's footer text. Currently, two translations are provided: one for Dutch, and English for every other set language.

### Theme Options
- `footer` if set, can be used to change the layout of the footer. Information displays the author short, institution short and title short. Empty removes all text except for the slide numbering. None removes the footer completely.
  - _Default: 'Discover the World at Leiden University' in either English or Dutch, see above on the documentclass option._
  - _Option(s): information, empty, none_

- `style` if set, can be used to change the accent colour to the colour of your faculty of choice.
  - _Default: midblueLU (#8592BC)_
  - _Option(s): social, science, humanities, archaeology, fgga, medicine, law_

- `styleslidenumbering` if set, change the colour of the background of the slide numbering to match the colour of the style option.
  - _Default: darkblueLU (#001158)_
  - _Option(s): \<none\>_

- `addstandoutfootline` if set, adds the footline to the standout template.
  - _Default: footline is removed._
  - _Option(s): \<none\>_

## Copyright
To this project applies the LaTeX Project Public License version 3 (LPPL Version 1.3c  2008-05-04).

## Thanks
I would like to thank @TAdeJong and @Thyrum for their initial work on an unofficial beamer theme for Leiden University and for sparking my interest to come up with a version to call my own!

## Additional Example Images
![Titlepage](example-images/slide2.png)
![Titlepage](example-images/slide3.png)
![Titlepage](example-images/slide4.png)
![Titlepage](example-images/slide5.png)
![Titlepage](example-images/slide6.png)
![Titlepage](example-images/slide7.png)
