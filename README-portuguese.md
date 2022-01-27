##Instalação

##Começo

##Iniciar

1. `yarn` or `npm install`
2. `yarn start` or `npm start`

Executando testes

`yarn test`

##Explicação

Em primeiro lugar, como comecei este projeto? Eu fiz algumas pesquisas sobre as calculadoras Casio. Não encontrei o manual da Calculadora SL-300SV, mas aprendi como funciona nos manuais de outras calculadoras Casio.

Encontrei uma calculadora antiga da Casio no escritório da minha empresa atual. Eu tenho idéias de interação (aparência e sensação).

![demo][demo-image]

[demo-image]: https://images-na.ssl-images-amazon.com/images/I/71kcP55HoEL._SX522_.jpg

[demo-image]: screenshot.png

## Implementações
## Funções

A calculadora desliga automaticamente se você não realizar nenhuma operação em 10 minutos.

`Funções de Memória`

Eu não tinha certeza sobre como armazenar dados de memória em localStorage. Seria mais problemático replicar um hardware real.

`Divisão de Código`

Esta calculadora tem algumas funções avançadas, por isso passei a maior parte do tempo na divisão de código.

Eu dividi as chaves por tipos como `main, basic, memory, math, number`.

Eu escrevi `keys.js` e depois coloquei combinações de teclas em `layout.js`, todos os arrays em `layout` são rows.

Eu construí processadores para cada key type. Eles se parecem com Redux -> Redutores.

##Ideias Futuras

`Key Codes`

Você não precisa clicar na tecla. Se você pressionar a tecla do seu teclado, estamos acionando essa funcionalidade com animação.

