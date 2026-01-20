# Curso HTML e CSS: Ambientes de Desenvolvimento, Estrutura de Arquivos e Tags

## 1. O Editor de Código VSCode

### 1.1. Apresentação
- O curso ensinará como transformar código HTML em página web.
- Ensinará onde serão utilizadas as páginas Web.
- Ensinará onde serão escritos os arquivos HTML e CSS.
- Ensinará para que serve o HTML e o CSS.

### 1.2. Criando um Arquivo
- Criar um código HTML e CSS é como criar um arquivo de texto no Doc/Docx.
- A diferença, é que no Doc existem recursos visuais que auxiliam.
- Para criar um Título, por exemplo, existe um recurso específico no Doc.
- Da mesma forma são para parágrafos, imagens e quebra de linhas.
- No HTML, demarcamos estas formatações utilizando as Tags.
- Arquivos HTML têm a extensão ".html", que são lidas pelos Navegadores.
- O código HTML é escrito em Editores de Código, ferramentas específicas.

### 1.3. Instalando o VSCode
- Um Editor de Código muito utilizado pelos é o Visual Studio Code.
- É possível baixá-lo para os sistemas Windows, Linux e MacOS.
- Os projetos HTML geralmente possuem muitos arquivos para editar.
- Por isso, usam-se pastas para armazená-los e organizá-los.
- O primeiro arquivo HTML usa por padrão o nome "index.html".
- Este nome é reconhecido por várias tecnologias e frameworks. 

## 2. Documentação e HTML

### 2.1. Documentação e Estrutura Básica do HTML
- Sempre recorremos a um manual quando queremos aprender alguma coisa nova.
- Isso também inclui linguagens, como HTML, e outras tecnologias em TI.
- O HTML também tem os seus próprios manuais, como o W3School.
- O HTML (HyperText Markup Language), é uma linguagem de marcação.
- Ela é utilizada para marcar os textos que por ela podem ser formatados.
- Para fazer estas marcações, o HTML faz o uso de Tags.
- Através das Tags HTML, são definidas as estruturas das Páginas Web.
- Partes do texto são rotuladas como títulos, parágrafos, links, etc.
- A tag <!DOCTYPE html> identifica o uso da versão 5 do HTML.
- A tag <html> é a raiz, que engloba todas as outras tags HTML.
- A tag <head> contém metainformações e metatags a respeito da página HTML.
- A metatag <title> em <head> dá um título da página na aba do navegador.

### 2.3. Criando o corpo da Página
- A tag <body> define o corpo do documento, onde o conteúdo é visível.
- A tag <h1> exibe dentro do <body> o texto na forma de um título.
- A tag <p> serve para englobar um trecho de texto em um parágrafo.
- As tags ajudam o navegador a entender o que uma Página Web é.
- A tag <img> serve para inserir uma imagem no conteúdo da Página.
- A <img> é uma tag única, porque ela não precisa envolver uma imagem.
- Geralmente as tags <img> fazem referência a um endereço específico.
- Estas referências são passadas para o atributo "href" de <img>.
- O endereço refernciado pode ser uma url ou um caminho de arquivo.
- No <body> existe algumas informações que são invisíveis no conteúdo.
- O atributo "alt" da tag <img> oferece uma descrição para a imagem.
- O "alt" não muda o conteúdo, exceto se a imagem quebrar.
	- Não podendo exibir a imagem, a <img> exibe o texto do "alt".
- O texto no "alt" também serve para questões de acessibilidade.

### 2.4. Quirks Mode e Live Server
- A opção "Inspecionar" do navegador permite visualizar o HTML de qualquer site.
- A ferramente que permite esta visualização de HTML chama-se DevTools.
- A DevTools também pode detectar se um HTML está em Modo Quirks.
- O Modo Quirks indica um HTML em não conformidade com os padrões HTML5.
- O ideal é que o HTML seja sempre ajustado para que não fique neste modo.
- Os ajustes no HTML podem demandar que a tela seja atualizada várias vezes.
- Uma extensão no VSCode atualiza a automaticamente uma página HTML atualizada.
- A extensão Live Server faz esta atualização assim que o arquivo HTML é salvo.

## 3. Layout e Tags Semânticas

### 3.1. Projeto no Figma
- Geralmente o desenvolvimento das Páginas Web passa por dois profissionais.
- Um deles é responsável por desenhar a Página e dizer o que ela irá ter.
- O outro é o desenvolvedor, que faz a codificação da página com o HTML.
- A este desenho da página a ser codificada, damos o nome de Design.
- Dentro do Design da Página, é definido um Layout base para o código.
- Uma das ferramentas de design mais utilizadas pelos designers é o Figma.
- Os Designs são estudados e pensados para prover uma boa experiência.
- Cada elemento desenhado possui informações importantes para a codificação.
	- Altura, largura, cor, borda, alinhamento, posicionamento, fonte, etc.
- O HTML é usado para estruturar todo o layout da Página conforme o Design.
- O CSS é utilizado para dar à Página a estilização fornecida pelo Design.

### 3.2. Tags Semânticas
- O plugin Emmet do VSCode já escreve automaticamente uma estrutura básica em HTML.
- Ao digitar o caractere de exclamação, ele traz a opção de gerar as Tags básicas.
- Com isso, são geradas a <DOCTYPE html>, <html>, <head> e a <body>.
- Também, são geradas algumas Metatags comumente usadas pelos desenvolvedores.
- O atributo 'lang' da Tag <html> se refere à linguagem oficial da Página.
- A Tag <meta> permite algumas configurações internas da página.
- O atributo 'charset' da <meta> define a codificação de caracteres do arquivo.
- Atributo 'http-equiv' e 'content': Permitem a configuração do HTML para o Edge.
- Atributo 'name': Define o nome de alguma configuração que precisa de ajuste.
	- Configuração 'viewport': Escala a Página para os dispositivos que a acessa.
- Dentro do <body>, o HTML deve ser pensado separando o Layout em elementos.
- Existem Tags Semânticas que auxiliam nesta separação específica dos elementos.
- Uma separação básica divide a Página em cabeçalho, conteúdo principal e rodapé.
- As Tags referentes a esta separação são: <header>, <main> e <footer>.

### 3.3. Desenvolvendo o HTML
- Uma sugestão para desenvolver é pegar os elementos de uma direção para a outra.
- Comumente, pega-se da esquerda para a direita e também de cima para baixo.
- A Tag <strong> faz com que um trecho do texto receba um destaque mais forte.
- A Tag <a> é uma âncora que ao ser clicada direciona o usuário para outro lugar.
- O atributo 'href' recebe o endereço para onde o usuário deve ser direcionado.

## 4. Estilizando o Projeto com CSS

### 4.1. Como funciona o CSS
- De alguns anos para cá, a parte visual de uma Página Web ganhou muita importância.
- O CSS é a linguagem usada para dar a estilização adequada às Páginas Web.
- Ele descreve a forma como devem ser exibidos os elementos de marcação do HTML.
- Alguns os aspectos definidos são: Cor, formato, margem, tamanho, posição, etc.
- Com o CSS, é capaz de controlar o layout de várias páginas de uma só vez.
- Os estilos são controlados a partir das propriedades que os elementos possuem.
- Algumas propriedades: background-color, color, text-align, font-family, font-size.
- A criação do CSS foi responsável por remover do HTML tags de estilo como <font>.
- O CSS pode ser escrito em um arquivo separado do HTML, contendo a extensão `.css`.

### 4.2. Criando o CSS
- O nome padrão que é usado para o arquivo principal de é o `style.css`.
- Começamos a estilizar sempre os elementos que são mais externos.
- Logo, o elemento mais externo a ser estilizado é sempre o <body>.
- A propriedade `background-color` define a cor de fundo da página.
- Para que o CSS funcione, é necessário fazer a comunicação com o HTML.
- O arquivo CSS precisa ser linkado no arquivo HTML na tag <head>.
- Esta relação é criada através da metatag <link>.
- A metatag tem um atributo `rel` onde definimos o valor `stylesheet`.
- No atributo `href`, definimos o caminho do arquivo a ser linkado.
- No CSS, a propriedade `color` faz com que a cor da fonte mude.

## 5. Super Estilizando o seu CSS

### 5.1. Cores no CSS
- As cores no CSS podem ser representadas de uma forma diferente do nome.
- Esta forma pode ser um código hexadecimal que representa o padrão RGB.
- Cada par representa as cores vermelha, verde e azul que se misturam.
- Entre o #000000 e o #FFFFFF existem muitas combinações diferentes.
- Existem diferentes sites que mostram as combinações de cores.
- Dentro destas combinações, existem diferentes de cores harmonizantes.

### 5.2. Destacando o Texto
- No CSS, é possível destacar um texto concedendo ele uma cor específica.
- Podemos estilizar diretamente a tag <strong>, definindo uma cor padrão.
- Dando um estilo para à tag, ela será estilizada sempre que aparecer.
- Nem sempre é isso que queremos, pois ficaríamos limitados a uma só cor.
- Queremos o poder de usar <strong> e outras tags em diversos estilos.


# Curso HTML e CSS: Classes, Posicionamento e Flexbox

## 1. Seletores e Posicionamento

### 1.1. Apresentação
- Será apresentado ao usuário mais conhecimento a respeito do Cascading Style Sheets (CSS).
- Conseguiremos realizar uma estilização completa da página que já foi criada.
- Aprenderemos a posicionar elementos dentro do CSS, utilizaremos tecnologias de mercado.
- Conheceremos mais a tecnologia do CSS e como trazemos fontes diferentes para a aplicação.
- Será feito um refinamento no projeto já feito, deixando o seu visual ainda mais bonito.

### 1.2. Classes no CSS
- Queremos colocar uma cor na tag <strong> sem que todas as tags sofram esta mudança.
- No CSS criado, usamos o `body` e o `strong` como seletores para o CSS funcionar.
- Com isso, as tags que tiverem estes nomes sofrerão as mudanças definidas no CSS.
- Porém, não precisamos utilizar os nomes das tags como seletores, há outras formas.
- A forma mais utilizada de seletor é o de Classe CSS, que é mais flexível.
- Estes seletores abrangem apenas os elementos HTML que possuem o nome da Classe.
- Com isso, conseguimos mudar apenas um conjunto de tags com estas Classes CSS.
- O atributo `class` fica inserido na tag inicial de cada elemento HTML.
	- Ex: `<strong class="titulo-destaque">Texto</strong>`.
- Para definir o nome das Classes CSS, pode ser adotado um entre muitos padrões.
- Independente do padrão, devemos dar um nome que faça sentido para o que ela atende. 
- Dentro do CSS, o nome da Classe deve ser precedida do caractere `.`:
	- Ex: `.titulo-destaque { color: #22D4FD; }`
- Com isso, apenas os elementos que têm casse `titulo-destaque` recebem a cor azul.

### 1.3. Box Model
- Começamos a organizar o layout do portfolio, mas muitos pontos de posicionamento não estão legais.
- Além de estar grudado no lado esquerdo, o título parece estar ocupando uma linha inteira.
- Quanto aos links e a imagem do portfolio, parecem que estão ajustados em uma única linha.
- A sensação que fica é que dentro do HTML do portfolio, há algum CSS default sendo aplicado.
- É algo comum nos navegadores, e os desenvolvedores usam um `reset.css` para resolver isto.
- Com isso, eles conseguem ter um controle maior sobre o CSS, eliminando os padrões dos navegadores.
- Existem diversos `reset.css`, que resetam diversas tags que são comumente usadas em páginas HTML.
- Os `reset.css` eliminam os paddings, as margens, os estilos de fonte e posicionamentos defaults.
- Utilizando as o Dev Console do navegador, é possível visualizar o CSS aplicado por default.
- Cada elemento HTML segue um modelo conhecido como `Box Model` que define sua estrutura.
- Dentro dela, visualizamos a margem, a borda, o padding, o tamanho e comprimento dos elementos.
- Dentro do CSS, podemos definir configurações de cor e forma para todas estas propriedades.
- Para fazer um reset, devemos ter um seletor `*` que seleciona todos os elementos de uma página.
- Com isso, podemos configurar para zero os valores de todas estas propriedades, mudando o padrão.

## 2. Posicionando mais Elementos

### 2.1. Height e Box-Sizing
- Existem alguns padrões que nos ajudam a desenvolver um CSS melhor e bem estruturado.
- Há, por exemplo, uma forma de informarmos que a página ocupará a tela inteira.
- Dentro do seletor `body`, configuramos a propriedade de altura `height: 100vh;`.
- A propriedade marca o `body` com 100% de altura do `viewport` na página HTML.
- O `viewport` é a porção da área visível de um plano, no caso a tela do dispositivo.
- O `viewport` é definido através de uma meta tag criada no <head> do `index.html`.
- Isso significa que a altura máxima da página será o tamanho da tela do dispositivo.
- Devemos também garantir que os elementos filhos do `body` saiam de dentro dela.
- O nome desta propriedade é `box-sizing`, e ela serve para enquadrar os elementos.
- Apenas `width: 100%;` não é o suficiente, pois as bordas e margens saem do pai.
- Com `box-sizing: border-box;`, o filho ajusta suas margens e bordas ao elemento pai.
- Não importa a largura definida, o elemento encolhe sua largura para caber no pai.

### 2.2. Flexbox
- Depois de dar uma embelezada no layout da página, precisamos posicionar de fato os elementos.
- Existem várias formas de definirmos o posicionamento dos elementos de uma página HTML.
- Podemos definí-los de forma fixa, mas isto pode não funcionar a depender do dispositivo.
- Este tipo de posicionamento pode ser feito em alguns pontos, mas não com elementos grandes.
- No caso dos elementos grandes, temos tecnologias que são capazes de ajustá-los corretamente.
- Dentro do portfólio, temos dois elementos grandes, que é a sessão de texto e a imagem.
- O que queremos, é centralizar estes dois elementos no centro da página HTML do porftólio.
- A tecnologia de `Flexbox` é nova, e a ideia dele é centralizar blocos de conteúdo.
- A centralização é feita verticalmente, dentro de seus blocos pai sem um afetar o outro.
- Primeiro de tudo, devemos declarar o elemento principal onde o Flexbox vai ser utilizado.
- Devemos declarar neste elemento a propriedade CSS `display: flexbox`, o marcando como pai.
- Será a partir dela que conseguiremos fazer o posicionamento dos elementos com Flexbox.
- Por padrão, todos os elementos filhos do pai ficamo posicionados na mesma linha ou `row`.
- Com o `flex-direction`, podemos configurar para que os elementos fiquem na mesma coluna.
- O `flex-direction` disposto em linha ou em coluna vai depender muito do projeto.
- Com o `align-items`, podemos alinhar os itens em cima, embaixo ou no centro do elemento pai.
- O alinhamento dos itens acontece tendo como referência o item que tiver o maior tamanho.
- O item de maior altura que definirá o ponto central do alinhamento nestes casos.

## 3. Estilos de Texto e Fontes

### 3.1. Alinhando o Conteúdo
- Dentro do alinhamento de itens do Flexbox, conseguimos separá-los em blocos diferentes.
- No HTML, podemos estruturar esta separação em blocos por meio da tag `<section>`.
- Colocamos dentro da tag `<section>` todos os itens que queremos separar dos demais.
- No elemento pai, tudo o que está dentro de `<section>` será considerado uma coisa só.
- Mesmo fazendo está separação, os elementos ainda podem ficar juntos, sem margens.
- Com o `justify-content`, conseguimos dispor os elementos de forma que fiquem espaçados.
- O `justify-content: space-between` faz com que haja um espaçamento entre cada elemento.
- Com um `margin: 10%`, margeamos o conteúdo da página com 10% do comprimento da tela.

### 3.2. Estilizando o Texto
- Após definirmos o posicionamento, agora nos preocupamos com o tamanho das seções na página.
- Para isso, precisamos atribuir uma classe que faça isso ao <section> do conteúdo textual.
- Por padrão, podemos nomear esta classe prefixada com o nome do pai seguido de `__`.
- Na nova classe `apresentacao__conteudo`, definimos um `width` ou largura específica.
- Precisamos também alterar o tamanho das fontes do conteúdo com a propriedade `font-size`.

### 3.3. Importando Fontes
- O Google Fonts provê uma gama de fontes diferentes que podem ser importadas na página.
- Podemos trazer estas fontes tanto através do HTML quanto através do `@import` no CSS.
- Geralmente, os desenvolvedores costumam realizar a importação dentro dos arquivos CSS.
- Fazer esta importação dentro do HTML deixa o código engessado e menos reutilizável.
- É boa prática colocarmos o `@import` sempre no início do CSS antes de utilizá-la.
- Logo após a importação, configuramos o `font-family` dos seletores onde queremos usar.
- Dentro de um mesmo `@import`, conseguimos importar diferentes fontes para o CSS.

## 4. Manipulando Botões

### 4.1. Posicionando os Botões
- Dentro do HTML, os botões estão posicionados como se fossem uma pequena divisão do conteúdo.
- Para tratar esta divisão como um único elemento no posicionamento, usamos a tag `<div>`.
- Esta divisão poderia ser referente a botões, links, textos ou imagens específicas.
- Dentro da <div>, fazemos um `display: flex` com `justify-content: space-between`.
- Com isso, além de alinhados, os dois botões do portfólio ficam bem espaçados entre eles.

### 4.2. Estilizando os Botões
- Os dois botões que se encontram no portfólio têm o mesmo estilo, logo terão a mesma classe.
- Toda a estilização que for feita para um botão, automaticamente será feita para o outro.
- A propriedade `background-color` dá cor de fundo aos elementos HTML, incluindo a tag <a>.
- A propriedade `text-align` dá um alinhamento do texto em relação ao elemento HTML.
- A propriedade `border-radius` define o raio de arredondamento das boardas do elemento HTML.
- A propriedade `padding` define a distância entre as bordas do elemento HTML e seu conteúdo.
- Podemos distinguir o eixo vertical e o horizontal do padding com `padding: <v> <h>`.
- A propriedade `text-decoration: none` nos permite remover a decoração de uma tag <h>.
- A propriedade `font-weight` define se a forma da fonte será mais grossa ou mais fina.

## 5. Ajustando o Espaçamento

### 5.1. Recurso Gap
- Por questão de responsividade, os elementos <main> não devem receber margens fixas em pixels.
- Devemos, no mínimo, definir estes espaçamentos maiores por meio de valores em porcentagem.
- Usando o `flexbox`, conseguimos prover mais espaçamento para elementos muito aglomerados.
- Com o `flex-direction: column`, conseguimos dispor os elementos um abaixo do outro.
- A propriedade `gap: 40px` provê um espaçamento controlado entre os elementos dispostos.


# Curso HTML e CSS: Cabeçalho, Footer e Variáveis CSS

## 1. Preparando o Layout do Projeto

### 1.1. Apresentação
- Refinaremos o layout, teremos cabeçalho, uma nova tela e mais flexibilidade para configurar a aparência.

### 1.2. Figma do Projeto Atualizado
- É comum dentro da rotina da programação recebermos atualizações no layout de nossas páginas.
- Estas atualizações costumam ser documentadas por meio do Figma ou outra ferramenta.
- Com base nos layouts apresentados, vamos atualizando as páginas progressivamente.

### 1.3. Posicionando os Links
- No display flex, o valor `row` vem por padrão na propriedade `flex-direction`, podendo ser alterada.
- A propriedade `align-items` responde à `flex-direction`, alinhando os itens de acordo com ela.
- Com a propriedade `gap`, conseguimos definir um espaçamento entre os componentes de um elemento.

### 1.4. Estilizando os Links
- Para o subtitulo, foi criada uma classe CSS para definir a fonte como Krona One ou sans-serif.
- Para os botões, foi removida a cor de fundo, colocada uma borda e alterada a fonte.

## 2. Criando Ícones Clicáveis

### 2.1. Ícones das Redes Sociais
- Os ícones foram baixados pelo GitHub disponibilizado pela a Alura.
- Foram colocados em uma pasta com o nome de `assets` (Boa Prática).
- Foram referenciados pela tag `<img>` indicando o caminho do ícone.

### 2.2. Posicionando os Ícones
- A propriedade `justify-content` é responsável por justificar os filhos dentro do elemento pai.

### 2.3. Hover
- Ao passar o ponteiro do mouse em cima dos botões, queremos que eles recebam um destaque.
- No CSS, podemos configurar isso estilizando a propriedade `:hover` do elemento.

## 3. Criando Header e Footer

### 3.1. Desenvolvendo o Footer
- A tag `<footer>` foi reaproveitada para inserir um elemento parágrafo contendo o texto de rodapé.
- Tanto o elemento quanto o texto foram estilizados de acordo com o layout definido no Figma.
- O tamanho da tag `<body>` agora foi redimensionado, pois agora o `<footer>` delimita a página.

### 3.2. Desenvolvendo o Cabeçalho
- A tag `<nav>` será usada dentro da tag `<head>` para estruturar o menu presente no cabeçalho.

## 4. Navegando entre Páginas

### 4.1. Estilizando o Cabeçalho
- Os itens do menu receberam a cor e as configurações de fonte definidas no Figma.
- Além disso, foi feito o posicionamento com o display `flex` e o `gap`.

### 4.2. Navegando entre Páginas
- Agora, foi criada uma pasta `styles` separada para organizar os arquivos CSS que a página possui.
- Foi criado um arquivo `about.html` com um HTML padrão, onde a nova página será desenvolvida.
- Utilizamos a propriedade `text-decoration: none` para eliminar a decoração do link.
- Dentro da tag `<a>`, referenciamos a página `about.html` na propriedade `href`.

### 4.3. Desenvolvendo a Nova Página
- As duas páginas usam o mesmo `<footer>` e o mesmo `<header>`, então basta copiar a estrutura.
- É possível importar também o arquivo CSS através da tag `<link>`, reutilizando a existente.

## 5. Aplicando Variáveis CSS

### 5.1. Conteúdo da Página Sobre Mim
- Dentro da tag `<main>`, foi reutilizada a mesma estrutura da página inicial.
- A diferença foi a adição das tags `<p>` contendo os textos do 'Sobre mim'.

### 5.2. Variáveis CSS
- As variáveis CSS armazenam estilos que são utilizados em diferentes lugares do HTML.
- Elas podem ser declaradas dentro de um seletor `:root`, indicando escopo global.

### 5.3. Aplicando as Variáveis
- Para aplicar, atribuímos à propriedade a função `var(--nome-variavel)` correspondente ao estilo.
- Feito isso, basta apenas mudar o valor de uma única variável, e o estilo inteiro será alterado.


# Curso HTML e CSS: Trabalhando com Responsividade e Publicação de Projetos

## 1. Unidade de Medidas

### 1.1. Apresentação
- O portfólio agora poderá ser acessado de qualquer lugar e terá layout responsivo.

### 1.2. A Unidade de Medida REM
- A unidade de medida `px` não é adaptável às configurações de navegador do usuário.
- Logo, a unidade não funciona para navegadores com fontes de outros tamanhos.
- Existem dois grupos de medidas no CSS: Absolutas e Relativas.
- A unidade `rem` mede o tamanho dos elementos de acordo com o elemento raiz.
- Geralmente usamos uma escala de `16px` para calcular a conversão para `rem`.
	- Para cada `16px`, atribuímos proporcionalmente `1rem`.
