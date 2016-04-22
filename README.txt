Drupal Bookstore - Narnes & Bobles
Drupal Code Review for Epicodus, 04.22.2016

by Michael Lor

Description

This website is a bookstore developed in Drupal. Its intended purpose is to provide multiple pages of navigation, such as About, Contact, and Location. This site implements views and blocks to show specific content.

Specific project goals include:

* Page creation.
* Enabling and utilizing core modules.
* Downloading and utilizing contrib modules.
* Creating user roles and setting custom permissions.
* Site configuration management using Strongarm and Features modules.
* Content management.

Setup

[For Code Reviewer Reference]
    database: bookstore
    database admin: admin_bookstore
    database admin password: test
    drupal site admin: admin
    drupal site admin password: test

1) Clone repository to local drive.

2) Open MAMP and click on 'Open WebStart page'.

3) Click on the Tools dropdown at the top of the page and select phpMyAdmin.

4) Select the Import tab and click the Choose File button under the 'File to Import:' section to bring up the file selection window.

5) The database file for this project will be a .zip file located under the /db-backup folder in the project's root folder.

6) Once the database is uploaded, go back to MAMP and select the Preferences menu.

7) Under the Web Server tab, click on the folder icon next to 'Document Root:' and select the drupal core folder for this project.

8) Navigate to localhost:8888 in a web browser to open the project.

Technologies Used
* Atom
* Drupal 7.43 (Feb 24 2016 Release)
* Drush
* phpMyAdmin
* MAMP
* Terminal

Drupal Contrib Modules Used
* Views
* Ctools (Chaos Tools)
* Features
* Strongarm

License

Copyright (c) 2016 - This software is licensed under the MIT license
