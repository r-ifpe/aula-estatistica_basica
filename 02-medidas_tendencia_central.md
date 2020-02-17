# Medidas de Tendência Central

Neste capítulo veremos as três principais medidas de tendência central: média, mediana e moda.

## Média

É o valor médio entre todos os valores de um conjunto de dados. Em estatística costuma-se representar por $\overline{X}$. A fórmula é dada por:

$$\overline{X} = \frac{x_1 + x_2 + ... + x_n}{n}$$

Onde x corresponde a cada elemento do conjunto de dados, $x\_n$ corresponde ao último elemento do conjunto de dados e $n$ é o número total de elementos do conjunto de dados.

Exemplo: 1-1-2-2-2-2-3-4-5-6

$$\overline{X} = \frac{1+1+2+2+2+2+3+4+5+6}{10} = \frac{30}{10} = 3$$ 

Como você pode perceber, a cálculo da média é igual ao que você aprendeu na escola. A diferença aqui é a interpretação dela. Para nós estatísticos, a média significa, literalmente, um centro. Você deve ter visto em física algo sobre centro de massa, um ponto em um objeto que é como se todo seu peso estivesse concentrado neste único ponto, sabe como calcula isso? usando médias.

Para a estatística, a média também significa um centro e é como se todos os elementos daquela amostra fossem representados por aquele único número. Por exemplo, quando se entra numa sala e pergunta a idade da turma, não se diz a idade de cada um dos alunos, tira-se uma média das idades. Se, por exemplo, na sua sala a média de idade é 20, isso é um ponto central e tem-se a ideia de todos naquela sala tem 20 anos, ou pelo menos próximo a isso.

Mas, as vezes pode acontecer o caso de um elemento apresentar um valor muito maior \(ou muito menor\) que os demais. Por exemplo, imagine um jogo em que todos marcam 50 pontos e de repente alguem vem e marca 500. A esses elementos cujo o valor é muito longe da média chamamos eles de pontos aberrantes ou _outliers_. Isso pode prejudicar a avaliação da medida de tendência central. Suponha a sequência 1-2-3-4-5, a média é 3, certo? Mas se alterarmos um único elemento da sequência, por exemplo 1-2-3-4-500, a média agora é 102. Percebe que o valor 102 não representa essa sequencia como medida de centro? O elemento de valor 500 é claramente um _outlier_ e isso faz com que a média se "perca" como medida de centro.

Quando temos _outliers_ na amostra e não temos como retirar, precisamos de uma segunda medida de centro: a mediana.

## Mediana

É o elemento que ocupa a posição central do conjunto de dados quando estes estão em ordem, seja crescente ou decrescente. Em estatística, costama-se representar a mediana como $\widetilde{X}$. Para calcular a mediana siga o esquema abaixo.

* Se a quantidade de elementos for impar, use $\frac{n + 1}{2}$
* Se a quantidade de elementos for par, tire a média entre o elemento $\frac{n}{2}$ e $\frac{n}{2} + 1$

Exemplo: 1-1-2-2-2-2-2-3-4-5 \(quantidade de elementos impar\) Aqui são 9 elementos então $\frac{9 + 1}{2} = 5$. Lembre-se que 5 não é o valor da mediana e sim a posição da mediana. Olhando pra sequência deste exemplo o quinto elemento é 2, por isso a mediana para esse conjunto de números é 2.

Exemplo: 1-1-2-2-3-4-5-6-7-7 \(quantidade de elementos par\) Aqui são 10 elementos então a posição da mediana será a média entre os elementos da posição $\frac{10}{2} = 5$ e posição $\frac{10}{2} + 1 = 6$. O elemento da posição 5 é 3 e o elemento da posição 6 é 4, então $\frac{3 + 4}{2} = 3,5$, logo o valor da mediana para este conjunto de números é 3,5.

## Moda

É o valo do elemento que ocorre com maior frequência. Em estatística representamos por $M\_o$. Uma sequência de dados podem apresentar mais de uma moda caso tenham mais de um elemento com a mesma quantidade de repetição. Um conjunto de dados, inclusive pode não aprenstar moda caso nenhum elemento se repita.

Exemplo: 1-1-2-2-2-2-2-3-4-5-6  
$M\_o = 2$

Exemplo: 1-1-2-3-4-5-5  
$M\_o = 1 \space e \space 5$ \(bi-modal\)

Exemplo: 1-2-3-4-5  
Amodal \(nenhum elemento se repete\)

## Quando utilizar média e mediana

### OUTLIER
