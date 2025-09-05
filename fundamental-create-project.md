# Laravel
*fundamental laravel 12*

_"read documentation https://laravel.com/"_

Laravel is a web application framework with expressive, elegant syntax. A web framework provides a structure and starting point for creating your application, allowing you to focus on creating something amazing while we sweat the details.

- LARAVEL HERD tools untuk membuat laravel versi windows seperti laragon
- PHPSTRORM code editor khusus PHP
- PHP paling baru versi 8.2

*konfigurasi awal*
- install composer https://getcomposer.org/
- NodeJs https://nodejs.org/en/download update download binary
- jika menggunakan laragon ke folder laragon/www/NamaProject
- sebelum membuat project dengan laragon ada beberapa ekstensi yang harus di checklst pada laragon
klik kanan > php > extention > checklish pod.sqlite, sqlite3, zip

*install composer for windows*

open terminal
# Run as administrator...
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://php.new/install/windows/8.4'))

- install composer global
// install new
composer global require laravel/installer
// update version
composer global update laravel/installer

- create new project
laravel new example-app

npm install → install frontend tools.

npm run build → build asset buat production.

npm run dev → build asset buat development (hot reload).

php artisan serve → jalanin server Laravel.

selain itu ada cara one click command menggunakan laragon 
start all > klik kanan > quick app > laraveL
