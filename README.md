# laravel-jwt

após baixar o projeto instale as dependencias :
$ composer install

crie o arquivo .env baseado no .env.example e altere as configurações de conexão ao banco de dados.

$ cp .env.example .env

gere a chave de aplicação :

$ php artisan key:generate

rode as migrations 

$ php artisan migrate

e escolha o segredo de seu token JWT

$ php artisan jwt:seusegredo

