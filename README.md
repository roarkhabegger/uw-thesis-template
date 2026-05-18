# uw-thesis-template
LaTeX Template for University of Wisconsin-Madison Doctoral Thesis

With new accessibility guidelines, it has become necessary to correctly tag the final thesis pdf. This tagging requires LuaLaTeX, unicode-math, and other restrictions from general LaTeX packages.

This thesis template was made by Dr. Evan Linck (tagging+accessibility and table formatting) and Dr. Roark Habegger (unicode version of physics.tex, AAS Journal commands/bibliography).

It derives from the following old templates which do not meet the accessibility standards but were very useful in constructing this template. 
- [https://github.com/willb/wi-thesis-template]
- Lizhou Sha's thesis
- Old astronomy templates: [https://github.com/fourwood/thesis-tex], [https://www.overleaf.com/3417557469tbmsmmdgfsrq]

The fake paper and text utilized in this template were generated with Microsoft Copilot. LaTeX code and compatibility was not generated with AI, unless people posted AI code to stack overflow and we got it from there.

Usage notes:
1. Make sure to compile with LuaLaTeX. This sometimes requires more runs at the end than the usual latex->bibtex->latex->latex to get the tagging correct. 
2. Be careful with importing libraries. Check if they are compatible with tagging. Otherwise, you may need to define your own commands and environments. For examples, see definitions.tex and physics.tex
3. Biggest change for equations is using \symbf and \symup instead of \mathbf and \mathrm. amsmath is not compatible with tagging. 
4. Use a software like verapdf to check that tagging has been done correctly. Note that a passing verapdf check does not imply compliance with all accessibility criteria, only that the structure and tagging of the pdf file itself has been done correctly. 

