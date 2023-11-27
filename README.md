# Desafio
    - Ultizando todos os conhecimentos que aprendemos em aula,  
      agora crie o seu blog sozinho, e ele será um blog dos livros
      que leu esse ano, e nele você deverá colocar as seguintes informações:

      1: Titulo do livro;
      2: Autor do livro;
      3: Nota que você deu;
      4: Descrição do livro;

## Resolução
    - Iniciei um novo projeto com:
       
       $ rails new blog

    - Gerei a Home com o código:

       $ rails generate controller home index
    
    - Alterei a rota para que a page home fosse a pagina principal.
       comentando o get 'home/index' e adicionando 
       o root 'home#index'
    
    - Por fim adicionei os itens solicitado no desafio.
    
       1: Titulo do livro;
       2: Autor do livro;
       3: Nota que você deu;
       4: Descrição do livro;
