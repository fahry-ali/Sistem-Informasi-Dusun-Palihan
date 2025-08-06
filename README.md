# Sistem Informasi Dusun Palihan

<div align="center">
  
[![Laravel][Laravel.com]][Laravel-url]
[![Bootstrap][Bootstrap.com]][Bootstrap-url]
[![PHP][PHP.com]][PHP-url]
[![MySQL][MySQL.com]][MySQL-url]
[![Vite][Vite.dev]][Vite-url]

[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[PHP.com]: https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white
[PHP-url]: https://www.php.net
[MySQL.com]: https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white
[MySQL-url]: https://www.mysql.com
[Vite.dev]: https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white
[Vite-url]: https://vitejs.dev

</div>

## Overview
This is a web-based village information system built with Laravel for Dusun Palihan. The system provides comprehensive features for managing village information, news, announcements, and various administrative functions.

## Tech Stack
- PHP 8.x
- Laravel Framework
- MySQL Database
- Bootstrap
- Vite (Frontend Build Tool)

## Project Structure

### Core Directories
- `app/` - Contains the core code of the application
  - `Console/` - Console commands and scheduled tasks
  - `Http/` - Controllers, Middleware, and request handling
  - `Models/` - Eloquent models representing database tables
  - `Policies/` - Authorization policies
  - `Providers/` - Service providers

### Key Models
- `Agama.php` - Religion management
- `Anggaran.php` - Budget management
- `Announcement.php` - Village announcements
- `Berita.php` - News management
- `Gallery.php` - Image gallery
- `PerangkatDesa.php` - Village officials
- `Umkm.php` - Small business (UMKM) management
- `User.php` - User management
- `Wilayah.php` - Regional management

### Frontend
- `resources/`
  - `views/` - Blade template files
    - `admin/` - Admin panel views
    - `auth/` - Authentication views
    - `layouts/` - Layout templates
    - `partials/` - Reusable view components
  - `css/`, `js/`, `sass/` - Frontend assets

### Configuration
- `config/` - Application configuration files
- `database/` - Database migrations and seeders
- `routes/` - Application routes
  - `web.php` - Web routes
  - `api.php` - API routes

### Public Assets
- `public/`
  - `admin/assets/` - Admin panel assets
  - `assets/` - Public frontend assets

## Features
1. User Management System
2. News and Announcements
3. Village Gallery
4. UMKM (Small Business) Management
5. Village Officials Directory
6. Contact Information
7. Village History
8. Village Map
9. Service Information
10. Budget Transparency

## Installation

1. Clone the repository:
```bash
git clone https://github.com/fahry-ali/Sistem-Informasi-Dusun-Palihan.git
```

2. Install PHP dependencies:
```bash
composer install
```

3. Install JavaScript dependencies:
```bash
npm install
```

4. Create environment file:
```bash
cp .env.example .env
```

5. Generate application key:
```bash
php artisan key:generate
```

6. Configure your database in `.env` file

7. Run database migrations:
```bash
php artisan migrate
```

8. Build frontend assets:
```bash
npm run build
```

9. Start the development server:
```bash
php artisan serve
```

## Development
- For development, run:
```bash
npm run dev
```
- For production build:
```bash
npm run build
```

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License
This project is licensed under the MIT License.

## Author
- Fahry Ali
- GitHub: [@fahry-ali](https://github.com/fahry-ali)

## Acknowledgments
Special thanks to all contributors and the Dusun Palihan community for their support in developing this system.
