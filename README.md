# CakePHP Bookmarker Application

A Simple Bookmarker application using CakePHP

#CakePHP Installation Guide

1. Download [Composer](http://getcomposer.org/doc/00-intro.md) or update `composer self-update`.
2. Run `php composer.phar create-project --prefer-dist cakephp/app [app_name]`.

If Composer is installed globally, run

```bash
composer create-project --prefer-dist cakephp/app
```

In case you want to use a custom app dir name (e.g. `/myapp/`):

```bash
composer create-project --prefer-dist cakephp/app myapp
```

You can now either use your machine's webserver to view the default home page, or start
up the built-in webserver with:

```bash
bin/cake server -p 8765
```

Then visit `http://localhost:8765` to see the welcome page.


#Bookmarker Implementation

This is a simple Bookmark Application using CakePHP.

1. Created a new Database in MAMP
2. Configured the Database
3. Generated the Model/View/Controller Code using 'bin/cake Bake'
4. Created User Login/logout Page and hashed the password.
5. View Bookmarks based on specific tag(Ex. Cooking/Romance).
6. Enabled Registration and restricted access to bookmarks based on user credentials.
7. User who logs using his credentials can only access his/her Bookmarks. User can edit/delete only his bookmarks.

