# Ligne de commande

Introduction à [l'utilisation de la ligne de commande](https://fr.wikipedia.org/wiki/Interface_en_ligne_de_commande) avec l'interpréteur [Bash](https://fr.wikipedia.org/wiki/Bourne-Again_shell).

![Capture d’écran](https://raw.githubusercontent.com/AECS-17/AECS-informatique/master/ligne-de-commande/capture.png)

## Objectifs pédagogiques

1. Commandes de base
   - Utilisation de l'aide (`--help`, `man`)
   - Fichiers et dossiers:
     `cp`,
     `ls`,
     `mkdir`,
     `mv`,
     `pwd`,
     `rm`,
     `rmdir`,
     `touch`
   - Fichier texte:
     `cat`,
     `echo` (redirection `>`, `>>`),
     `sed` (substitution simple)
     `sort`,
     `wc`
   - Processus: `kill`, `ps`, `bg`, `fg`, `Ctrl+C`, `Ctrl+Z`, `&`

2. Transfert de fichiers
   - Téléchargement de page: `wget`
   - Session à distance: `scp`, `ssh`
   - Logiciel de gestion de versions: `git` (clone, log, status, diff, etc)

## Plan

0. Introduction. Exemple :
   On dispose de 100 photos au format JPEG et on souhaite les redimensionner,
   changer leur qualité et les compresser dans une archive ZIP afin de réduire
   la taille des fichiers. Comment s'y prendre ? Que faire si à la fin les
   fichiers sont encore trop volumineux pour les transférer (e.g. par courriel).
1. `pwd`, `pwd --help`, `man pwd`.
2. Créer/Supprimer/Renommer des fichiers et dossiers, vérifier avec `ls`.
3. Utiliser `echo` et `cat` pour créer et afficher des fichiers avec plusieurs lignes (e.g. liste de personnes).
4. Utiliser `sort`, `uniq`, `wc`, `sed` sur ces fichiers.
5. Illustrer les commandes de processus avec le programme `gedit`.
6. Télécharger une page web avec `wget`.
7. Envoyer la page sur une autre machine et se connecter à cette machine (`scp`, `ssh`).
8. Cloner ce dépôt `git https://github.com/AECS-17/AECS-informatique.git` et
   présenter les commandes et concepts de base selon le temps disponible.