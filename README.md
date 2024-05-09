# Docker + Apache + MariaDB + PHP

A Docker Compose equivalent to [XAMPP](https://www.apachefriends.org/), the popular PHP development environment.

## Usage

#### Project structure

The `htdocs` directory is the root of the Apache server, see the example `index.php` entry point. Place your PHP files there.

#### Start the containers

```bash
docker-compose up
```

#### Access

After starting the containers, you can access the following URLs:

- Apache Web Server: [http://localhost:8080](http://localhost:8080)
- phpMyAdmin: [http://localhost:5050](http://localhost:5050)
  - User: `root`
  - Password: `root`
- MariaDB: `localhost:3306`
  - Database: `db`
  - User: `user`
  - Password: `password`
