# Arsène Valentin Reims — site vitrine

Site one-page statique (HTML/CSS/JS, aucune dépendance, aucun build).
Boutique : 7 rue Théodore Dubois, 51100 Reims · 07 62 41 37 84

## Fichiers

| Fichier | Rôle |
|---|---|
| `index.html` | Page complète (styles + scripts inclus) |
| `interior.webp` | Intérieur — hero + fond de la devise |
| `facade.webp` | Façade — galerie + aperçu réseaux sociaux |
| `wall.webp` | Mur d'e-liquides — section « La maison » |
| `counter.webp` | Comptoir — galerie |
| `kit.webp` | Gamme maison — galerie |
| `favicon.svg` | Icône d'onglet (monogramme AV) |
| `.nojekyll` | Désactive Jekyll sur GitHub Pages |

## Mise en ligne

**GitHub Pages** : Settings → Pages → Source « Deploy from a branch » → `main` / `(root)`.
**Vercel / Netlify** : importer le repo, framework « Other », aucune commande de build, dossier de sortie `/`.

## À compléter avant livraison

- [ ] Remplacer les photos par de vraies photos de la boutique (mêmes noms de fichiers, format WebP, ~1200 px de large)
- [ ] Remplacer le monogramme AV reconstruit par le SVG officiel (symbole `#av` dans `index.html` + `favicon.svg`)
- [ ] Footer : raison sociale, SIRET, page « Mentions légales »
- [ ] Vérifier les horaires avec le gérant (objet `HOURS` en haut du script)
- [ ] Mettre `og:image` en URL absolue une fois le domaine connu

## Réglages rapides

- Densité de la fumée sur le site : `const SITE={I:.62,…}` (`.45` discret → `.8` présent)
- Fluidité sur machines lentes : `const SCALE=innerWidth<820?.32:.42` (baisser pour alléger)

## Conformité

Publicité pour les produits du vapotage interdite (art. L3513-4 CSP) : ne pas ajouter de prix, promotions ou allégations santé. Contrôle d'âge 18+ à l'entrée.
