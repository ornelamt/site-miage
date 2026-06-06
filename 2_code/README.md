# Code — Site MIAGE WordPress

## Contenu
- `site_miage.sql` : export complet de la base de données WordPress
- `siteMiage.zip` : fichiers complets du site WordPress (à ajouter)

## Prérequis
- XAMPP (avec Apache et MySQL)
- WordPress 6.9.1
- PHP 8.2 ou supérieur

## Installation en local
1. Installer XAMPP et le démarrer
2. Décompresser `siteMiage.zip` dans `C:/xampp/htdocs/`
3. Créer une base de données `site_miage` dans phpMyAdmin
4. Importer `site_miage.sql` dans cette base
5. Modifier `wp-config.php` avec tes identifiants de base de données
6. Accéder au site sur `http://localhost/siteMiage`

## Technologies utilisées
- WordPress 6.9.1
- Thème Astra
- Plugin Quiz And Survey Master (QSM) v10.1.1
- PHP 8.2 / MySQL
