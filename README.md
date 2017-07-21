# Weather App
## Instruções de instalação
Primeramente instale as dependências. No seu terminal digite:
```
npm install
```

Em seguida, rode a aplicação digitando no seu terminal:
```
gulp
```
O projeto rodará no localhost na porta 3000.

<br/>

## Considerações
- Criei um loader improvisado que após 2 segundos ele roda a aplicação, pois não sei como executar uma função apenas após todos os requests serem executados.
- Consegui converter as distâncias para as medidas brasileiras (km, km/h e C) e também os dias da semana (esse eu fiz "na mão" mesmo), porém não consegui deixar o idioma da API em pt-BR. Portanto, as cidades ficaram sem acento (além de outros parâmetros que também ficaram em inglês)
- Acredito que tenha a API tenha mudado um pouco e agora o parâmetro de 'sensação térmica' não existe (eu particularmente não encontrei), então resolvi deixar um número fixo (19° C).
- Agradeço a oportunidade. Fico no aguardo de um feedback :D