# Stats Basket - Kit GitHub Pages

## Contenu
- `index.html` : application principale
- `manifest.webmanifest` : configuration d'installation tablette
- `service-worker.js` : cache simple pour un usage plus fluide
- `icon-192.png` et `icon-512.png` : icones de l'application
- `.nojekyll` : evite certains traitements GitHub Pages

## Mise en ligne sur GitHub
1. Cree un depot GitHub public, par exemple `stats-basket-tablette`.
2. Envoie tous les fichiers de ce dossier dans le depot.
3. Va dans **Settings > Pages**.
4. Dans **Build and deployment**, choisis **Deploy from a branch**.
5. Selectionne la branche **main** et le dossier **/(root)**.
6. Sauvegarde.
7. Attends la publication, puis ouvre l'URL fournie par GitHub Pages.

## Installation sur tablette
### iPad
- Ouvre l'URL dans Safari.
- Touche **Partager**.
- Choisis **Ajouter a l'ecran d'accueil**.

### Android
- Ouvre l'URL dans Chrome.
- Utilise **Ajouter a l'ecran d'accueil** ou **Installer l'application** si propose.

## Mise a jour
Quand tu modifies l'appli, remplace `index.html` dans le depot et pousse la nouvelle version sur GitHub. La tablette recuperera la mise a jour apres rechargement.
