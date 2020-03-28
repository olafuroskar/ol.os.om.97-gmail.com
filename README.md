# Verkefni 2 - Greining reiknirita

## Keyrsla

Til þess að compile-a þarf að nota `C++ 14` þar sem kóðinn nýtir sér eiginleika þeirrar útgáfu. Með GCC compilernum er það gert á eftirfarandi hátt
```{console}
g++ -std=c++14 -o battleships -battleships.cpp
```
### Gnuplot
Ég nýtti mér [gnuplot](gnuplot.info) til þess að teikna gröfin sem eru í `.pdf`-skjalinu. Ef það er uppsett á tölvu viðkomandi ásamt [boost](boost.org)-library þá er hægt af-commenta þau comment í kóðanum sem eru merkt `gp` og compile-a á eftirfarandi hátt
```{console}
g++ -std=c++14 -o battleships battleships.cpp -lboost_iostreams -lboost_system -lboost_filesystem
```
`/gnuplot-iostream` er fengið frá [https://github.com/dstahlke/gnuplot-iostream](https://github.com/dstahlke/gnuplot-iostream).

