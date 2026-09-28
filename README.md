# Groove Scribe Batterie (Android)

Convertit une partition MuseScore (.mscz) de batterie en liens Groove Scribe.
Tout se passe sur le téléphone, rien n'est envoyé nulle part.

## Obtenir l'APK

1. Envoie ce dossier sur un dépôt GitHub (voir les étapes dans les explications de Claude).
2. Va dans l'onglet **Actions** du dépôt : le build démarre tout seul (3 à 6 minutes).
3. Une fois le build terminé (coche verte), va dans **Releases** (colonne de droite de la page du dépôt),
   ouvre « Dernière version » et télécharge `groove-scribe-batterie.apk` depuis ton téléphone.
4. Ouvre le fichier téléchargé. Android demandera d'autoriser l'installation depuis ce navigateur : accepte.

## Modifier l'appli

Le code de l'appli est dans `www/index.html`. Chaque modification envoyée sur GitHub
relance le build et remplace l'APK dans les Releases.
