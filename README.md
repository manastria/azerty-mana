Ce clavier reprend la disposition du clavier AZERTY de Windows (Français - France) en y apportant les modifications suivantes :

Sur la touche VK_OEM_7 : 

- le symbole 'SUPERSCRIPT TWO' (U+00B2) qui était en position de base est transféré en position ag.
- le symbole 'GRAVE ACCENT' (U+0060) prend la position de base

V1.7
Add exposant and indice from Bépo layout.

V1.6
ADD 5 - sh+ag - 2011 - Non-Breaking Hyphen
MOV 6 - sh+ag - 2013 - En Dash
MOV 7 - sh+ag - 2014 - Em Dash

Ajout avec la avec la touche morte AG+F
- 0075	2022	// u -> •
- 0069	2023	// i -> ‣
- 0068	26A0	// h -> ⚠
- 006A	26D0	// j -> ⛐
- 006C	2714	// l -> ✔
- 006D	2718	// m -> ✘

V1.5

- Ajout de e-dans-l’o 
  - o + AG      : U+0153
  - o + AH + AG : U+0152
  
- Modification
  - ESPACE + SH      : SP
  - ESPACE + AG      : NB SP   : espace insécable
  - ESPACE + AG + SH : NNB SP  : espace fin insécable

V1.4 Ajout des flèches avec la touche morte AG+F
- 0061	2190	// a -> ←
- 0062	27F9	// b -> ⟹
- 0063	27F7	// c -> ⟷
- 0064	21D1	// d -> ⇑
- 0065	2191	// e -> ↑
- 0066	21D2	// f -> ⇒
- 0067	21D4	// g -> ⇔
- 006E	27FA	// n -> ⟺
- 006F	27E9	// o -> ⟩
- 0070	27A4	// p -> ➤
- 0071	21D0	// q -> ⇐
- 0072	2192	// r -> →
- 0073	21D3	// s -> ⇓
- 0074	2194	// t -> ↔
- 0076	27F8	// v -> ⟸
- 0077	27F5	// w -> ⟵
- 0078	27F6	// x -> ⟶
- 0079	21C4	// y -> ⇄
- 007A	2193	// z -> ↓

V1.3
Déplacement de l'apostrophe typographique courbe
- 2 + SH + AG : U+00AB «
- 3 + SH + AG : U+00BB »
- ! + SH + AG : U+2212 − (signe moins)
- ; + AG      : U+00D7 ×
- : + AG      : U+00F7 ÷
- , + SH + AG : U+2026 …
- 5 + SH + AG : U+2013 – (Tiret long demi-cadratin)
- 6 + SH + AG : U+2014 — (Tiret cadratin)


V1.2
- Ajout des "flèches" avec la touche morte AG+F

V1.1
- Les lettres é, è, à, ù, ç sont mise en majuscule avec CAPS LOCK
- ESPACE + SH : NNBSP (U+202F)
- ESPACE + SH + AG : NBSP (U+00A0)
- 2 : U+00AB
- 3 : U+00BB
- 4 + SH + AG : U+2019 ’ (apostrophe courbe)

