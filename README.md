xeCJKnumb.sty
=============

Porting the CJKnumb.sty to XeLaTeX.

Version: 4.8.4


How to use
----------
The LaTeX document **must** be in UTF-8 to work. Then load the package by:

```latex
\usepackage[taiwan]{xeCJKnumb}
```

The option is to determine which system to use:

- `taiwan`: 零一二三四五六七八九十百千萬億
- `china`: 零一二三四五六七八九十百千万亿
- `japan`: 零一二三四五六七八九十百千万億
- `capital`: 零壹貳參肆伍陸柒捌玖拾佰仟萬億
- `japancap`: 零壱弐参四五六七八九拾百千万億

default is `taiwan` for it is the historical way to write numbers.

Afterwards, please see CJKnumb package for command and usage. This is the copy
of `/usr/share/doc/latex-cjk-common/CJKnumb.txt`:

```
This is the file CJKnumb.txt of the CJK macro package ver. 4.8.4
(18-Apr-2015).

CJKnumb.sty
------------

This package provides commands to typeset CJK representations of
numbers (within a CJK or CJK* environment).

  \CJKnumber{number}
    Convert `number' to a full CJK representation.

  \CJKdigits{arg}
  \CJKdigits*{arg}
    Handle `arg' as a string of digits and convert each of them into the
    corresponding CJK digit. The starred version uses the traditional glyph
    for digit zero; the unstarred version uses the CJK circle glyph.

Usage:

  \usepackage{CJK}
  \usepackage{CJKnumb}


---End of CJKnumb.txt---
```
