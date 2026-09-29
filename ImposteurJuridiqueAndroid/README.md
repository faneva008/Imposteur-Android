# Imposteur Juridique — Android 100 % hors ligne

Projet Android Studio qui embarque l'application HTML dans une WebView locale.

## Hors ligne
- Aucun CDN Tailwind.
- Font Awesome est embarqué dans `app/src/main/assets/fontawesome`.
- Aucune police Google distante n'est requise ; la police utilise un fallback système.
- La permission INTERNET a été retirée du manifeste.
- Toute la logique du jeu est chargée depuis `file:///android_asset/index.html`.

## Compilation
Ouvrir le dossier dans Android Studio puis :
**Build > Build Bundle(s) / APK(s) > Build APK(s)**.

APK debug : `app/build/outputs/apk/debug/app-debug.apk`

Nom de l'application : **Imposteur Juridique**
Identifiant : `com.imposteurjuridique.app`
