# IFRI_MentorLink — TODO (UI/UX Spec → Front)

## Étape 1 — Audit & cadrage
- [ ] Re-lire `index.html` et lister les écarts principaux vs spec (design system + écran 4)
- [ ] Définir la stratégie front-end (multi-pages HTML statiques) + layout shell partagé

## Étape 2 — Design System (tokens & composants)
- [x] Centraliser couleurs/typos/tokens dans une feuille CSS (ex: `styles.css`)
- [x] Créer des classes composants: Primary/Secondary/Ghost buttons, Inputs, Cards, Badges, Skeleton, navbar glass


## Étape 3 — Pages (génération)
- [x] Créer `landing.html` (écran 1)

- [x] Créer `auth.html` (écran 2)

- [x] Créer `onboarding.html` (écran 3)

- [x] Refactor `index.html` en `dashboard.html` (écran 4) + wrapper de navigation partagée

- [x] Créer `search.html` (écran 5)
- [x] Créer `create-offer.html` (écran 6)
- [x] Créer `create-demand.html` (écran 7)
- [x] Créer `matching.html` (écran 8)
- [x] Créer `profile.html` (écran 9)
- [x] Créer `messages.html` (écran 10)


## Étape 4 — Interactions & états
- [ ] Ajouter transitions (150ms cubic-bezier, 200ms page transition)
- [ ] Ajouter skeleton shimmer + états loading spinner (boutons)


## Étape 5 — Responsive
- [ ] Vérifier desktop/tablette/mobile pour chaque écran (grilles & breakpoints)

## Étape 6 — Vérification finale
- [ ] Ouvrir chaque page dans le navigateur et valider la conformité visuelle au spec

