Projeto de Testes Automatizados - Demoblaze.com
Este repositório apresenta um projeto de testes automatizados com Katalon Studio desenvolvido com foco no site Demoblaze, uma loja virtual fictícia utilizada para fins educacionais.

O objetivo do projeto é demonstrar a criação e execução de casos de teste automatizados que cobrem funcionalidades críticas do sistema, simulando ações reais dos usuários, como cadastro, login, compras e navegação por categorias de produtos.

Ferramentas Utilizadas: 
- Katalon Studio
- Groovy (linguagem base do Katalon)
- Git/GitHub
- Testes realizados com interface gráfica (UI)

Objetivos do Projeto:
- Praticar a automação de testes funcionais utilizando Katalon Studio
- Validar os principais fluxos do sistema de e-commerce
- Garantir que funcionalidades essenciais estejam funcionando conforme esperado
- Exercitar boas práticas em QA, como organização dos testes e reaproveitamento de componentes

Casos de Teste Automatizados:

Código/Caso de Teste	| Descrição
- TC1 SignUp | Cadastro de novo usuário com dados válidos
- TC2 Login com credenciais válidas | Login com usuário e senha válidos (utilizando variáveis)
- TC3 Login com credenciais inválidas | Validação de mensagem de erro com usuário e senha inválidos
- TC4 Login com senha inválida | Teste de login com senha incorreta
- TC5 Logout | Validação do fluxo de logout
- TC6 Contact - Envio de mensagem	| Teste de envio de mensagem através do formulário "Contact"
- TC7 AboutUs com vídeo |	Validação da exibição do vídeo na seção "About Us"
- TC8 Compra bem-sucedida | Fluxo completo de compra com preenchimento correto dos dados
- TC9 Compra sem dados no formulário | Tentativa de compra sem preencher o formulário (validação de erro)
- TC10 Deletar produto do carrinho | Remoção de produto do carrinho de compras
- TC11 Filtro Categoria: Phones | Validação do filtro de produtos da categoria "Phones"
- TC12 Filtro Categoria: Laptops | Validação do filtro de produtos da categoria "Laptops"
- TC13 Filtro Categoria: Monitors	| Validação do filtro de produtos da categoria "Monitors"
- TC14 Lista de produtos - Botão NEXT | Teste de navegação para próxima página de produtos
- TC15 Lista de produtos - Botão PREVIOUS | Teste de navegação para página anterior de produtos
- TC16 Banners principais da Home	| Verificação de exibição dos banners principais na página inicial
- TC17 Login com credenciais válidas | Repetição do fluxo de login válido (com variações de dados)
- TC18 SignUp com usuário já existente| Tentativa de cadastro com usuário já registrado

Estrutura do Projeto:

- ├── Test Cases/
- │   ├── TC1_SignUp
- │   ├── TC2_Login_Valid_Variables
- │   ├── ...
- │   └── TC18_SignUp_UserExists
- ├── Object Repository/
- ├── Test Suites/
- ├── Reports/
- └── README.md

Considerações Finais: Este projeto foi desenvolvido com o objetivo de consolidar os conhecimentos em automação de testes manuais e funcionais com Katalon Studio, sendo uma importante etapa na minha jornada de transição para a área de Quality Assurance (QA).

Fique à vontade para explorar os testes, clonar o repositório ou entrar em contato para trocar experiências! :)
