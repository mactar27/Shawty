# Le site d'Astou

Un site immersif, romantique et privé — prêt à héberger et partager par lien.

## Pour l'ouvrir tout de suite
Double-clique simplement sur `index.html`. Ça ouvre déjà tout : le site marche directement dans le navigateur.

## Pour obtenir un lien privé à partager
Le plus simple et gratuit :
1. Va sur **https://app.netlify.com/drop**
2. Glisse-dépose tout le dossier `site` (celui qui contient `index.html` et `images/`)
3. Netlify te donne un lien du type `https://xxx.netlify.app` — envoie ce lien à Astou.
   Personne ne le trouvera sans le lien exact (pas indexé sur Google).

## Pour personnaliser les textes
Ouvre `index.html` avec un éditeur de texte (Notes, VS Code...) et cherche les commentaires
`✏️ À PERSONNALISER`. Tu peux changer :
- Les légendes de chaque photo dans le tableau `PHOTOS` (vers le milieu du fichier)
- Les "chapitres" et textes du mur des souvenirs et de la timeline (`MEMORIES`)
- Les 4 pages de la lettre (section `#lettre` dans le HTML), pour y mettre tes vrais mots

## Pour ajouter une musique d'ambiance
1. Mets un fichier mp3 dans un dossier `audio/` à côté d'`index.html`, nommé `song.mp3`
2. Dans `index.html`, décommente la ligne :
   `<!-- <audio id="bgAudio" loop src="audio/song.mp3"></audio> -->`

Bonne surprise à préparer. ♥
