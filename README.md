# API_REST_Login
Por trás de todos os aplicativos da Web ou móveis, há um ótimo back-end. Para um desenvolvedor moderno de pilha completa ou desenvolvedor de back-end, é necessário saber como criar uma API REST escalável do Node.js. para seu aplicativo. 

O que é REST
REST é um acrônimo de Representational State Transfer,  que é uma arquitetura baseada na Web e usa o protocolo HTTP. Ele acessa e manipula a operação dos dados usando a operação sem estado.

Abaixo estão os cinco métodos HTTP mais comuns usados ​​pelos desenvolvedores para criar uma API REST

GET:  usado para buscar os recursos do banco de dados
POST:  usado para criar os novos recursos no banco de dados
PUT:  usado para atualizar / modificar os recursos no banco de dados
DELETE:  usado para excluir os recursos do banco de dados
PATCH:  Principalmente se comporta da mesma forma que PUT. Depende totalmente dos desenvolvedores como ele / ela deseja criar a API REST
Além dos cinco métodos de HTTP acima, também existem muitos métodos usados ​​ao criar APIs REST escalonáveis ​​node.js. 

Como estruturar a API REST escalável do Node.js.
Depende totalmente dos desenvolvedores individuais, de um grupo de desenvolvedores ou organizações, de como eles desejam estruturar sua API. Neste tutorial, usarei a arquitetura MVC mais famosa para criar nossa API REST node.js. Mas há muitos desenvolvedores ou comunidades que gostam de criar sua API com base no recurso do aplicativo.

O que é arquitetura MVC
A arquitetura MVC é um dos padrões de arquitetura mais famosos no desenvolvimento da web. Na arquitetura MVC, dividimos nosso aplicativo em Model, View e Controller. No modelo, escrevemos todas as consultas relacionadas ao banco de dados. No controlador, escrevemos sobre a lógica. Na visão, escrevemos a interface do usuário e como exibir os dados.

Mas estenderemos isso um pouco e adicionaremos mais alguns diretórios como Rotas, Serviços e Middlewares. Neste tutorial, escreveremos toda a nossa lógica de negócios na pasta services e depois a usaremos em nosso controlador. É uma prática recomendada manter toda a lógica de negócios separada dos controladores.


Express.js:   é um framework famoso e amplamente usado pelo node.js. para desenvolver o aplicativo.
Mongoose:  é um ORM do MongoDB que fornece sintaxe fácil de usar para consultar os dados do banco de dados.
body-parser:  é usado para analisar toda a solicitação que vem no aplicativo.
babel-cli:  é usado para tornar nosso código ES6 do aplicativo na versão compatível com versões anteriores do javascript.
webpack:  é usado para agrupar os arquivos javascript para a produção.
nodemon:  é usado para iniciar nosso servidor toda vez que houver alguma alteração no código. É apenas para o propósito de desenvolvimento que é por isso que o instalamos nas devDependencies.
