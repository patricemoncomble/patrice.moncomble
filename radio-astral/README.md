# RADIO ASTRAL — by Astraël

Site radio / vitrine musicale autonome, construit autour du lecteur officiel Mixcloud.

- Fichier du site : `radio-astral/index.html` (CSS et JS inclus).
- Sept mixs publics temporaires sont définis dans le tableau `tracks` situé en bas du fichier.
- Chacun est lié à Mixcloud pour commentaires, favoris, reposts et partage.
- Les covers sont demandées à l'API publique Mixcloud et affichées si la plateforme les fournit.
- Boutons précédent / suivant / lecture, mode aléatoire, mode boucle et enchaînement automatique via l'événement `ended`.
- L'utilisateur doit lancer la lecture ; les règles d'autoplay des navigateurs et les restrictions Mixcloud restent applicables.
- Ce site n'effectue **aucun** streaming audio en dehors du lecteur Mixcloud et ne promet aucune augmentation automatique des statistiques.
- Responsive (mobile / ordinateur).

## Publication

Le dépôt `patricemoncomble/patrice.moncomble` n'avait pas GitHub Pages activé lors de l'installation (23 octobre 2026).
Pour publier les fichiers statiques :

1. Ouvrir https://github.com/patricemoncomble/patrice.moncomble/settings/pages
2. Sélectionner **Deploy from a branch**.
3. Sélectionner **main** et **/(root)**, puis enregistrer.

Une fois GitHub Pages activé pour cette source, l'adresse attendue du dossier radio est
https://patricemoncomble.github.io/patrice.moncomble/radio-astral/

Attention : ce choix publiera aussi la page d'accueil existante du dépôt (le site du livre).
Pour une radio complètement indépendante, créer ensuite un dépôt public séparé et y copier `index.html`.

## Édition

Remplacer les éléments du tableau `tracks` par les liens des sets choisis. Le titre, le genre et la durée sont modifiables. Ne pas intégrer de flux ou de téléchargements audio : Mixcloud assure l'hébergement et la lecture.
