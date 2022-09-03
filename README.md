# Book Tracking

# Sobre o projeto
Aplicativo single-page application(SPA) que permite aos usuários manter uma lista de alguns de seus livros favoritos. Livros podem ser categorizados pelo usuário em três categorias - "leu", "deseja ler" ou "está lendo no momento". O aplicativo mantém o armazenamento na categoria local e remotamente e também permite que os usuários pesquisem novos livros na API Udacity Books. Depois que um livro é encontrado na tela de pesquisa, os usuários podem adicioná-lo à estante desejada.

## Opções de manipulação implantadas.
![Listagem dos livros](https://github.com/klvosantos/assets/blob/main/booktracking/manipulacao%20dos%20livros.jpg?raw=true) 

## Mecanismo de busca.
![Mecanismo de busca](https://github.com/klvosantos/assets/blob/main/booktracking/mecanismo%20de%20busca.jpg?raw=true) 

## Instruções.
Para executar este aplicativo, primeiro você precisa baixar os arquivos ou clonar este repositório para começar. O aplicativo é construído usando a biblioteca React, então você também precisará executar npm install no seu terminal enquanto estiver no diretório do projeto para instalar todas as dependências do projeto. Finalmente, você precisará executar npm start no diretório do projeto para iniciar o servidor.
## Comandos necessarios:
    - npm install
    - npm start
    - execução padrão: http://localhost:3000/
    
## Udacity Books API
O aplicativo busca dados da API Udacity Books para pesquisar novos livros, o que significa que o acesso à Internet é necessário para que todas as funcionalidades funcionem corretamente. Esse servidor de back-end é necessário para que o projeto seja executado corretamente, mas nenhuma instalação ou alteração adicional precisa ser feita no código. O arquivo BooksAPI.js contém todos os métodos que funcionam com esta API, bem como seu endereço atual.

A API de back-end usa um conjunto fixo de resultados de pesquisa em cache e é limitada a um conjunto específico de termos de pesquisa como:

'Android', 'Art', 'Artificial Intelligence', 'Astronomy', 'Austen', 'Baseball', 'Basketball', 'Bhagat', 'Biography', 'Brief', 'Business', 'Camus', 'Cervantes', 'Christie', 'Classics', 'Comics', 'Cook', 'Cricket', 'Cycling', 'Desai', 'Design', 'Development', 'Digital Marketing', 'Drama', 'Drawing', 'Dumas', 'Education', 'Everything', 'Fantasy', 'Film', 'Finance', 'First', 'Fitness', 'Football', 'Future', 'Games', 'Gandhi', 'Homer', 'Horror', 'Hugo', 'Ibsen', 'Journey', 'Kafka', 'King', 'Lahiri', 'Larsson', 'Learn', 'Literary Fiction', 'Make', 'Manage', 'Marquez', 'Money', 'Mystery', 'Negotiate', 'Painting', 'Philosophy', 'Photography', 'Poetry', 'Production', 'Programming', 'React', 'Redux', 'River', 'Robotics', 'Rowling', 'Satire', 'Science Fiction', 'Shakespeare', 'Singh', 'Swimming', 'Tale', 'Thrun', 'Time', 'Tolstoy', 'Travel', 'Ultimate', 'Virtual Reality', 'Web Development', 'iOS'


Mais informações:

https://www.udacity.com/

https://github.com/udacity
