# Interface Own Finance

Mon espace finance personnel, publié gratuitement avec GitHub Pages.

- **`/patrimoine/`** — *Mon Patrimoine* : suivi de patrimoine (portefeuille multi-devises en CHF, allocation cible, objectifs, simulateur d'intérêts composés, calculateur FIRE, import CSV).
  Les données sont enregistrées uniquement dans le navigateur (localStorage) : rien n'est envoyé sur GitHub. Utiliser *Import & réglages → Copier les données* pour faire une sauvegarde.
- **`/academy/`** — *PM Academy* : cours de finance (EN / FR). Chaque cours est dans `academy/courses/<id>.en.html` et `<id>.fr.html`.

## Ajouter un cours

1. Créer `academy/courses/<id>.en.html` et `academy/courses/<id>.fr.html`.
2. Dans `academy/index.html`, passer le `status` du cours de `'soon'` à `'ready'`.

## Mise en ligne

Settings → Pages → *Deploy from a branch* → branche `main`, dossier `/ (root)`.
Le site est ensuite disponible sur `https://kissackjonathan.github.io/Interface_Own_Finance/`.
