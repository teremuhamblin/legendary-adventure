# Palette de couleurs
- — legendary-adventure

- Couleur principale — Or légendaire  
  Label: Legendary Gold  
  Hex: #F5C453  
  Usage: titres, éléments clés du HUD, boutons primaires, surbrillance.

- Couleur secondaire — Nuit mystique  
  Label: Mystic Night  
  Hex: #111827  
  Usage: arrière-plans, menus, écrans de chargement, cartes.

- Couleur d’accent — Acier runique  
  Label: Runic Steel  
  Hex: #E5E7EB  
  Usage: textes secondaires, bordures, icônes, séparateurs.

- Couleur d’alerte — Rouge danger  
  Label: Peril Red  
  Hex: #EF4444  
  Usage: dégâts, erreurs, alertes critiques, feedback négatif.

- Couleur de succès — Vert vitalité  
  Label: Vitality Green  
  Hex: #10B981  
  Usage: soins, succès de quêtes, validation d’actions.

---

Typographie

- Titres & logo  
  Police suggérée: style serif héroïque (ex: Cinzel, Cormorant Garamond ou équivalent)  
  Usage: LEGENDARY, titres d’écrans, menus principaux.

- Texte d’interface / HUD  
  Police suggérée: sans-serif lisible (ex: Inter, Roboto, Open Sans)  
  Usage: dialogues, menus, inventaire, tooltips.

- Hiérarchie typographique  
  - H1 (écran titre / gros titres): serif, majuscules, or (Legendary Gold)  
  - H2 (sous-titres / sections): serif ou sans-serif, Runic Steel  
  - Texte courant: sans-serif, #E5E7EB sur fond sombre  
  - Texte désactivé: même police, opacité réduite (60–70 %)

---

Style visuel général

- Ambiance: fantasy épique, sombre mais lisible, avec touches d’or et de lumière.  
- Formes:  
  - Boutons légèrement arrondis (4–6 px)  
  - Icônes inspirées de runes, armes, bannières  
- Effets:  
  - Légers glows dorés sur les éléments importants  
  - Ombres douces pour détacher les cartes / panneaux du fond  
- Illustrations:  
  - Silhouettes de montagnes, épées, soleils, constellations  
  - Textures discrètes (grain léger, parchemin, pierre)

---

Logo legendary-adventure

Je t’ai généré un logo pour le projet, avec :  
- une épée centrale  
- des montagnes  
- un soleil levant  
- le texte “LEGENDARY ADVENTURE” en capitales, avec “LEGENDARY” en clair et “ADVENTURE” en or.

Règles d’usage du logo

- Fond recommandé:  
  - Mystic Night (#111827) ou tout fond très sombre.  
- Zone de protection:  
  - Laisser au moins la hauteur de la lettre L autour du logo sans autre élément.  
- Tailles minimales:  
  - Web: largeur min. ~ 160 px  
  - Impression: largeur min. ~ 35 mm  
- Variantes conseillées:  
  - Version complète (emblème + texte) pour écrans titre, splash screen, README.  
  - Version emblème seul (épée + montagnes + soleil) pour favicon, icône, watermark.

---

Intégration dans ton repo legendary-adventure

Je te propose cette structure :

`bash
legendary-adventure/
├─ docs/
│  ├─ branding/
│  │  ├─ logo-full.png
│  │  ├─ logo-emblem.png
│  │  ├─ palette-colors.md
│  │  └─ typography.md
`

Et un début de docs/branding/PALETTE.md :

`md

Charte graphique — legendary-adventure

Palette

- Legendary Gold — #F5C453
- Mystic Night — #111827
- Runic Steel — #E5E7EB
- Peril Red — #EF4444
- Vitality Green — #10B981
`

---
