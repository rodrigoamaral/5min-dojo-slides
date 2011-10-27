# Sugestões de problemas

---

# Jokenpo

Jokenpo é uma brincadeira japonesa, onde dois jogadores escolhem um dentre três possíveis itens: Pedra, Papel ou Tesoura.

O objetivo é fazer um juiz de Jokenpo que dada a jogada dos dois jogadores informa o resultado da partida.

As regras são as seguintes:

- Pedra empata com Pedra e ganha de Tesoura
- Tesoura empata com Tesoura e ganha de Papel
- Papel empata com Papel e ganha de Pedra

**Fonte:** [DojoPuzzles.com](http://dojopuzzles.com/problemas/exibe/identificando-progressoes-aritmeticas/)

---

# Nomes de Autores 

Quando se lista o nome de autores de livros, artigos e outras publicações é comum que se apresente o nome do autor ou dos autores da seguinte forma: sobrenome do autor em letras maiúsculas, seguido de uma vírgula e da primeira parte do nome apenas com as iniciais maiúsculas.

Por exemplo:

SILVA, Joao    
COELHO, Paulo     
ARAUJO, Celso de    

Seu desafio é fazer um programa que leia um número inteiro correspondendo ao número de nomes que será fornecido, e, a seguir, leia estes nomes (que podem estar em qualquer tipo de letra) e imprima a versão formatada no estilo exemplificado acima.

---

# Nomes de Autores 

## (cont.)

As seguintes regras devem ser seguidas nesta formatação:

- o sobrenome será igual a última parte do nome e deve ser apresentado em letras maiúsculas;
se houver apenas uma parte no nome, ela deve ser apresentada em letras maiúsculas (sem vírgula): se a entrada for “ Guimaraes” , a saída deve ser “ GUIMARAES”;
- se a última parte do nome for igual a "FILHO", "FILHA", "NETO", "NETA", "SOBRINHO", "SOBRINHA" ou "JUNIOR" e houver duas ou mais partes antes, a penúltima parte fará parte do sobrenome. Assim: se a entrada for "Joao Silva Neto", a saída deve ser "SILVA NETO, Joao" ; se a entrada for "Joao Neto" , a saída deve ser "NETO, Joao";
- as partes do nome que não fazem parte do sobrenome devem ser impressas com a inicial maiúscula e com as demais letras minúsculas;
"da", "de", "do", "das", "dos" não fazem parte do sobrenome e não iniciam por letra maiúscula.

**Fonte:** [DojoPuzzles.com](http://dojopuzzles.com/problemas/exibe/identificando-progressoes-aritmeticas/)

---

# Identificando Progressões Aritméticas

Uma progressão aritmética (PA) é um seqüência numérica em que cada termo, a partir do segundo, é igual à soma do termo anterior com uma constante R positiva (denominada razão).

A fórmula geral de uma PA é:

an = a1 + (n - 1) * R

Dado um conjunto de números inteiros positivos, identificar todos os subconjuntos de no mínimo 3 elementos onde os números formam uma progressão aritmética.

Devem ser apresentados sempre os maiores subconjuntos que forme uma PA

---

# Identificando Progressões Aritméticas

## (cont.)

Por exemplo, dado o subconjunto (1,2,3,5,6,7,9) teríamos como resultado:    
(1,2,3)    
(5,6,7)    
(1,3,5,7,9)    
(3,6,9)    
(1,5,9)    

Note que, por exemplo, (1,3,5) não deve ser apresentada, porque já faz parte de (1,3,5,7,9).

**Fonte:** [DojoPuzzles.com](http://dojopuzzles.com/problemas/exibe/identificando-progressoes-aritmeticas/)

