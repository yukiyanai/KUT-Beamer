# KUT-Beamer


# [UNOFFICIAL] LaTeX Beamer Theme for Kochi University of Technology

**Yuki Yanai**, Assistant Professor, *School of Economics & Management, Kochi University of Technology*

This is an ***unofficial*** Beamer theme for KUT.

![Example](examples/example-KUT-Beamer.png)


## Installation

Download this direcotry by clicking **Download ZIP** button on the right.

Unzip the downloaded file, and move it to the directory where you keep LaTeX style files or Beamer theme files. In my environment, it is:

```
~/Library/texmf/tex/latex/beamer/
```

A Mac user's default directory should be something like:

```
/usr/local/texlive/2018/texmf/tex/latex/
```

A Windows user's default should be something like:

```
C:\localtexmf\tex\latex\beamer\themes\
```

Once you put the KUT-Beamer folder in the appropriate directory, type in the terminal:

```
sudo mktexlsr
```

## Usage

Add the following line to the preamble:

```
\usetheme{KUT}
```

Currently, four options are available.

1. nonav: suppress the navgaition bar
2. nologo: does not show the university logo mark
3. simplefoot: only the slide number is displayed in footer
4. jp: use the Japanese version of the university logo on the title page instaed of the English one

To use these options, write in the preamble

```
\usetheme[nonav]{KUT}
```

or

```
\usetheme[nologo]{KUT}
```

or

```
\usetheme[nonav,simplefoot,jp]{KUT}
```
etc.

Please use **nologo** option if you have not obtained the logo files yourself from the [KUT's official website](http://www.kochi-tech.ac.jp/kut_J/gakunai/internal/logomark.html), which you cannot access from outside the university (see **KUT Logo** below).



## Color Themes

At the moment, two color themes are available.

#### Theme 1: Kochi

This color theme mainly uses green and blue, which are KUT's school colors, and is distributed as [beamercolorthemekochi.sty](beamercolorthemekochi.sty).
Two school colors are kutgreen (PANTONE 370C; RGB 89, 150, 35) and kutblue (PANTONE 286C; RGB 0, 59, 148).

This is the default color theme for KUT Beamer.

To use this color theme with another Beamer theme, write in the preamble:

```
\usecolortheme{kochi}  
```

#### Theme 2: Tosayamada

This color theme mainly uses black and gray and is distributed as [beamercolorthemetosayamada.sty](beamercolorthemetosayamada.sty).

To use this color theme, write in the preamble:

```
\usecolortheme{tosayamada}  
```

## KUT Logo

Since I am not allowed to distribute the official logo marks of KUT, the logo files are not available here.

You must either obtain the logos from the official website of the university (internal access only) or use **nologo** option (see **Usage** above).


#### Getting the logos

To obtain the logos, you need to connect to KUT's network system. You can connect to the University's network on campus.

1. Go to [the download page](http://www.kochi-tech.ac.jp/kut_J/gakunai/internal/logomark.html) in KUT's official website.
1. Read [the rules](http://www.kochi-tech.ac.jp/kut_J/gakunai/internal/image/youkou.pdf) and [the guideline](http://www.kochi-tech.ac.jp/kut_J/gakunai/internal/image/KUT_rogoguideline_201603.pdf) about the university's logo marks.
1. Download three logo mark files:
	1. 2016_logo05.jpg
	1. 2016_logo07.jpg
	1. 2016_logo09.jpg
1. Save downloaded logo files in the **logo** folder inside KUT-Beamer folder.


## Examples

You will find some examples in [examples](examples) folder.
