## Dicionário de termos funcionais traduzidos

Após diversas threads de discussão no grupo do telegram foi visto necessário um dicionário de traduções curados e atribuidos a um nível de qualidade de tradução.

#### Tabela de tradução
- :white_check_mark: Tradução correta
- :interrobang: Tradução popular(não necessáriamente certa)
- :x: Erro comum

**Expression**

- :white_check_mark: Expressão

Pode se referir a expressões matemáticas ou algebricas. Geralmente com o intuito de gerar um valor por meio de avaliação(*ver Evaluation*).

*(1.6 https://libgen.pw/item/detail/id/5a1f04f13a044650f5087e0a)*

**Statement** 

- :white_check_mark: Declaração

Declarações funcionam ou como controle do fluxo de controle do programa como por exemplo, condicionais ou loops ou como meio de alterar o estado(memória).

*(1.6 https://libgen.pw/item/detail/id/5a1f04f13a044650f5087e0a)*

**Environment**
- :white_check_mark: ambiente

Em teoria de linguagens de programação, ambiente é uma estrutura de dados que associa identificadores de variáveis a valores. A implementação de uma linguagem com suporte a variáveis precisa ter pelo menos um ambiente global. Linguagens que implementam funções normalmente criam um ambiente local ao executar cada função. Além desses ambientes global e local, linguagens que permitem funções definidas dentro de outras também podem implementar closures. Dicionários e listas associativas são formas comuns de implementar ambientes.

**RunTime Environment**

- :white_check_mark: Ambiente de execução
- :x: Ambiente de tempo de execução(?)

Sistema de suporte que permite a execução de programas em linguagens que não tem compiladores para gerar código de máquina nativo. O ambiente de execução de linguagens interpretadas, como Python e Ruby, inclui o interpretador e a biblioteca-padrão da linguagem. Certas linguagens compiladas como Java, Closure e Kotlin dependem da máquina virtual Java (JVM) para executar seus binários.

**Arity**

- :white_check_mark: Aridade

Número de argumentos que uma função aceita. Por exemplo, em Python a função `abs(n)` tem aridade 1, mas `divmod(a, b)` tem aridade 2.

**Closure**

- :white_check_mark: Closure
- :x: Clojure
- :x: Fechamento

Estrutura formada por uma função e um ambiente com variáveis necessários para a execução da função, mas não definidas no corpo da função -- chamadas variáveis livres ou não-locais. Uma linguagem só precisa implementar o mecanismo de closure se ela permite a definição de uma função dentro de outra, e permite que a função externa devolva a função interna como resultado. C e Pascal não precisam de closures; Scheme e Python precisam.

**Garbage Collector**

- :white_check_mark: Coletor de lixo
- :x: Lixeiro

Sub-sistema de ambiente de execução de uma linguagem de programação que faz o descarte automático de estruturas de dados que não podem mais ser acessadas pelo programa do usuário. Smalltalk, Java, Python são linguagens com coletores de lixo integrados ao seu ambiente de execução. Em Go, o coletor de lixo é parte do código gerado pelo compilador ao produzir um executável.
s-expression
A sintaxe de expressões da linguagem LISP, formada por parêntesis aninhados, símbolos separados por espaços, e operadores prefixos (e não infixos como na aritmética convencional). A fórmula de Pitágoras pode ser escrita assim em LISP: `(sqrt (+ (* a a) (* b b)))`.

**Assignment**

- :white_check_mark: Atribuição

**State**

- :white_check_mark: Estado

**Invocation**

- :white_check_mark: Invocação

**Evaluation / Evaluate**

- :white_check_mark: Avaliação / avaliar
- :interrobang: Evaluação / Evaluar

**Lazy evaluation**

- :white_check_mark: Avaliação ociosa
- :x: Avaliação preguiçosa

**Right-hand**

- :white_check_mark: Segundo termo
- :x: Mão direita / Lado direito / Do lado direito

### TODO
