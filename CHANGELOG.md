# Changelog
## Docker-based LAMP stack 1.0.0
* Initial release.

## Docker-based LAMP stack 1.1.0
* Fixed IP ranges in docker-compose and README.
* Added DRUSH and PHP_SHOW_ERRORS variables for PHP-FPM container.
* Added DOCUMENT_ROOT as example variable for using the site in subfolders.
* Added sample configs folder and commented special directories in docker-compose.yml for PHP-FPM(PHP-5, PHP-7), Apache2, NGINX.
* Split MailHog to be the independent container and added a dependency on MailHog to PHP-FPM.
* Added references to MongoDB, Node.js in README.
* Started section in the documentation for Docker Toolbox.