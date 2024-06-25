# counttherefs
A LaTeX package that counts `/ref` appearances (of equations or theorem-environments) in your .tex code and displays them (next to the equation or theorem-environment, respectively).
## Usage
1. Import **counttherefs**, e.g. by copying _counttherefs.sty_ into the folder where your .tex file is and add `\usepackage{counttherefs}` to your .tex. Mind the order of imports of various packages (c.f. this documentation).
2. Change an equation's or a theorem-environment's `\label` into a `\clabel`, a "**c**ounted label".
3. Re-compile.
   
You should now see a little counter in gray next to the numbering of the equation or theorem-environment.

C.f. the documentation *counttherefs.pdf* for options on designing your counter, for known bugs, and for the commented source code.
## Examples
Some exemplary screenshots from my [master thesis](https://github.com/tob-asco/theses) where I used this package as `\usepackage[times,lightgray]{counttherefs}`:

![theorem-environment example](https://github.com/tob-asco/counttherefs/blob/main/theorem-environment-example.png)

![equation example](https://github.com/tob-asco/counttherefs/blob/main/equation-example.png)
