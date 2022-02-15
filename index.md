# Hello

abc

```!
using LaTeXStrings
import PGFPlotsX
PGFPlotsX.@pgf PGFPlotsX.Axis(
    {
      xlabel = L"x",
      ylabel = L"f(x) = x^2 - x + 4"
    },
    PGFPlotsX.Plot(
      PGFPlotsX.Expression("x^2 - x + 4")
    )
)
```
