# Noyaux, masse et énergie — application Android
Simulation 3D interactive (2e Bac PC) — **Pr. Hicham MESBAH**

## Ouvrir le projet
1. Décompresser le dossier.
2. Android Studio → File → Open → choisir le dossier `NoyauxMasseEnergie`.
3. Attendre la synchronisation Gradle (connexion Internet nécessaire la première fois).
4. Brancher un téléphone (mode développeur + débogage USB) ou lancer un émulateur, puis ▶ Run.

## Générer l'APK à installer sur les téléphones
Build → Build Bundle(s) / APK(s) → Build APK(s). L'APK se trouve dans `app/build/outputs/apk/debug/`.

## Modifier la simulation
Tout le contenu est dans `app/src/main/assets/index.html`.

## Remarque
La bibliothèque 3D (three.js) et les polices sont chargées depuis Internet : le téléphone doit être connecté.
