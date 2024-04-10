# Aprendendo Java

Este repositório documenta minha jornada de aprendizado em Java, iniciada com a ajuda do ChatGPT para estabelecer um plano de estudo estruturado.

## Semana 1: Fundamentos Básicos de Java

### Dia 1:
- Introdução à linguagem Java (já introduzida na faculdade)

- **Variáveis e tipos de dados**:
  - **boolean**: armazena 1 bit
  - **char**: armazena 1 byte (8 bits)
  - **String**: cadeia de caracteres
  - **byte**, **short**, **int**, **long**: tipos numéricos
  - **float**, **double**: tipos de ponto flutuante
  - **Constantes**: variáveis cujo valor não pode ser alterado após a atribuição inicial.

- **Operadores básicos**:
  - **Atribuição**: declara o valor inicial da variável ou sobrescreve seu valor.
    Exemplos:
    ```java
    String nome = "Gustavo";
    int idade = 21;
    double peso = 67.5;
    boolean doador = false;
    Date dataNascimento = new Date();
    ```

  - **Aritméticos**: adição (+), subtração (-), multiplicação (*), divisão (/).
    Exemplos:
    ```java
    double soma = 12.5 + 3.5;
    int subtracao = 113 - 2;
    int divisao = 15 / 3;
    int modulo = 18 % 3;
    double resultado = (10 * 7) + (20 / 4);
    ```

  - **Concatenação de Strings**: o operador `+` concatena texto.
    Exemplo:
    ```java
    String nomeCompleto = "Gustavo" + "Freire"; // Resultado: "GustavoFreire"
    ```

  - **Operadores unários**: servem para incrementar, decrementar, inverter valores numéricos e booleanos.
    Exemplo:
    ```java
    int numero = 5;
    System.out.println(-numero); // Imprimindo o número negativo

    numero++;
    System.out.println(numero); // Incrementando número em mais 1 (imprime 6)

    System.out.println(numero++); // Incrementando número em mais 1 (imprime 7)
    System.out.println(numero); // Imprime 7

    System.out.println(++numero); // Incremento pré-fixado (imprime 8)

    boolean verdadeiro = true;
    System.out.println("Inverteu: " + !verdadeiro); // Inverte o valor booleano
    ```

  - **Operadores relacionais**: avaliam a relação entre duas variáveis ou expressões.
    Exemplo:
    ```java
    int numero1 = 1;
    int numero2 = 2;

    if (numero1 > numero2) {
        System.out.println("Numero 1 maior que numero 2");
    }

    if (numero1 < numero2) {
        System.out.println("Numero 1 menor que numero 2");
    }

    if (numero1 >= numero2) {
        System.out.println("Numero 1 maior ou igual que numero 2");
    }

    if (numero1 <= numero2) {
        System.out.println("Numero 1 menor ou igual que numero 2");
    }

    if (numero1 != numero2) {
        System.out.println("Numero 1 é diferente de numero 2");
    }
    ```

- **Valor e referência**:
  - Exemplo:
    ```java
    String nome1 = "JAVA";
    String nome2 = "JAVA";

    System.out.println(nome1 == nome2); // true

    String nome3 = new String("JAVA");
    System.out.println(nome1 == nome3); // false

    String nome4 = nome3;
    System.out.println(nome3 == nome4); // true

    System.out.println(nome1.equals(nome2)); // true
    System.out.println(nome2.equals(nome3)); // true
    System.out.println(nome3.equals(nome4)); // true
    ```

### Dia 2:
- Estruturas de controle: `if`, `else`, `switch`
- Loops: `for`, `while`, `do-while`
- Exercícios práticos

### Dia 3:
- Arrays em Java
- Métodos e funções
- Exercícios de aplicação prática

## Semana 2: Orientação a Objetos em Java

### Dia 4:
- Introdução à Programação Orientada a Objetos (POO)
- Classes e Objetos em Java

### Dia 5:
- Encapsulamento e modificadores de acesso
- Construtores e sobrecarga de métodos

### Dia 6:
- Herança e Polimorfismo
- Exercícios práticos de POO

## Semana 3: Tópicos Avançados

### Dia 7:
- Interfaces e classes abstratas
- Pacotes e visibilidade

### Dia 8:
- Tratamento de exceções (`try-catch-finally`)
- Manipulação de arquivos em Java

### Dia 9:
- Coleções em Java: List, Set, Map
- Exercícios práticos com coleções

## Semana 4: Desenvolvimento de Projetos e Prática Avançada

### Dia 10:
- Introdução ao desenvolvimento de projetos Java
- Criação de pequenos aplicativos ou jogos

### Dia 11:
- Introdução ao uso de uma IDE (como IntelliJ IDEA, Eclipse)
- Depuração e teste de código

### Dia 12:
- Revisão dos tópicos anteriores
- Desafios de programação em Java

Este plano de estudo visa proporcionar uma base sólida
