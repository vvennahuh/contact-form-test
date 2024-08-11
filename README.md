# contact-form-test

## 環境構築
- Dockerビルド
1.git clone git@github.com:coachtech-material/laravel-docker-template.git
2.docker-compose up -d --build

- Laravel環境構築
1.docker-compose exec php bash
2.composer install
3. .env.exampleファイルから.env作成。環境変数の変更
（DB_DATABASE=laravel_db
DB_USERNAME=laravel_user
DB_PASSWORD=laravel_pass）
4.php artisan key:generate
5.php artisan migrate


## 使用技術(実行環境)
- PHP 3.8
- Laravel 8.0
- Mysql 8.0.26

## ER図


## URL
- 開発環境
- http://localhost/
- 開発環境2
- http://localhost/login
- phpMyadmin:
- http://localhost:8080/
# Re-cotact-form-test
