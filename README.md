# Portfólio - Dangeles Lima

Este portfólio é uma pequena compilação de projetos pessoais de simulação computacional e análise de dados.

## Simulação Computacional e Análise de Dados

### <a href="https://github.com/limadlp/NeuroComp" target="blank">Neurociência Computacional</a>

<a href="https://github.com/limadlp/NeuroComp/tree/main/Cpp" target="blank">**Classes em C++**</a>

Para facilitar a utilização e reutilização de vários modelos de neurônios, desenvolvi uma interface computacional com diferentes modelos de redes, dinâmicas neuronais e sinapses.
O núcleo da interface se divide em duas classes: 
* “rede.h”, contendo estruturas de redes; 
* “dinamica.h”, contendo modelos de dinâmica neuronais e sinapses; 


<a href="https://github.com/limadlp/NeuroComp/tree/main/Cpp" target="blank">Aqui</a>, temos exemplos de códigos para as classes da interface:

Na classe “rede.h” temos a rede unidimensional, a rede quadrada e um tipo de rede modular hierárquica. 
Na classe “dinamica.h” temos o modelo de integra-dispara simples, o modelo de Izhikevich. e o modelo de Levina-Herrmann-Geisel simplificado. 

**<a href="https://github.com/limadlp/NeuroComp/tree/main/Julia" target="blank">Modelos de neurônios em Julia</a>**

Alguns modelos de neurônios em linguagem Julia:
  * <a href="https://github.com/limadlp/NeuroComp/blob/main/Julia/LeakyIF.ipynb" target="blank">Leaky integrate and fire </a>
  * <a href="https://github.com/limadlp/NeuroComp/blob/main/Julia/ExpoIF.ipynb" target="blank">Exponential integrate and fire </a>
  * <a href="https://github.com/limadlp/NeuroComp/blob/main/Julia/HxHuxley.ipynb" target="blank">Hodkin-Huxley </a>


**<a href="https://github.com/limadlp/NeuroComp/blob/main/DataScience/Avalanche.ipynb" target="blank">Avalanches Neuronais - Análise de dados</a>**

<a href="https://github.com/limadlp/NeuroComp/blob/main/DataScience/Avalanche.ipynb" target="blank">Aqui,</a> um breve exemplo de análise utilizando Python. 

Os dados são de uma simulação de 1024 neurônios (modelo leaky integrate and fire) numa rede quadrada. 
A partir dos dados, é obtidada o histograma da distribuição de avalanches neuronais, bem como verifica-se um comportamento de lei de potência a partir do gráfico log-log.
___


### <a href="https://github.com/limadlp/LuckvsTalent" target="blank">Luck vs Talent</a>

Numa tentativa de estudar a não conexão entre inteligência e sucesso financeiro, simulei um modelo de sorte vs inteligência baseado em um <a href="https://arxiv.org/pdf/1802.07068.pdf" target="blank">artigo</a> que li. 

O modelo do artigo é baseado em agentes, os eventos seguem uma caminhada aleatoria num espaço bidimensional, foi programado em Netlogo. A minha versão dispensa a necessidade de um espaço e considera que os eventos sejam sorteados a cada iteração de acordo com uma determinada probabilidade e foi programado em C++ e em Python.

Mais detalhes e códigos <a href="https://github.com/limadlp/LuckvsTalent" target="blank">aqui</a>.
___

### <a href="https://github.com/limadlp/Biofeedback" target="blank"> Biofeedback com Arduino </a>

Circuitos e códigos, que desenvolvi, para capturar biosinais com arduino em tempo real. <a href="https://github.com/limadlp/Biofeedback" target="blank">Aqui.</a>
___

### <a href="https://github.com/limadlp/OrbitalDynamics" target="blank"> Dinâmica Orbital de Satélites </a>

Repositório com códigos, em Fortran, utilizados em um trabalho de simulação computacional de transferências orbitais de satélites.

No trabalho, foi apresentada uma proposta de manobras orbitais, de satélites, a partir do modelo de Hohmann para transferências não-impulsivas diferenciando a equação de Hohmann com intuito de obter um modelo semi-analítico de transferência entre órbitas próximas. Para obter os resultados a partir de simulações numéricas, foi utilizado um veículo espacial hipotético cujo decaimento se inicia a partir de 300 km até 120 km de altitude, onde supostamente começa a reentrada atmosférica do veículo até atingir a superfície da Terra. 
___

### <a href="https://github.com/limadlp/Blackjack" target="blank">Blackjack com Neuroevolução</a>

Criei uma inteligência artificial para jogar Blackjack utilizando redes neurais e algoritmos genéticos.

Mais detalhes e códigos <a href="https://github.com/limadlp/Blackjack" target="blank">aqui</a>.
___

### <a href="https://github.com/limadlp/Pokemon/blob/master/Pokemon3.ipynb" target="blank">Pokemon dataset</a>

Algumas análises exploratórias num <a href="https://www.kaggle.com/abcsds/pokemon" target="blank">dataset</a> de pokemon encontrado no <a href="https://www.kaggle.com/" target="blank">kaggle</a>.

Jupyter notebook: <a href="https://github.com/limadlp/Pokemon/blob/master/Pokemon3.ipynb" target="">aqui</a>.
___

## Aplicativos

### <a href="https://play.google.com/store/apps/details?id=com.axdtechnology.chordtransposer" target="blank">Practical Chord Transposer</a>

Aplicativo para Android que faz a transposição de notas e acordes em N semitons.

<img src="https://raw.githubusercontent.com/limadlp/limadlp.github.io/master/img/sc01.png" height="300">   <img src="https://raw.githubusercontent.com/limadlp/limadlp.github.io/master/img/sc03.png" height="300">   <img src="https://raw.githubusercontent.com/limadlp/limadlp.github.io/master/img/sc02.png" height="300">

Download <a href="https://play.google.com/store/apps/details?id=com.axdtechnology.chordtransposer" target="blank">aqui</a>.
