# BackupManager Plugin pour GLPI

Plugin GLPI permettant la gestion des sauvegardes, des scripts d’exécution et des tâches planifiées via une interface simple et centralisée.

## 🚀 Fonctionnalités

- Création et gestion de sauvegardes manuelles ou programmées
- Association de scripts aux tâches de sauvegarde
- Historique des jobs exécutés
- Définition de politiques de conservation

## 🛠️ Installation

1. Copier le dossier du plugin dans `.../glpi/plugins/backupmanager`
2. Se rendre dans le menu **Configuration > Plugins**
3. Cliquer sur **Installer** puis **Activer**
4. Les droits sont automatiquement attribués au profil Super-Administrateur

## 🔐 Droits et Profils

Le plugin initialise les droits pour tous les profils, et attribue automatiquement **tous les droits** (lecture, mise à jour, suppression) au Super-Administrateur.

## 🧱 Prérequis

- GLPI ≥ 10.x
- PHP ≥ 7.4
- MySQL ≥ 5.7

## 📄 Licence

Ce plugin est distribué sous la licence **GNU GPL v3+**  
Voir : [https://www.gnu.org/licenses/gpl-3.0.html](https://www.gnu.org/licenses/gpl-3.0.html)

---

# BackupManager Plugin for GLPI

GLPI plugin to manage backups, job executions, and associated scripts through a simple centralized interface.

## 🚀 Features

- Create and manage manual or scheduled backups
- Link scripts to backup jobs
- Execution history of jobs
- Retention policy definition

## 🛠️ Installation

1. Copy the plugin folder into `.../glpi/plugins/backupmanager`
2. Go to **Configuration > Plugins**
3. Click **Install** then **Enable**
4. Rights are automatically granted to the Super-Administrator profile

## 🔐 Rights and Profiles

The plugin initializes rights for all profiles and automatically grants **full permissions** (read, update, delete) to the **Super-Administrator** profile.

## 🧱 Requirements

- GLPI ≥ 10.x
- PHP ≥ 7.4
- MySQL ≥ 5.7

## 📄 License

This plugin is released under the **GNU GPL v3+** license  
See: [https://www.gnu.org/licenses/gpl-3.0.html](https://www.gnu.org/licenses/gpl-3.0.html)
