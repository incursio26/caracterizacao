Linguagem C++

Apresentação e Histórico
		C++ surge como uma linguagem de programação que estende de C, dessa forma, pode-se considerar que C++ é um super conjunto de C, ou seja, todo programa em C pode ser visto também como um programa em C++, contudo a recíproca não é verdadeira. A ideia original por trás da criação da linguagem se dá pelo intuito de desenvolver uma maneira mais simples e elegante de desenvolver códigos do que a linguagem C, C++ se apresenta também com maior flexibilidade, pois mistura um pouco de baixo e alto nível.

Características da Linguagem
	Paradigma, Propósito e Sistema de Tipagem
		C++ é uma linguagem orientada a objetos cujo objetivo inicial era melhorar uma versão do núcleo Unix. Com o passar do tempo, C++ se tornou muito popular e uma das linguagens de programação mais utilizadas no mundo.
		Na sua etapa de desenvolvimento, foram adicionados diversos elementos de distintas linguagens de vários níveis, com a ideia da criação de uma linguagem com vários novos elementos sem problematizar a questão da programação em si.
		C++ se caracteriza ainda por ser uma linguagem fortemente tipada de tipo estático, ou seja, após a declaração de uma variável, não é possível alterar seu tipo posteriormente. É possível, contudo, copiar o valor da variável ou retorno da função para uma variável de outro tipo, são as conhecidas conversões de tipo.

Capacidades da Linguagem
	Confiabilidade e Escalabilidade
		A confiabilidade sempre deve ser um aspecto considerado ao analisar linguagens de programação, dado que uma linguagem confiável possibilita a criação de programas mais seguros, mais simples de serem desenvolvidos e com maior taxa de facilidade destinada ao usuário. Existem diversos fatores que podem ser levados em consideração para analisá-la, dentre os quais destacam-se o tratamento de exceções, legibilidade, facilidade de escrita etc. C++ possui algumas características que possibilitam erros na programação, um dos mais “criticados” é a manipulação direta de endereços de memórias, sobretudo com a utilização de ponteiros. Cabe mencionar que a linguagem possui, no entanto, um tratamento de exceções através dos comandos try() e catch() que permite ao programador tratar diretamente alguns erros.

Produtividade do Desenvolvedor
	Frameworks e Containers
		Em palavras mais simples, pode-se dizer que contêineres seriam itens entendidos como “modelos” de classe. Quando uma variável de contêiner é declarada, especifica-se os tipos de elementos que serão mantidos pelo contêiner. Estes podem ser criados com listas e possuem funções para manipulação de elementos e realizar diversas operações. Alguns dos principais containers de C++ são:  
<bitset> - manipulação de arranjo de bits
<vector> - manipulação de arranjo
<deque> - manipulação de lista duplamente ligada
<list> - manipulação de lista simplesmente ligada
<stack> - manipulação de lista LIFO
<queue> - manipulação de lista FIFO
<map> - manipulação de conjunto associativo ordenado do tipo chave → valor
<set> - manipulação de conjunto
Com o C++14, versão recente da linguagem, é possível passar qualquer tipo para o qual é definido um operador sobrecarregado, ele permite a comparação com o respectivo tipo de chave. Vale mencionar ainda que caso seja utilizado o comparador padrão, o comportamento será o mesmo das versões mais antigas.
	Dentre os frameworks em C++, destacam-se alguns para a utilização de interfaces gráficas como o gtkmm, que é um software livre capaz de permitir a criação de telas de usuário em código, além de outras funcionalidades como um conjunto de elementos para a extensibilidade de widgets através de herança e recursos de callback; outro notável é o Qt, um kit de ferramentas de widget para a criação de interfaces gráficas, ele é um aplicativo com recursos e velocidade nativos.

Ecossistema
	Maturidade, Comunidade e Fragmentação
		A fragmentação de memória em C++ pode ser entendida com uma metáfora simples, como em uma sala na qual existem algumas caixas de diversos tamanhos e há o interesse de alocar mais uma grande caixa de tamanho X e apesar da sala ter espaço disponível para a caixa, o espaço está distribuída de forma desigual em vários pequenos espaços e a caixa não é suportada na sala já que ela não pode ser divida em caixas menores.. Basta associar a sala à memória e as caixas aos objetos. 
		Geralmente, esse não é um problema tão grave e ele pode ser evitado com algumas práticas preventivas, como a alocação prévia explícita da memória destinada a vetores e objetos menores. Com isso, o desempenho também é aumentado e as chances de problemas com memória são reduzidas.
		A comunidade em C++ se distingue como uma das maiores, mais ativas e mais duradouras da internet. Diversos fóruns estão à disposição dos programadores e usuários, além de extensas documentações e tutoriais desde o nível básico até os mais avançados temas da linguagem. Dentre os mais distintos fóruns e portais, destacam-se Clube do Hardware, Fórum Script Brasil e o próprio fórum do C++, que seguem elencados na seção de referências do presente documento.
		C++ destaca-se sobretudo, devido a seus vários anos de evolução, como uma linguagem robusta, madura e concisa. Afinal, existem diversas aplicações e utilizações que foram aumentando ao longo do tempo, e mesmo com o surgimento e popularização de outras linguagens, C++ segue, desde sempre, sendo amplamente utilizada e isso gerou uma ótima consequência, a construção de uma linguagem que amadureceu ao longo do tempo e tornou-se muito adaptável.


Referências
https://docs.microsoft.com/pt-br/cpp/standard-library/stl-containers?view=msvc-170
https://docs.microsoft.com/en-us/cpp/dotnet/stl-clr-containers?view=msvc-170
https://pt.wikipedia.org/wiki/Biblioteca_padr%C3%A3o_do_C%2B%2B
http://users.cms.caltech.edu/~mvanier/hacking/rants/scalable_computer_programming_languages.html
https://www.cplusplus.com/forum/
https://forum.scriptbrasil.com.br/forum/20-c-c/
https://www.clubedohardware.com.br/forum/177-ccc/
https://blog.geekhunter.com.br/os-5-melhores-frameworks-de-python/
https://docs.python.org/3/library/collections.html
https://docs.python.org/3/library/collections.html
https://terminalroot.com.br/2021/09/os-7-melhores-frameworks-cpp-para-criar-interface-grafica.html
https://www.gartner.com/en/documents/2071615/programming-languages
https://wiki.sj.ifsc.edu.br/index.php/Introdu%C3%A7%C3%A3o_C%2B%2B#Introdu.C3.A7.C3.A3o
https://www.cetax.com.br/blog/linguagem-python-por-que-aprender/
https://www.ti-enxame.com/pt/c%2B%2B/o-que-e-fragmentacao-de-memoria/971042005/