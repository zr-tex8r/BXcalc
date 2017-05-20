BXcalc Package
==============

LaTeX: To extend the functionality of the calc package

This package bundle consists of the following packages:

  * bxcalcize: To make calc expressions available in more places.

  * bxcalcux: To add user-defined units to the calc syntax.

In addition, this bundle provides the bxcalc package, which simply loads
the above-mentioned packages internally.

### System requirement

  * TeX format: LaTeX.
  * TeX engine: Anything.
      - Some functions requires the e-TeX extension.
  * Dependent packages:
      - calc

### Installation

  - `*.sty` → $TEXMF/tex/latex/BXcalc

### License

This package is distributed under the MIT License.

bxcalc package ― main
----------------------

This package simply loads all other packages in this bundle.

bxcalcize package ― to make calc expressions available in more places
----------------------------------------------------------------------

Some standard LaTeX commands involving length specification do not allow
the use of calc expressions. This package makes such uses possible.

See the manual bxcalcize.pdf for detail.

bxcalcux package ― to add user-defined units to the calc syntax
----------------------------------------------------------------

This package enables users to define new length units and use them in
calc expressions.

See the manual bxcalcux.pdf for detail.

Revision History
----------------

  * Version 1.0  〈2017/05/21〉
      - The first public version as this bundle, which has been seperated
        from the old BXjatool bundle.

--------------------
Takayuki YATO (aka. "ZR")  
https://github.com/zr-tex8r
