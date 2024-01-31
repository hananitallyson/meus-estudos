# Cap. 2 - Operações de Números naturais

## Adição de números naturais

Formalmente, temos que, para todo a, b ∈ N, existe um único número c ∈ N, tal que a + b = c, onde a, b são denominados **parcelas** e c é denominado **soma** ou **total**. A adição de dois números naturais é sempre um número natural.

```
  315 > Parcelas
+ 208 > Parcelas
-----
  523 > Soma total
```

### Propriedades da adição

A adição possui três propriedades: **comutativa**, **associativa** e **elemento neutro**.

1. **Comutativa**: Para todo a, b ∈ N, temos que a + b = b + a.
   - e.g., 3 + 5 = 5 + 3 = 8
2. **Associativa**: Para todo a, b, c ∈ N, temos que (a + b) + c = a + (b + c).
   - e.g., (12 + 4) + 3 = 12 + (4 + 3) = 19
3. **Elemento neutro**: Existe o elemento neutro aditivo em N, que é o zero, de modo que para todo a ∈ N, temos que a + 0 = 0 + a.
   - e.g., 9 + 0 = 0 + 9 = 9

## Subtração de números naturais

Consideramos dois números a, b ∈ N. Se existir um c ∈ N de modo que b + c = a, então temos a - b = c, onde a é denominado **minuendo**, b é o **subtraendo** e c é a **diferença** ou **resto**.

```
  225 > Minuendo
-  13 > Subtraendo
-----
  212 > Diferença ou resto
```

Se fizermos a diferença somada com o subtraendo, obtemos o minuendo. Logo, a subtração é a operação inversa da adição. É a sua **prova real** (i.e., uma operação matemática realizada para provar que outra operação está correta).

As propriedades **comutativa**, **associativa** e o **elemento neutro** não se aplicam à subtração, uma vez que:

1. a - b ≠ b - a
2. (a - b) - c ≠ a - (b - c)
3. a - 0 ≠ 0 - a.

## Multiplicação de números naturais

De modo geral, sejam a, b ∈ N. A multiplicação entre a e b é igual à adição de a **parcelas** b. Ou seja:

```
  a x b = b + b + ... + b
```

Os termos de um multiplicação são: **multiplicando**, **multiplicador** e **produto**. Os dois primeiros também podem se chamar **fator**.

```
   87 > Multiplicando
x  13 > Multiplicador
-----
 1131 > Produto
```

A multiplicação possui quatro propriedades: **comutativa**, **associativa**, **elemento neutro** e **distributiva**. As propriedades **comutativa** e **associativa** funcionam como na adição (i.e., a x b = b x a; (a x b) x c = a x (b x c)).

O **elemento neutro** da multiplicação é 1, tal que qualquer número natural multiplicado por 1 é sempre o próprio número (i.e., 1 x a = a x 1, onde a ∈ N).

A **distributiva** é a propriedade relacionada a adição, e é popularmente chamada de "chuveirinho". Onde, a x (b + c) = a x b + a x c, distribuindo a multiplicação para as duas parcelas da adição.

## Divisão de números naturais

Existem dois tipos de divisão: **divisão exata** e a **divisão não exata**.

Os termos de um divisão são: **dividendo** (D), **divisor** (d), **resto** (R) e **quociente** (Q).

### Divisão exata

É quando o resto é zero. De modo formal, dados dois números a, b ∈ N com B ≠ 0, define-se como divisão exata de a por b se existe um único número c ∈ N, tal que o resto é 0.

### Divisão não exata

Se efetuarmos uma divisão em que não existe um número natural que faça ser exata, pois o resto é diferente de zero, então essa é uma divisão não exata e possui um **quociente aproximado**, ou seja, R ≠ 0.

### Informações importantes da divisão

1. O divisor deve ser sempre diferente de zero (i.e., d ≠ 0).
2. Se: D = 0, d ≠ 0, então Q = 0.
3. Se: D = d, Q = 1.
4. Se: D ≠ 0 e d = 1, então Q = D.
5. Na divisão não exata: R < d.

Assim como a subtração é a operação inversa da adição, a divisão é a **operação inversa** da multiplicação. Na divisão exata temos que D = Q x d. Enquanto na divisão não exata temos que D = Q x d + R. Dessa forma, é possível tirar **prova real** da divisão.

## Potenciação com números naturais

Uma multiplicação de **fatores iguais** denomina-se potenciação.

```
  2 x 2 x 2 x 2 x 2 = 2⁵ = 32
```

Os termos de uma potenciação são: **expoente**, **base** e **potência**.

```
    Expoente
    ^
   3² = 9 > Potência
   v
   Base
```

Genericamente: se a ∈ N e n ∈ N (n ∩ 2), podemos escrever:

```
  a x a x a x ... x a = aⁿ
```

### Propriedades relativas às potências de mesma base

1. aⁿ x aⁱ = aⁿ⁺ⁱ
2. bⁿ / bⁱ = bⁿ⁻ⁱ
3. (aⁿ)ⁱ = aⁿ\*ⁱ
4. (bⁿ x cⁱ)ª = bⁿ\*ª x cⁱ\*ª

### Expoente zero e 1

Qualquer número natural, diferente de zero, elevado a 0 é igual a 1. Enquanto, qualquer número natural elevado a 1 é igual a ele mesmo.

### Potências notáveis de base decimal

A chamada notação científica. São as potências cuja base é o numeral 10 (i.e., 10ⁿ = 10.......0)

## Radiciação de números naturais

A radiciação é a **operação inversão** da potenciacão. De modo que:

```
  aⁿ = A 🠖 ⁿ√A = a
```

Cada elemento possui um nome específico:

| Elemento | Nome            |
| -------- | --------------- |
| n        | Índice da raiz  |
| A        | Radicando       |
| a        | Raiz            |
| √        | Símbolo da raiz |

## Resolução de expressões aritméticas

A resolução de uma expressão aritmética se faz na seguinte ordem, de cima para baixo:

| Ordem | Símbolos      | Operação                  |
| ----- | ------------- | ------------------------- |
| 1°    | Parenteses () | Potenciação ou radiciação |
| 2°    | Colchetes []  | Multiplicação ou divisão  |
| 3°    | Chaves {}     | Adição e subtração        |

---

- [⬅️ Anterior](1-numeros-e-conjuntos.md) - [Guia 📝](../guia-de-matematica.md) - [Próximo ➡️](2-operacao-de-numeros-naturais.md)

## Referências

Bosquilha, Alessandra; Amaral, João Tomás do; Miranda, Mônica. Manual compacto de matemática: ensino fundamental. 1. ed. São Paulo: Rideel, 2010.

Wikipedia. (s.d.). Prova Real. [https://pt.wikipedia.org/wiki/Prova_real]
