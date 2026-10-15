# BeatLab — fichiers pour hébergement

Ces fichiers préparent BeatLab comme application web installable (PWA). Ils ne constituent pas encore un APK.

## Publication avec GitHub Pages
1. Crée un dépôt public nommé `beatlab`.
2. Téléverse le contenu de ce dossier à la racine du dépôt (pas le dossier ZIP lui-même).
3. Dans le dépôt, ouvre Settings → Pages.
4. Sous Build and deployment, choisis Deploy from a branch, branche `main`, dossier `/ (root)`, puis Save.
5. Attends que GitHub Pages affiche l'adresse HTTPS du site.
6. Ouvre cette adresse sur Android avec Chrome. Pour tester l'installation, menu ⋮ → Ajouter à l'écran d'accueil (le libellé peut varier).

## Préparer un APK
Une fois le site public en HTTPS, ouvre https://www.pwabuilder.com/ et saisis l'adresse du site. Vérifie le rapport PWA puis explore l'option Android. Les services et les exigences peuvent évoluer; ne paie rien sans vérifier les conditions.

## Notes
- L'export WAV est local.
- L'export MP3 charge lamejs depuis un CDN et nécessite Internet.
- Ce prototype n'a pas encore été validé sur tous les appareils Android.
