# MP3download

L'application Flask (synchrone) déployée localement pour le téléchargement de fichiers audio, de fichiers vidéo et de listes de lecture de fichiers vidéo et audio (zip) à partir d'une URL YouTube valide.

#### Programmes en ligne de commande utilisés
  * `youtube-dl` - Utilisé pour télécharger le fichier depuis Internet.
  * `ffmpeg` - Utilisé pour les données de post-traitement, c’est-à-dire pour convertir un fichier du format .webm au format .mp3.
  
#### Dépendances
  * [flask](http://flask.pocoo.org/) - Un framework pour le backend.
  * [bs4](https://www.crummy.com/software/BeautifulSoup/) - Pour analyser le document HTML.
