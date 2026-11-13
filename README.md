# VKARD BAT Studio — mises à jour

Ce dépôt public ne contient que les mises à jour de **VKARD BAT Studio** (aucun code source, aucune donnée client) :

- `manifest.json` : dernière version publiée (numéro, archive, empreinte SHA-256, notes) ;
- `vkard-bat-studio-x.y.z.tar.gz` : moteur et interface de cette version (les 3 dernières sont conservées).

L'application installée lit `manifest.json` au démarrage puis toutes les 4 h, télécharge l'archive, vérifie son empreinte et propose de redémarrer. Les fichiers sont servis gratuitement par GitHub (raw.githubusercontent.com).
