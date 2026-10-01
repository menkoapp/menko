# Menko

**Le logiciel gratuit pour gérer ta collection de cartes de sport Topps et Panini sur Windows, en local.**

[Télécharger la dernière version](https://github.com/menkoapp/menko/releases/latest/download/Menko-Installateur.exe) · [Site officiel](https://menko.framer.website) · [Checklists](https://menko.framer.website/checklists)

---

## Ce que fait Menko

- **Checklists complètes** : importe la checklist d'un set au format Excel et coche les cartes que tu possèdes. Ta progression s'affiche en pourcentage, par section.
- **Ta collection en images** : recto et verso pour chaque carte, vue grille ou liste, logos des 32 franchises NBA, favoris, doublons, cartes numérotées et gradées.
- **Scan depuis ton iPhone** : connecte ton téléphone au PC par QR code, photographie une carte, l'app détecte son contour, redresse la perspective et envoie l'image au PC. Loupe de précision pour ajuster les coins au doigt.
- **Recherche par photo** : retrouve les cartes de ta collection qui ressemblent le plus à une photo, sans aucune IA ni service en ligne.
- **Suivi des ventes** : prix, frais, plateforme, statut d'envoi, bénéfice net et bilan par mois.
- **Export Excel** : liste de tes cartes manquantes, de celles que tu as, ou de tes doublons.
- **Sauvegarde automatique** quotidienne, et avant chaque mise à jour.

## Installation

1. Télécharge `Menko-Installateur.exe` depuis la [dernière version](https://github.com/menkoapp/menko/releases/latest).
2. Lance le fichier. Windows affiche un avertissement SmartScreen parce que l'application n'est pas signée numériquement : clique sur **Informations complémentaires**, puis sur **Exécuter quand même**.
3. Suis l'assistant. Menko s'installe pour l'utilisateur courant, sans droits administrateur.

Pour mettre à jour, relance simplement le nouvel installateur : tes données ne sont jamais touchées.

## Tes données t'appartiennent

Menko fonctionne **entièrement hors connexion**. Aucun compte, aucun serveur, aucune donnée envoyée nulle part. Tout est stocké sur ton ordinateur, dans `%APPDATA%\Menko` :

- `data\collection.json` : ta collection, tes ventes, tes dépenses
- `data\images` : les photos de tes cartes
- `auto-backups` : les sauvegardes automatiques des 14 derniers jours

La connexion avec ton téléphone passe par ton réseau Wi-Fi local, protégée par un code que tu choisis.

## Configuration

Windows 10 ou 11, 64 bits. Environ 300 Mo d'espace disque, hors images de cartes.

## Questions et bugs

Ouvre une [issue](https://github.com/menkoapp/menko/issues) ou passe par la [page Contact](https://menko.framer.website/contact) du site.

Une checklist manque ? Demande-la sur la [page Checklists](https://menko.framer.website/checklists), je la convertis au format Menko et je la mets en ligne.

---

Menko n'est pas affilié à Topps ni à Panini.
