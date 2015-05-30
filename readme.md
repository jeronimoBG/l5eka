#Curso Laravel 5 - Edukee.com

O código fonte da primeira aula se enconta no branch aula1. A cada aula novos branches serão criados.

Para instalar, após a preparação de seu ambiente (criação do virtual host e configuração da pasta raiz para o host), basta **clonar o branch** e, a partir do Terminal e estando na pasta raiz do projeto, executar `composer install`

**Importante** o arquivo .env foi enviado para o repositório, para que vc o tenha. Modifique-o para que reflita as configurações do seu banco de dados e em seguida adicione-o no .gitignore para que não seja mais enviado em commits posteriores.

## Migrations

Não se esqueça de executar as migrations. Também no Terminal, a partir da pasta raiz, executar `php artisan migrate`. Todas as tabelas serão criadas no seu banco dados.

## Seeds

Altere o arquivo /database/seeds/DatabaseSeeder.php e adicione um usuário seu. Por fim, execute `php artisan db:seed` para abastecer o DB com informações.

**Em caso de duvidas** use nosso fórum.

##Elixir
Para o uso do Livereload, que é o único recurso Elixir utilizado na aula 2, vá à pasta raiz do projeto utilizando o terminal e digite `npm install` (assume-se aqui que você tenha instalado o Node e o Npm).

Já para o [Livereload para Elixir](https://www.npmjs.com/package/laravel-elixir-livereload) basta seguir as instruções de instalação na página do módulo.

Finalmente, caso ainda não tenha o Gulp, basta executar `npm install gulp` e em seguida à instalação rodar `gulp watch`. Pronto: não será mais necessário pressionar F5 para atualizar a página (exceto em caso de erros).

## Sobre o curso

Se por acaso vc chegou aqui e não sabe do que se trata, segue o [link do curso de Laravel 5](http://www.edukee.com/pt/curso/laravel-5/turma-a/2305860968)