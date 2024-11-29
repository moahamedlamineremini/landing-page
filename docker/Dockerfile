# Utiliser une image PHP officielle avec Apache
FROM php:8.1-apache

# Installer les extensions nécessaires
RUN docker-php-ext-install pdo pdo_mysql

# Copier les fichiers du projet
COPY public/ /var/www/html/

# Configurer les permissions
RUN chown -R www-data:www-data /var/www/html
