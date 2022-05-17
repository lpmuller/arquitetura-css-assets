# FRUTA & FRUTO 

Através do curso de [“Arquitetura CSS: descomplicando os problemas”](https://cursos.alura.com.br/course/arquitetura-css) da Alura, com o instrutor [Matheus Castiglioni](https://cursos.alura.com.br/user/matheushcastiglioni) (**[Linkedin](https://www.linkedin.com/in/matheus-castiglioni-7aa105114/) / [Github](https://github.com/mahenrique94))**, foi desenvolvida a página de receitas **Fruta & Fruto**, incluindo :

- cabeçalho;
- banner;
- seção *Sobre*;
- listagem de receitas;
- seção *Quem somos*, com as pessoas envolvidas na empresa;
- rodapé com informação de contatos

Através das medias queries, o site é responsivo, se adaptando às alterações de tela. Com isso, também será possível acessá-lo de maneira agradável mesmo em um celular, tablet ou desktop. Para o desenvolvimento desse site foram utilizadas boas práticas de CSS, como a metodologia ***Atomic Design***, com a qual o projeto foi organizado e arquitetado de maneira mais eficiente e de fácil manutenção.

Além disso, foram usadas metodologias de nomenclatura das classes, de modo a manter um padrão. Desta forma, outros desenvolvedores que utilizarem o código terão mais facilidade para entendê-lo e modificá-lo.

### Projeto Inicial

[](https://github.com/alura-cursos/arquitetura-css/archive/assets.zip)

### Protótipo

O layout de base está disponível no link: ‣

## Atomic Design

![https://miro.medium.com/max/1400/1*-5eD_eAuSK1ZBnLQyQGVCQ.png](https://miro.medium.com/max/1400/1*-5eD_eAuSK1ZBnLQyQGVCQ.png)

Para este projeto, foi criado um arquivo CSS para cada elemento da página, utilizando a metodologia **Atomic Design**, que consiste, basicamente, em um modelo de organizar os componentes, pastas e a estrutura do nosso CSS a partir do princípio de *átomos*, onde um átomo é toda tag HTML (cada button, input, label, etc). Juntos esses elementos, ou átomos, formam uma "molécula" - como por exemplo, a molécula de um formulário de pesquisa. A junção de várias moléculas, por sua vez, forma os "organismos". No exemplo, juntando a molécula referente ao formulário de pesquisa com a molécula referente a um menu (que também tem seus átomos, como a imagem e os links), temos um organismo que representa o cabeçalho de uma página.

Unindo vários organismos, chegamos aos "templates". No exemplo, temos o organismo referente ao cabeçalho, ao banner e à descrição, e que juntos formam um template. Por fim, o template dá lugar a uma página.

## Metodologia BEM

A falta de um padrão definido de nomenclatura nos títulos das classes não é recomendado, pois  dificulta reconhecermos as classes já existentes ou criarmos novas. Para resolver esse problema, foi utilizada no projeto a metodologia reconhecida pela sigla BEM, de *Block Element Modifier* - ou seja, "bloco, elemento e modificador", da seguinte forma:

```
bloco
bloco__elemento
bloco--modificador
bloco__elemento--modificador
```