# **Akaunting**

Akaunting is a free, open source and online accounting software designed for small businesses and freelancers. It is built with modern technologies such as Laravel, VueJS, Tailwind, RESTful API etc. Thanks to its modular structure, Akaunting provides an awesome App Store for users and developers.

- Home - The house of Akaunting
- Forum - Ask for support
- Documentation - Learn how to use
- Developer Portal - Generate passive income
- App Store - Extend your Akaunting
- Translations - Help us translate Akaunting

## **Requirements**
- PHP 8.0 or higher
- Database (eg: MySQL, PostgreSQL, SQLite)
- Web Server (eg: Apache, Nginx, IIS)
- Other libraries

## **Framework**

Akaunting uses Laravel, the best existing PHP framework, as the foundation framework and Module package for Apps.

## **Installation**
- Install Composer and Npm
- Clone the repository: git clone https://github.com/akaunting/akaunting.git
- Install dependencies: composer install ; npm install ; npm run dev
- Install Akaunting:

```
php artisan install --db-name="akaunting" --db-username="root" --db-password="pass" --admin-email="admin@company.com" --admin-password="123456"
```

Create sample data (optional): 
``` php artisan sample-data:seed ```

## **Contributing**
Please, be very clear on your commit messages and pull requests, empty pull request messages may be rejected without reason.

When contributing code to Akaunting, you must follow the PSR coding standards. The golden rule is: Imitate the existing Akaunting code.

Please note that this project is released with a Contributor Code of Conduct. By participating in this project you agree to abide by its terms.

## Translation
If you'd like to contribute translations, please check out our Crowdin project.

## Changelog
Please see Releases for more information what has changed recently.

## Security
Please review our security policy on how to report security vulnerabilities.
