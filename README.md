# KontHub - Desafio Técnico

Bem vindos ao desafio técnico da Kontulari! O desafio que vai nos dar uma base para saber qual é seu atual nível técnico em relação a desenvolvimento full stack.

### Introdução

O desafio consiste em realizar o desenvolvimento de dois projetos, um frontend com [ReactJS](https://reactjs.org) e outro backend com [Spring Boot](https://spring.io/projects/spring-boot) que utilizem como fonte de dados para exibição a [API do GitHub](https://api.github.com).

### Descrição

O principal objetivo do desafio é conhecer e avaliar as suas habilidades de integração entre sistemas, sendo assim você deve realizar dois tipos de integração nos projetos. A primeira integração deve ser feita a partir do backend com Spring Boot comunicando-se com a API do GitHub para realizar as consultas de usuários e repositórios e disponibilizar uma API que será consumida pelo cliente frontend em ReactJS. A segunda integração deve ser feita do frontend para o backend consumindo a API criada na primeira etapa.

Você pode explorar a documentação da API do GitHub e utilizar os recursos que ela provê da forma que preferir, mas seu projeto **deve implementar** o seguinte requisito funcional:

**- Realizar uma consulta de usuário do GitHub e na sequência consultar os repositórios desse usuário para listá-los na exibição, exiba os dados que preferir de cada usuário e repositório. Caso o usuário não tenha repositórios, deve ser exibida uma mensagem adequada no frontend.**

Exemplos de consulta utilizando o usuário do Facebook:

- GET https://api.github.com/users/facebook
- GET https://api.github.com/users/facebook/repos


### Requisitos Técnicos

Para a realização do desafio, você deve utilizar o framework Spring Boot 2.7 ou superior com a linguagem de programação Java (versão 8+) ou Kotlin (versão 1.7+) e para o desenvolvimento do frontend você deve utilizar a biblioteca ReactJS na versão 18 com a linguagem JavaScript ou TypeScript. Não é necessário a utilização de banco de dados nesse desafio.

Para a integração Backend-Github você pode utilizar as bibliotecas OkHttp ou RestTemplate, mas fique livre para escolher a biblioteca de integração que preferir. Para a API de consultas do cliente você deve seguir o padrão REST.

O frontend deve ser responsivo para telas de qualquer tamanho (celular, tablet, PC), utilize as ferramentas de desenvolvimento do seu navegador para validar a responsividade. Sinta-se livre para desenvolver a interface do aplicativo web da forma que preferir (paleta de cor, biblioteca de estilo, imagens, fonte, posicionamento dos componentes), mas como sugestão você pode criar uma tela de pesquisa semelhante a do Google com um único campo de formulário para busca onde será digitado o usuário do GitHub.

O README do seu projeto deve documentar todo o processo de desenvolvimento, veja mais detalhes na sessão seguite.

Em caso de dúvida, não deixe de entrar em contato para esclarecimentos sobre o desafio.

### Envio do projeto

Antes de iniciar o desafio, crie um repositório no GitHub para armazenar os seus projetos em pastas separadas do backend e frontend (não é necessário a utilização de *monorepo*) e faça commits documentais que relatem o passo a passo do desenvolvimento, **isso também será avaliado**. Além disso o README do projeto deve conter o **passo a passo detalhado** de como fazer a execução dos projetos em ambiente local.

O repositório pode ser público ou privado, mas caso opte por criar um repositório privado, envie um convite de colaboração para o usuário [kontulari](https://github.com/kontulari) e [augustorodrigues](https://github.com/augustorodrigues) no GitHub. Não faça fork desse repositório para evitar que os concorrentes vejam o processo de desenvolvimento do seu projeto.

O link do repositório deve ser enviado para o email **comunicacao@kontulari.com.br** até o prazo limite, não havendo possibilidade de prorrogação. Você pode enviar o link logo quando criar o repositório, porém as análises se iniciam apenas após a finalização do prazo.

### Diferenciais

- Testes de unidade, de interface, etc;
- Docker.

### O que será avaliado

- Instruções detalhadas para execução em ambiente local dos seus projetos;
- Utilização do padrão REST para desenvolvimento de APIs;
- Responsividade no frontend;
- Commits documentando o processo de desenvolvimento;
- Explicação da estrutura de pastas utilizada no projeto;
- Descrição no README de como você organizou cada etapa do desenvolvimento até a sua finalização.

### Prazo

**Entrega até 08/03/2023 as 23:59.**

Commits realizados após esse prazo não serão considerados na avaliação.

### Importante saber

**O código do projeto é seu.** Nós não utilizaremos nenhum código implementado nesse desafio técnico nos projetos da Kontulari.

*Let´s code!*
