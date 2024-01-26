# KNN.ADAtech
## Apresentação do projeto:
Este projeto vem da proposta do professor Théo Carvalho do módulo de Lógica de programação II no curso Data Science do
programa Santander Coders 2023.2 em parceria com a ADA tech. Consiste no desenvolvimento de um modelo K-Nearest Neighbors
utilizando python sem o auxílio de ferramentas importadas de outras bibliotecas

## Contextualização
Os dados do nosso projeto são referentes ao cadastro de clientes de uma empresa de investimentos com suas respectivas carteira de investimentos, que indica se esse cliente tem o perfil de investidor Conservador, Moderado ou Agressivo. O nosso intuito é, a partir do investimento de alguns clientes que já tem um perfil definido, estimar esse perfil para aqueles que ainda não estão classificado, afim de oferecer novos produtos que sejam mais adequados a eles.

Os dados do projeto seguem o seguinte padrão:

[CPF: INT, Perfil Do Investidor: STRING, Carteira de Investimento: TUPLA]

### Regras
    Se você precisar de uma função para computar algo crie ela
    Não é permitido usar nenhum módulo externo como numpy e math
    Use apenas os objetos e fluxos visto até o momento no curso
    Se você tiver dificuldade de trabalhar com mais de 2 dimensões, pode utilizar apenas os dois primeiros valores de cada tupla
    O objetivo principal desse projeto não é encontrar o modelo de knn mais otimizado, mas sim você conseguir criar um modelo de KNN,
    independente se ele é o melhor ou não
    Não precisa se preocupar com a normalização das dimensões.