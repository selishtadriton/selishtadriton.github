<!-- tipografia e sistemit-->

<!--  Madhesia e shkronjave ( Font Sizes) -->

0 / 12 / 14 / 16 / 18 / 20 / 24 / 30 / 36 / 44 / 52 / 62 / 74 / 86 / 98

<!-- Pesha e shkronjave (Font Weights) -->

Default 400
Medium: 500
Semi-bold: 600
Bold: 700

<!-- Lartesia e vijave ( line Heights) -->

Default: 1
Small: 1.05
Medium: 1.2
Paragraph default: 1.6

<!-- Hapsira ne mes shkronjave ( letter spacing) -->

-0.5px
0.75px

<!-- Ngjyrat ( colors) -->

- Primary: #e67e22

- Tints:
  #fdf2e9
  #fae5d3
  #eb984e

<!-- -  Hijet (Shades): -->

#cf711f
#45260a

<!-- Thekësimet dhe Gritë (Accents and  Greys)  -->

#888
#767676 (lightest grey allowed on #fff)
#6f6f6f (lightest grey allowed on #fdf2e9)
#555
#333 -->
#888
#767676 (lightest grey allowed on #fff)
#6f6f6f (lightest grey allowed on #fdf2e9)
#555
#333

<!-- Hijet ( Shadows ) -->

0 2.4rem 4.8rem rgba(0, 0, 0, 0.075);

<!--  Rrezja e mureve (Border Radius) -->

Default: 9px
Medium: 11px

<!-- Hapsira ne Sistem (Spacing System) -->

2 / 4 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 80 / 96 / 128

<!-- specifika e përzgjedhësit (selector specificity) apo * -->

- {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  }

html {
/_font-size: 10px;
/_ 10px / 16px = 0.625 = 62.5% _/
/_ Percentage of user's browser font-size setting
font-size: 62.5%;
}

_body {
font-family: "Rubik", sans-serif;
line-height: 1;
font-weight: 400;
color: #555;
}_

.container {
/_ 1140px _/
max-width: 120rem;
padding: 0 3.2rem;
margin: 0 auto;
