# Árvore de Decisão 

 
A árvore de decisão é um modelo de aprendizado de máquina frequentemente usado em problemas de classificação. Como o nome sugere, a árvore de decisão é estruturada semelhante a uma árvore, onde cada nó representa uma decisão e cada folha representa um rótulo ou valor resposta.

No processo de treinamento de uma árvore de decisão, o modelo divide recursivamente o conjunto de dados em subconjuntos menores com base em certas características ou atributos. Cada divisão é escolhida de forma que minimize a impureza do subconjunto resultante, onde a impureza pode ser medida por diferentes critérios, como a entropia. O processo de divisão continua até que todas as amostras em cada subconjunto pertençam a uma única classe ou tenham um valor de saída. 

A Entropia é uma medida de incerteza em um conjunto de dados. Em termos simples, quanto maior a entropia, maior a incerteza em relação à distribuição das classes em um conjunto de dados. Na construção de uma árvore de decisão, o objetivo é minimizar a entropia nos subconjuntos de dados resultantes da divisão dos dados em nós filhos. Isso é feito escolhendo o atributo que produz a maior redução na entropia, ou seja, a escolha que melhor separa as amostras por classe.  Em termos simples, a impureza de Gini mede a frequência com que um elemento aleatório selecionado aleatoriamente de um subconjunto seria rotulado incorretamente, se o rótulo fosse atribuído aleatoriamente de acordo com a distribuição de classes do subconjunto. Se todos os elementos no subconjunto pertencerem à mesma classe, a impureza de Gini é zero, o que significa que não há incerteza sobre a classe desses elementos. Por outro lado, se as classes forem distribuídas uniformemente no subconjunto, a impureza de Gini será máxima.

Depois que a árvore é construída, ela pode ser usada para fazer previsões para novos exemplos, navegando na estrutura da árvore com base nos valores de seus atributos. Por exemplo, em uma árvore de decisão para classificar compradores online, o modelo faz uma série de perguntas para determinar se um comprador fará uma compra online, começando com a pergunta "Qual é a idade do comprador?" e continuando com outras perguntas. Os modelos de árvore de decisão são populares porque são fáceis de entender e interpretar.


# Referências 
* ChatGPT, https://chat.openai.com 
