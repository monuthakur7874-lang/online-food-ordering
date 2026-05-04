# QuickBite - Online Food Ordering System

QuickBite is a PHP and MySQL based food ordering system with three separate panels:

- Customer panel for browsing food, placing orders, and tracking payments
- Admin panel for managing users, food items, categories, riders, and orders
- Delivery panel for riders to accept orders, update live status, and view earnings

## Tech Stack

- PHP
- MySQL / MariaDB
- Bootstrap 5
- HTML, CSS, JavaScript

## Project Structure

- `index.php` - main portal entry page
- `user/` - customer panel
- `admin/` - admin panel
- `delivery/` - rider panel
- `config/db.php` - database connection and shared session setup
- `db.sql` - database schema and default admin seed

## Features

- User registration and login
- Admin authentication
- Delivery rider authentication
- Food category and menu management
- Cart and checkout flow
- COD and online payment flow support
- Order history and tracking
- Delivery assignment and status updates
- Rider earnings and payout views
- Help/support query storage

## Local Setup

1. Copy the project folder into your local web root, for example `htdocs`.
2. Create a MySQL database named `food_db`.
3. Import `db.sql` into the database.
4. Update database credentials in `config/db.php` if needed.
5. Start Apache and MySQL.
6. Open the project in the browser:

```text
http://localhost/online_food_ordering_system/
```

## Default Admin Login

- Email: `admin@gmail.com`
- Password: `admin123`

Change this password after first login.

## Important Notes

- The repository currently contains many existing local modifications. Review them before making your first GitHub commit.
- `db.sql` is the main database file to use for setup.
- PHP CLI was not available in the current terminal session, so automated syntax linting could not be completed here.

## Recommended Before GitHub Upload

- Add screenshots of the customer, admin, and delivery dashboards
- Replace sample/demo content with your own branding if needed
- Verify database credentials are safe for public upload
- Test login, checkout, and order status flow locally

## Git Commands

Use these commands after reviewing your files:

```bash
git init
git add .
git commit -m "Prepare QuickBite project for GitHub"
git branch -M main
git remote add origin <your-github-repo-url>
git push -u origin main
```

## License

This project is for academic and learning use unless you add your own license.
