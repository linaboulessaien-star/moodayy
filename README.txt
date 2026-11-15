# MOODAY — version tablette

## Ce que contient cette première version
- Accueil, calendrier mensuel, tâches, notes et thèmes.
- Interface responsive en portrait et paysage.
- Sauvegarde locale dans le navigateur.
- Export/import manuel des données.
- Base PWA (manifest + service worker) pour installation sur Android.

## Pour l'installer sur ta tablette
Une PWA doit être publiée sur une adresse HTTPS pour que Chrome puisse proposer l'installation.
1. Crée un compte GitHub si tu n'en as pas.
2. Crée un dépôt public nommé `mooday`.
3. Ajoute tous les fichiers de ce dossier à la racine du dépôt.
4. Dans Settings > Pages, choisis `Deploy from a branch`, puis `main` et `/ (root)`.
5. Ouvre l'adresse GitHub Pages obtenue dans Chrome sur ta tablette.
6. Menu ⋮ > `Installer l'application` ou `Ajouter à l'écran d'accueil`.

## Important
Cette version ne synchronise pas encore automatiquement le PC et la tablette. Les données sont stockées localement sur chaque appareil. Pour transférer les données, utilise Personnaliser > Exporter puis Importer. La synchronisation cloud sera une prochaine étape.

Le projet est fourni gratuitement. GitHub Pages convient à un petit site statique public. Ne mets aucune donnée privée dans le dépôt.
