<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>


## Descrição de comandos para executar o projeto 

- Instalar o composer fazendo download dele seguindo a documentação do site: **[https://getcomposer.org/download](https://getcomposer.org/download)**
- Após criar o projeto executei o mesmo abrindo o prompt de comando do windows ou terminal do windows e executar o comando: php artisan serve
- Acessar o projeto no endereço: http://localhost:8000/

Ao baixar pela primeira vez pelo github será necessário instalar todas as depêndencias. Para isso basta executar o comando abaixo:
- composer install 

Foi criado os controllers e requests com os comandos abaixo:
- php artisan make:controller HomeController

Foi criado os models com os seguintes comandos
- php artisan make:model Pessoa --seed --factory --migration
- php artisan make:model Estado --seed --factory --migration
- php artisan make:model Cidade --seed --factory --migration
- php artisan make:model Hobbie --seed --factory --migration

Para criar as tabela utilizar o comando:
- php artisan migrate

Para popular os registros de cidade, estados e hobbies utilizei o seeder do laravel. Basta dar o comando abaixo que ja está tudo configurado para criar os registros
- php artisan db:seed


