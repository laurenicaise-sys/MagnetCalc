════════════════════════════════════════════════════════════════
  MagnetCalc v3 — Pack de dimensionnement magnétique
  Laure Nicaise — INP / GLDF, 2026
════════════════════════════════════════════════════════════════


CE PACK CONTIENT
────────────────

  MagnetCalc_v3.html          →  L'outil de calcul (à ouvrir dans un navigateur)
  guide_magnetcalc_v3.docx    →  Le guide d'utilisation complet (document PDF joint) 


POUR COMMENCER
──────────────

  1. Double-cliquer sur MagnetCalc_v3.html
  2. Il s'ouvre dans votre navigateur (Chrome, Firefox, Safari, Edge)
  3. Aucune installation. Aucune connexion internet requise.
  4. Commencer par l'onglet ◎ Mode d'emploi si c'est votre première utilisation, vous pouvez aussi vous référer au PDF 


À QUOI ÇA SERT
───────────────

MagnetCalc v3 est un outil d'aide au dimensionnement des systèmes de
présentation magnétique pour la conservation du patrimoine.

Il calcule, pour une œuvre donnée :
  - le nombre minimal d'aimants nécessaires (avec facteur de sécurité)
  - l'espacement recommandé entre aimants
  - la force effective réelle en cisaillement vertical
  - la pression de contact exercée sur l'œuvre
  - la charge linéaire (g/cm)
  - un schéma à l'échelle de la disposition des aimants

Il prend en compte : la nature et la fragilité de l'œuvre, le type
d'aimant (pull force, forme, dimensions), le fond ferromagnétique,
les matériaux intercalaires (tamponnage), l'angle d'exposition,
l'hygrométrie, la durée d'exposition et le type d'éclairage.

⚠ Les résultats sont des estimations préliminaires destinées à
  orienter les choix. Ils ne remplacent pas un test empirique sur
  l'œuvre réelle dans ses conditions d'exposition.
  Facteur de sécurité ≥ 3 toujours appliqué.
  — Spicer (2019, ch. 4)


ORGANISATION DE L'OUTIL
────────────────────────

L'interface est divisée en quatre espaces accessibles par la barre
de navigation en haut de l'écran :

  ◎ Mode d'emploi
      Guide pas à pas, explication de chaque paramètre et de chaque
      résultat, aimant-crochet, alertes colorées, FAQ, glossaire.
      → Point d'entrée recommandé pour toute première utilisation.

  ◈ Guide pédagogique
      Rappels de physique magnétique illustrés : traction vs
      cisaillement, effet du gap, triboélectricité, série
      triboélectrique, angle d'exposition.
      Quiz interactif de 6 questions pour valider la compréhension.

  ⊞ Calculateur
      Formulaire de saisie (panneau gauche) commun à trois
      sous-onglets :
        ① Calculateur principal  — nombre d'aimants + schéma
        ② Force max admissible   — pression de contact
        ③ Aimant-crochet         — accrochage mural par friction

  ⊟ Tables & Sources
      10 tables empiriques issues de la littérature académique
      publiée + 9 formules entièrement sourcées.
      À consulter pour justifier les choix auprès d'un comité.


COMMENT UTILISER LE CALCULATEUR
────────────────────────────────

  1. Renseigner les cinq sections du panneau gauche :
       ① L'œuvre      — dimensions, poids, fragilité, éléments particuliers
       ② Aimants      — type, forme, dimensions, pull force
       ③ Fond         — type, épaisseur, revêtement de surface
       ④ Tamponnage   — matériau intercalaire, épaisseur totale
       ⑤ Conditions   — angle, durée, HR, température, éclairage

  2. Cliquer sur ▶ Calculer

  3. Lire les résultats dans le panneau droit :
       - Cartes colorées (vert = OK / orange = vigilance / rouge = action requise)
       - Schéma à l'échelle de la position des aimants
       - Détail numérique étape par étape de la formule

  La saisie est commune aux trois sous-onglets : renseigner une
  seule fois, naviguer librement entre les onglets.


INFORMATIONS TECHNIQUES
────────────────────────

  Compatibilité    : Chrome, Firefox, Safari, Edge (versions récentes)
  Installation     : aucune
  Connexion        : non requise après ouverture
                     (les polices peuvent mettre quelques secondes à
                     charger sans connexion, sans affecter le calcul)
  Données          : aucune donnée transmise, tout fonctionne en local
  Format           : fichier HTML autonome, auto-contenu


SOURCES PRINCIPALES
────────────────────

Les formules et coefficients de MagnetCalc v3 sont fondés sur :

  Spicer, G. (2019). Magnetic Mounting Systems for Museums and
    Cultural Institutions. Spicer Art Books, Delmar.

  Billot, M. (2016). L'utilisation des aimants pour présenter et
    assurer le maintien des biens culturels. Mémoire, HES-SO /
    Musée du quai Branly. Données in Spicer (2019b), tab. 4a–5b.

  Garcia, V. (2015). Conservation-restauration d'une bannière
    votive de Dunhuang. Mémoire INP, spécialité Peinture, p. 52.

  Henel, M. (2006). Guano de Judit Reigl (MAMVP). Mémoire INP,
    p. 122.

  Kuperholc-Duruel, N. (2021). La présentation d'un masque
    bamiléké au MQB. Mémoire INP, spécialité Objets, p. 183-209.

  Etre, K. et al. (2014). Rare Attraction. JAIC, 53(4).

La bibliographie complète est disponible dans le guide .docx et
dans l'onglet ⊟ Tables & Sources de l'outil.


────────────────────────────────────────────────────────────────
  Annexe au mémoire INP — GLDF, Cabinet de l'amateur, 2024-2025
  Laure Nicaise
════════════════════════════════════════════════════════════════
