# HTML5_CSS3_DIO

## Aprendendo a utilizar HTML5 e CSS3
&nbsp;

> Primeira Aula
* Tags de estrutura básica de um documento HTML

 < !DOCTYPE html>
 < html>
 < head>
 < body>
 < title>
&nbsp;
* Tags HTML estruturais

< header>
< footer>
&nbsp;
* Tags HTML de título

< h1, h2,...h6>
&nbsp;
* Tags HTML de texto

< p>
< b>
< i>
< br/>
< hr/>

&nbsp;
> Segunda Aula
* Tags HTML estruturais

< nav>
< section>
&nbsp;

* Tags HTML de listas

< ul>
< li>
&nbsp;

* Tags HTML de multimídia

< img>

&nbsp;
> Terceira Aula
* Tags HTML estruturais

< div>
&nbsp;

* Tag de link HTML

< a> - Atributos href e target

&nbsp;
> Quarta Aula
* Tag de link HTML

< a> - Atributos href com mascara de email e telefone

&nbsp;
> Quinta Aula
* Introdução ao CSS
* Informações sobre o CSS3
* Criação de arquivo style para começar a estilizar o HTML

* Elemento HTML

< link> - especificar relação entre documento atual e um recurso externo.
Elemento utilizado para vincular as folhas de estilo.
Categoria de conteúdo: Metadata content.

&nbsp;
> Sexta Aula
* Inserindo estilo ao HTML utilizando CSS3

Utilizando o CSS podemos selecionar qualquer elemento do HTML e alterar seus estilos e formatação (body, h1, h2, footer,etc)


![Sintaxe CSS](img/sintaxe_css.png)

**Seletor (Selector)**

O nome do elemento HTML no começo do conjunto de regras. Ele seleciona o(s) elemento(s) a serem estilizados (nesse caso, elementos < p>). Para dar estilo a um outro elemento, é só mudar o seletor.

**Declaração (Declaration)**

Uma regra simples como color: red; especificando quais das propriedades do elemento você quer estilizar.

**Propriedades (Property)**

Forma pela qual você estiliza um elemento HTML. (Nesse caso, color é uma propriedade dos elementos < p>.) Em CSS, você escolhe quais propriedades você deseja afetar com sua regra.

**Valor da propriedade (Property value)**

À direita da propriedade, depois dos dois pontos, nós temos o valor de propriedade, que escolhe uma dentre muitas aparências possíveis para uma determinada propriedade (há muitos valores color(cor) além do red(vermelho)).


## Propriedades CSS:

**Font-Family** - Selecionar tipo de fonte;

**Font-size** - Selecionar tamanho de fonte;

**Margin-(top/left/right/bottom** - Selecionar tamanho da margem dos elementos;

**Color** - Selecionar cor da fonte;

**Background** - Selecionar cor da pagina;

&nbsp;
> Setima Aula

* Aplicando estilo e formatação através das classes.


Criar classe no elemento HTML class="elemento" que se deseja alterar com CSS, e no arquivo CSS
deve indicar qual elemento deseja alterar atraves do "."

Exemplo: .elemento{color: blue;}
