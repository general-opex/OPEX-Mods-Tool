## 📋 Changelog

 ### V2.0 Stable

▶ Launch War Thunder
New "▶ Launch War Thunder" button added in the sidebar. Launches launcher.exe directly  in one click. Displays an error message if the executable is not found.

 Userskins folder auto-creation
When clicking "Open Userskins Folder", if the folder doesn't exist the tool now offers to create it automatically instead of just showing an error

### V1.9 Stable
🔍 "Verify OPEX System are ready" button
New single button that checks everything in one click:

Detects and deletes non-OPEX .bank files from the mod folder
Detects and removes conflicting useLoops lines from config.blk
If nothing is found → ✔ OPEX system is ready

### V1.8 Stable
🐛 Bug fix — enable_mod:b=yes duplication
When adding enable_mod:b=yes to config.blk, the line was incorrectly duplicated if it already existed. This is now fixed — the existing line is kept as-is without adding another one.
🔍 New — Conflict checker
New "Check conflicts" button in the CONFIG.BLK section. It detects the following lines that are known to conflict with OPEX Mod and offers to remove them:

useloopsForGunSound:b=yes
useloopsForGunSound:b=no
useLoopsForGMGunSound:b=yes
useLoopsForGMGunSound:b=no

### V1.7 Stable

** Migration PyQt6 -> PySide6**
The framework has been switched from PyQt6 to PySide6. Both are based on the same Qt technology and the interface is identical — this change is purely legal.

PyQt6 is licensed under **GPL v3**, which requires publishing the source code when distributing the application. PySide6 uses the **LGPL v3** license, which allows distributing the `.exe` freely on GitHub without any obligation to publish the source code.

The only requirement is to mention PySide6 in a CREDIT file included with the release.

---

**EN/FR 🇫🇷**

** Migration PyQt6 -> PySide6**
Le framework passe de PyQt6 à PySide6. Les deux sont basés sur la même technologie Qt et l'interface est strictement identique — ce changement est purement juridique.

PyQt6 est sous licence **GPL v3**, ce qui oblige à publier le code source lors de la distribution de l'application. PySide6 utilise la licence **LGPL v3**, qui permet de distribuer le `.exe` librement sur GitHub sans aucune obligation de publier le code source.

La seule obligation est de mentionner PySide6 dans un fichier `CREDITS.txt` inclus dans la release.


<img width="902" height="651" alt="Capture d&#39;écran 2026-07-08 173717" src="https://github.com/user-attachments/assets/2b94e0fb-b3bf-48fa-bdff-0eea3b127418" />






## 🇬🇧 ENGLISH

**What is OPEX Mods Tool?**
OPEX Mods Tool is a free, all-in-one utility designed for War Thunder players who use sound mods, skins and usersights. Instead of manually editing config files and digging through folders, everything is handled in a clean, intuitive interface — in one click.

---

**✨ Key Features**

🗂 **Folder Management**
Instantly access your mod, Userskins, and UserSights folders. The tool remembers all paths so you never have to search again.

⚙️ **Config.blk Manager**
Check, enable, or disable `enable_mod:b=yes` in your War Thunder config with a single click — no text editor needed.

📦 **Mod Installer**
Select a `.zip` mod file and the tool extracts it directly into the right folder. Handles file conflicts with a replace confirmation, and shows you exactly which files were left untouched.

⬇️ **Mod Download Menu**
Built-in links to download the best OPEX sound mods:
→ OPEX Mod · Crew Pack FR · Crew Pack US · Crew Pack DE

🗑 **One-Click Cleanup**
Remove all mods and reset your config in a single click with the "Delete All Mods & Config" button.

🌐 **Bilingual Interface**
Full English and French support — switch at any time. Language preference is saved automatically.

📖 **Built-in User Guide**
A step-by-step guide opens on first launch to help new users get started quickly. Can be re-opened anytime via the "?" button.

---

**💻 Requirements**
Windows 10 / 11 · War Thunder installed

**🔗 Find us on**
YouTube · Discord · Patreon

---
---

## 🇫🇷 FRANÇAIS

**C'est quoi OPEX Mods Tool ?**
OPEX Mods Tool est un utilitaire gratuit tout-en-un pensé pour les joueurs War Thunder qui utilisent des mods sonores, skins et viseurs personnalisé. Fini l'édition manuelle de fichiers de config et la navigation dans des dossiers — tout se gère depuis une interface propre et intuitive, en un clic.

---

**✨ Fonctionnalités principales**

🗂 **Gestion des dossiers**
Accès instantané à vos dossiers mod, Userskins et UserSights. L'outil mémorise tous les chemins pour que vous n'ayez jamais à les rechercher.

⚙️ **Gestionnaire Config.blk**
Vérifiez, activez ou désactivez `enable_mod:b=yes` dans votre config War Thunder en un seul clic — sans ouvrir le moindre éditeur de texte.

📦 **Installateur de mods**
Sélectionnez un fichier `.zip` et l'outil extrait automatiquement les fichiers dans le bon dossier. Gestion des conflits avec confirmation de remplacement, et affichage des fichiers non concernés.

⬇️ **Menu de téléchargement**
Liens intégrés pour télécharger les meilleurs mods sonores OPEX :
→ OPEX Mod · Crew Pack FR · Crew Pack US · Crew Pack DE

🗑 **Nettoyage en un clic**
Supprimez tous les mods et réinitialisez votre config d'un seul clic avec le bouton "Supprimer tous les mods & config".

🌐 **Interface bilingue**
Support complet Français et Anglais — changez à tout moment. La préférence de langue est sauvegardée automatiquement.

📖 **Guide d'utilisation intégré**
Un guide pas à pas s'ouvre au premier lancement pour aider les nouveaux utilisateurs. Accessible à tout moment via le bouton "?".

---

**💻 Configuration requise**
Windows 10 / 11 · War Thunder installé

**🔗 Retrouvez-nous sur**
YouTube · Discord · Patreon
