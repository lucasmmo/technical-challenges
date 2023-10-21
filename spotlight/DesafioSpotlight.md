# Desafio Técnico: Simulação de Interseção de Trânsito e Servidor HTTP com API RESTful em Go usando Docker

## Introdução

Bem-vindo ao nosso desafio técnico em Go! Neste desafio, você será responsável por criar uma simulação de uma interseção de trânsito, com foco principal nos semáforos. Além disso, você também deve desenvolver um servidor HTTP que ofereça uma API RESTful, contendo um endpoint que retorna os status dos semáforos em tempo real. Este desafio irá testar suas habilidades em desenvolvimento de software, arquitetura de sistemas e trabalho com APIs RESTful usando a linguagem de programação Go, além de demonstrar seu conhecimento em Docker.

## Descrição do Desafio

### Parte 1: Simulação da Interseção de Trânsito

Você deve criar uma simulação de uma interseção de trânsito que inclui semáforos para diferentes direções. A simulação deve:

- Ter no mínimo dois semáforos para direções diferentes.
- Implementar lógica para alternar os semáforos entre os estados de verde, amarelo e vermelho.

### Parte 2: Servidor HTTP com API RESTful

Em paralelo com a simulação da interseção de trânsito, você deve criar um servidor HTTP que forneça uma API RESTful. O servidor deve:

- Ter um endpoint REST que retorna os status dos semáforos em tempo real.
- Aceitar requisições GET nesse endpoint para fornecer informações sobre os semáforos, como a direção atual e o tempo restante em cada estado (verde, amarelo, vermelho).

### Parte 3: Dockerização da Aplicação

- Dockerize sua aplicação Go e a interseção de trânsito.
- Forneça um arquivo `Dockerfile` e, se necessário, um `docker-compose.yml` para facilitar a execução da aplicação em um ambiente Dockerizado.

## Requisitos Técnicos

- Use a linguagem de programação Go para desenvolver a solução.
- Utilize boas práticas de programação e padrões de projeto em Go.
- Forneça instruções claras sobre como executar sua aplicação em um ambiente Dockerizado.
- Use controle de versão Git e compartilhe seu código em um repositório público no GitHub ou GitLab.
- Documente qualquer suposição que você fizer durante o desenvolvimento.

## Como Participar

1. Faça um fork deste repositório.
2. Desenvolva a solução para o desafio em Go.
3. Documente seu trabalho no arquivo `README.md` explicando sua solução, como executar sua aplicação em um ambiente Dockerizado e como usar a API RESTful.
4. Forneça o arquivo `Dockerfile` e, se necessário, um `docker-compose.yml`.
5. Quando terminar, compartilhe o link para o seu repositório no GitHub ou GitLab.

## Critérios de Avaliação

- **Funcionalidade**: A simulação da interseção de trânsito deve funcionar corretamente, alternando os semáforos de acordo com a lógica implementada. O servidor HTTP em Go deve servir a API RESTful de forma precisa e eficiente.

- **Organização do Código em Go**: Avaliaremos a estrutura do seu código em Go, o uso de boas práticas de programação, modularidade e legibilidade específicas para a linguagem Go.

- **Documentação em Go e Docker**: Sua documentação em Go deve ser clara e compreensível. Deve incluir instruções claras sobre como executar sua aplicação em um ambiente Dockerizado e como usar a API RESTful. A documentação Docker também deve ser clara e indicar como construir e executar o contêiner Docker.

- **Controle de Versão com Git**: Seu trabalho em Go deve ser versionado usando Git. Avaliaremos seus commits para entender sua jornada de desenvolvimento.

- **Dockerização**: A aplicação deve ser corretamente dockerizada, seguindo as melhores práticas do Docker e facilitando a execução em diferentes ambientes.

- **Criatividade em Go**: Se você tiver ideias adicionais ou recursos extras para melhorar a simulação ou a API em Go, ficaremos felizes em vê-los!

## Conclusão

Este desafio foi criado para testar suas habilidades técnicas e criatividade em Go, bem como sua habilidade em Dockerizar aplicações. Lembre-se de que não existe uma única solução correta - queremos ver como você aborda os problemas e desenvolve soluções inovadoras usando a linguagem Go e Docker.

Boa sorte! Estamos ansiosos para ver o que você vai criar em Go e Docker. Se tiver alguma dúvida, não hesite em nos contatar.
