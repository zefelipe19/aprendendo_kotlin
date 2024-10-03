# Um guia basico de introdução a linguagem kotlin
**Este é um guia introdutório da linguagem kotlin, todo o conteúdo de estudo será passado, por esse README, e 
dentro do diretório src/, encontra-se um script que vai por em prática tudo que foi passado aqui.**
## O que é kotlin?
Kotlin é uma linguagem **compilada** e **fortmiente tipada** isto é, todo o script é compilado e gerado um 
*binário (executável)*, que é executado pelo sistema operacional e toda variável que é declarada 
deve ter o seu tipo explicito já na declaração da mesma. 

*EX: var helloWorld: String = "Hello World"*

*print(helloWorld)* //Hello World

#### Syntaxe de declaração de uma variável em kotlin
Para declarar uma variável em kolin, preciamos inicia-la com **"val"** (para variáveis não mutáveis) e **"var"** 
(para variáveis mutáveis), 

**Variável imutável:**

*Ex: val mediaDeCorte: Int = 7*

*mediaDeCorte = 9* 

*print("A média de corte é: ${mediaDeCorte}")* // Kotlin: Val cannot be reassigned

**Variável mutável**

*Ex: var nodaDoAluno: Int = 8*

*notaDoAluno = 10*

*print("A nota do aluno é: ${notaDoAluno}")* // A nota do aluno é: 10

### Tipos básicos do kotln
O kotlin possuí alguns tipos básicos, que com eles podemos criar tipos mais complexos para estruras de dados, são eles:
- Integers {Byte, Short, Int, Long *Ex: val year: Int = 2020* }
- Unsigned integers { UByte, UShort, UInt, ULong *Ex: val score: UInt = 100u* }
- Floating-point numbers { Float, Double *Ex: val currentTemp: Float = 24.5f, val price: Double = 19.99* }
- Booleans { Boolean *Ex: val isEnabled: Boolean = true* }
- Characters { Char *Ex: val separator: Char = ','* }
- Strings { String *Ex: val message: String = "Hello, world!"* }

### Estruturas de Dados
As estruturas de dados básicas do kotlin, são:
- List
- Set
- Map