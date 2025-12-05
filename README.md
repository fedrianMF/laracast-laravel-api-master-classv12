# Laravel API Master Class (Updated to Laravel 12)

This project is an update to the [Laravel API Master Class](https://laracasts.com/series/laravel-api-master-class) by Jeremy McPeak, adapted for Laravel 12.

## Development Setup

1. **Install dependencies:**
   ```bash
   composer install
   npm install
   ```

2. **Setup environment:**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

3. **Run migrations:**
   ```bash
   php artisan migrate
   ```

4. **Start development server:**
   ```bash
   npm run dev
   # In a separate terminal:
   php artisan serve
   ```
