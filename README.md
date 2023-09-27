# TesteCaixaBranca
## Erros indentificados

Dentro do código em questão, utilizando os princípios de qualidade e testes de software, é possível observar alguns possíveis erros e condutas opostas as boas normas de programação.

![operacao](img2.png)

1° - Ao falhar na função "Try" seria recomendável que o código imprimisse uma mensagem do erro ocorrido, facilitando manutenções e entendimento de problemas. Isso pode ser resolvido utilizando a função "catch" do Java.

2° - A chamada da função SQL para verificar o login do usuário feita por uma concatenação de String's não é a maneira mais recomendada, assim tendo baixos índices de confiabilidade no código.

3° - A estruturação e organização do código não está de forma adequada, dificultando a leitura e compreensão do mesmo.

4° - O baixo número de comentários dificulta o entender do leitor que não desenvolveu o código. Atrapalhando uma possível manutenção feita por um colega de equipe ou os próprios testes de qualidade e aceitação

## Última atualização 27/09/23
