# Installation Process
The Doctor appointment application is a web-based platform developed using the Laravel framework that allows patients to schedule appointments with doctors online. The application is designed to simplify the process of booking appointments for patients and to improve the overall experience of visiting a doctor.

### Clone
```
git clone https://github.com/wishtree-hkumar/demo-app.git
```

### Change directory
```
cd demo-app
```

### Create .env
```
cp .env.example .env
```

### Install vedor
```
composer install
```

### Generate app key
```
php artisan key:generate
```

### Create database & set credetial in .env
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=test_app
DB_USERNAME=root
DB_PASSWORD=
```

### Run migration
```
php artisan migrate
```

### Run seeder for doctor data
```
php artisan db:seed
```

### Run project on your local
```
php artisan serve
```