## Tano Theme

Tano is my personal Beamer theme based on [Metropolis](https://github.com/matze/mtheme)
by Matthias Vogelgesang.


## Installation

Installing Tano from source, like any Beamer theme, involves four easy
steps:

1. **Download the source** with a `git clone` of the [repository](https://github.com/ntadej/beamertheme-tano) or as a [zip archive](https://github.com/ntadej/beamertheme-tano/archive/master.zip) of the latest development version.

2. **Compile the style files** by running `make sty` inside the downloaded
    directory. (Or run LaTeX directly on `source/beamerthemetano.ins`.)

3. **Move the resulting `*.sty` files** to the folder containing your
   presentation. To use Tano with many presentations, run `make install`
   or move the `*.sty` files to a folder in your TeX path instead (might require
   `sudo` rights).

4. **Use the theme for your presentation** by declaring `\usetheme{tano}` in
    the preamble of your Beamer document.


## Usage

The following code shows a minimal example of a Beamer presentation using
Tano.

```latex
\documentclass{beamer}
\usetheme{tano}           % Use tano theme
\title{A minimal example}
\date{\today}
\author{Tadej Novak}
\institute{Institute}
\begin{document}
  \maketitle
  \section{First Section}
  \begin{frame}{First Frame}
    Hello, world!
  \end{frame}
\end{document}
```


## License

The theme itself is licensed under a [Creative Commons Attribution-ShareAlike
4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/). This
means that if you change the theme and re-distribute it, you *must* retain the
copyright notice header and license it under the same CC-BY-SA license. This
does not affect the presentation that you create with the theme.
