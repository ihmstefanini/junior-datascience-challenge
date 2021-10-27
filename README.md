# 1. Bem-vindo ao repositório do Desafio de Dados da ihm stefanini

Esse repositório contém todas as informações e diretrizes necessárias para que você possa realizar o nosso desafio, como parte integrante do nosso processo de avaliação dos potenciais candidatos as vagas de cientista de dados júnior.

Sugerimos que você **leia com bastante atenção** a todos as etapas, critérios e requisitos a serem cumpridos no desafio.

## 1.1 Objetivo do desafio

Avaliar de forma qualitativa quais são os pontos fortes e os pontos de gaps do candidato a vaga.
A intenção do desafio não é de carácter eliminatório, mas sim uma forma mais pragmática de prover para o RH e os líderes da ihm informações sobre a experiência que você já tem na área. 

## 1.2 Etapas do desafio

O desafio se divide nas seguintes etapas:

1. Recebimento do link de acesso ao repositório (considerando que já cadastramos e liberamos o seu acesso previamente)
1. Recebimento do link para baixar o dataset
1. Desenvolvimento do desafio (analisar, explorar e modelar os dados)
1. Criar uma apresentação em formato PowerPoint
1. Submeter o(s) código(s) e o arquivo da apresentação ao mesmo repositório*(maiores detalhes vide seção 1.6)
1. Informar pelo email eduardo.magalhaes@ihm.com.br que você concluiu o desafio
1. Iremos combinar uma data da sua apresentação (a ser realizada remotamente via Microsoft Teams)
1. Realizar a apresentação final para os stackholders da ihm stefanini
 
## 1.3 Critérios de avaliação mais relevantes

Atenção! Pois os critérios são bem mais voltados para as soft skills do que as hard skills. Apesar de as hard skills serem base para que você possa gerar os *outcomes* necessários para demonstrar suas habilidades.

Iremos nos preocupar muito mais com:
1. Nível de organização e sequência lógica de exploração dos dados
1. Maturidade no correto entendimento dos conceitos fundamentais em ciência de dados e o julgamento apropriado de como você emprega as técnicas de exploração e modelagem de dados
1. Maturidade na codificação (organização do código, comentários e "explicabilidade")
1. Skills de comunicação e apresentação
1. Por último e não menos importante, seus skills em Data Viz, ou seja, a qualidade e a clareza dos seus gráficos, bem como a facilidade de interpretação

## 1.4 Critérios que não preocupamos tanto nessa etapa

Performance de modelo. É isso mesmo que você está lendo! Parece contraintuitivo, mas não estamos preocupado em você conseguir fazer um super modelo com mega performance, até porque esse modelo não será colocado em produção, então, não há necessidade de se preocupar demais com isso e gastar todo o tempo do desafio com isso. 

Sim, esperamos que você faça um modelo razoável, mas não "frite" com isso. Lembre dos principais critérios que estamos nos preocupando mais em te avaliar, conforme descrito no item anterior.

## 1.5 Requisitos mínimos

Para realizar o desafio, você precisa cumprir os seguintes requisitos:


1. Linguagem de programação 100% Python
1. Escolha da IDE: livre escolha. Pode usar Jupyter, VSCode, Pycharm...
1. Baixar os dados pelo link enviado no seu email e que também estão contidos na seção 2.2
1. Apresentação em formato ppt


## 1.6 Prazos e Submissão final

1. Utilizar o git para clonar e subir a versão final do(s) seu(s) código(s) em formato *.py e/ou *.ipynb;
1. Utilizar o git também para enviar o arquivo da sua apresentação;
1. Submeter em uma nova *branch* que segue o seguinte padrão: junior-datascientist-challenge-xxxxxxxx (onde x representa o seu nome e sobrenome juntos, sem acento e com caracteres minúsculos). Exemplo: junior-datascientist-challenge-eduardomagalhaes
1. Prazo inicial de **até 03 semanas**, a contar a partir da data em que você recebeu o email de convocação para o desafio;
1. A data final da apresentação será combinada via email com o time ihm stefanini.

## 1.7 FAQ

1. Pode usar Google, Kaggle, Stackoverflow à vontade, pois é assim que funciona na vida real!
2. Será permitido tirar dúvidas com as pessoas da ihm stefanini, apenas no que concerne ao entendimento da dinâmica do desafio. Não é permitido tirar dúvidas técnicas. O contato será via email eduardo.magalhaes@ihm.com.br

##--------------------------------------------------------------------------------------------------------------

# 2. Maiores Detalhes sobre o problema que você irá resolver no desafio
Nessa seção iremos trazer mais informações sobre o problema de negócio que você resolverá, os objetivos de negócio, bem como o que os tomadores de decisão estão esperando dessa solução.

## 2.1 Descrevendo o cenário e o problema

Imagine que você trabalha numa empresa que fornece serviços de ciência de dados para indústria e que você é o principal cientista de dados desse time. Considere também que é a primeira vez que você e sua empresa estão encarando o desafio proposto por esse cliente. 

Ou seja, você conhece pouco do processo produtivo dele, de como ele toma as decisões acerca do problema atualmente e tudo mais. Porém, por sua "sorte" o cliente é bem camarada e está topando um certo risco de o projeto dar errado, ou seja, você até não conseguir fazer um bom modelo, mas ele precisa acreditar que vale a pena explorar mais o problema e até mesmo explorar outras demandas caso essa não dê certo.

Pois então, veja que você a oportunidade em mãos de mostrar para esse cliente que a ciência de dados é **potencialmente** viável para o negócio dele.

Dito tudo isso, te damos uma dica: preocupe em avaliar bem os dados que você tem em mãos, explicar bem as escolhas das aplicações das técnicas de exploração dos dados e capriche numa apresentação impactante, de forma que o seu cliente que é leigo, possa entender os gráficos e o contexto que você quer vender: **há um bom potencial preditivo nesses dados, veja sô!**

Portanto, reforçando novamente: se preocupe menos com a performance do modelo.

Mais detalhes sobre o cliente: é uma mineradora e o seu cliente de contato direto e quem está comprando o projeto piloto da sua empresa tem uma leve noção de análise de dados.

## 2.2 O dataset

O dataset do problema a ser analisado se encontra na plataforma Kaggle, [nesse link](https://www.kaggle.com/edumagalhaes/quality-prediction-in-a-mining-process).

Lá você já encontrará toda a explicação mínima necessária para executar o desafio.

## 2.3 Considerações finais

Busque:

1. Formular suas hipóteses de exploração dos dados e documentá-las (livre escolha de onde achar melhor)
2. Descrever o que está vendo nas séries temporais? Há tendência/sazonalidade? Tem muito ou pouco ruído? E os outliers?
3. Descrever minimamente por que está técnica A ou B para explorar os dados. Exemplo, usei o PCA porque acredito ser interessante por causa de xxxx e esperava ver yyyyy
4. Descreva porquê e como escolheu as *features*
5. Comente porque está aplicando o modelo/algoritmo x e como está representando os dados para o modelo.
6. Comente como chegou na performance final do modelo e porque acredita que há potencial de explorarmos mais esses dados? 

## 2.4 Agradecimentos e dúvidas

Agradecemos o seu interesse de participar no desafio e qualquer dúvida, entre em contato pelo email com eduardo.magalhaes@ihm.com.br
