# drupalv8_up_to_date
System requirements

Last updated October 15, 2015. Created on February 2, 2003.
Edited by B_man, jcnventura, japerry, hansfn. Log in to edit this page.

Note: this page should not be edited without first discussing the changes in a Drupal Core issue as the requirements for each version of Drupal are decided upon by the Drupal Core developers.

To install and run Drupal your web server must meet certain minimum requirements. Most web hosting companies meet these requirements. However, a few stand out by also actively supporting the Drupal community. If you need hosting, consider selecting one of these web hosts.

Disclaimer
Note that the minimum requirements of Drupal core can be subject to change, given an important enough reason. Where such a change is likely to have broad impact on Drupal's user base, every effort will be made to communicate these decisions ahead of time.

Disk space
A minimum installation requires 15 Megabytes. 60 MB is needed for a website with many contributed modules and themes installed. Keep in mind you need much more for the database, files uploaded by the users, media, backups and other files.

Web server
Apache, Nginx, or Microsoft IIS
More details about web server requirements.

Database
Drupal 8:
MySQL 5.5.3/MariaDB 5.5.20/Percona Server 5.5.8 or higher with PDO and an InnoDB-compatible primary storage engine,
PostgreSQL 9.1.2 or higher with PDO,
SQLite 3.6.8 or higher
Drupal 7:
MySQL 5.0.15/MariaDB 5.1.44/Percona Server 5.1.70 or higher with PDO,
PostgreSQL 8.3 or higher with PDO,
SQLite 3.3.7 or higher
Drupal 6:
MySQL 4.1.1 or higher,
PostgreSQL 7.1
Microsoft SQL Server and Oracle are supported by additional modules.
More details about database requirements.

PHP
Drupal 8: PHP 5.5.9 or higher
Drupal 7: PHP 5.2.5 or higher (5.4 or higher recommended).
Drupal 6: PHP 5.x only (5.2.5 or higher recommended). Warning: support for PHP 4.x has been dropped. Drupal core should work with PHP 5.3.x, but PHP 5.3.x and higher may produce errors or unexpected behavior especially for contributed modules and themes.
More details about PHP requirements, including PHP memory.

See also the Site Performance section of the Administration Guide and the webhosting troubleshooting FAQ.
