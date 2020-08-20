# Widesoftware - Backend challenge
Crie um microserviço que aceite solicitações RESTful onde receberá por parâmetro o nome da cidade e retorne uma sugestão de músicas de acordo com a temperatura local. Apenas o nome das músicas sugeridas já é o suficiente.

## Regras de negócio
- Se a temperatura (em celsius) estiver acima de 30 graus, sugerir músicas de categoria **Festa**.
- Caso a temperatura esteja entre 21 e 30 graus, sugerir músicas de categoria **Hip Hop**.
- Se estiver um pouco frio, entre 15 e 20 graus, sugira músicas de categoria **Clássica**.
- Agora, se estiver muito frio, abaixo de 15 graus, a sugestão é músicas de categoria **Rock**.

## Dicas
Você pode usar a API do **OpenWeatherMaps** (https://openweathermap.org) para pegar os dados de temperatura e a API do **Spotify** (https://developer.spotify.com) para pegar as música que irá sugerir.

## O que avaliaremos?
- Qualidade do código.
- Cobertura de testes do código (TDD).

## Será um diferencial
- Enviar o projeto em Docker.
- Teste de integração.

Gostaríamos também que descrevesse os detalhes da arquitetura e padrões utilizados na criação do projeto.
Não esqueça de criar a documentação da API com instruções de como executar. (README)

Criar um repositório **privado** no github e adicionar nosso usuário developers@wideti.com.br como colaborador.
