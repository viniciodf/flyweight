Padroes de Projeto

1) Criacionais -> Os padrões criacionais fornecem vários mecanismos de criação de objetos, que aumentam a flexibilidade e reutilização de código já existente.
2) Estruturais -> Os padrões estruturais explicam como montar objetos e classes em estruturas maiores mas ainda mantendo essas estruturas flexíveis e eficientes.
3) Comportamentais -> Padrões comportamentais são voltados aos algoritmos e a designação de responsabilidades entre objetos.

* Estruturais

6.Flyweight

O que é:
O O Flyweight é um padrão de projeto estrutural que permite que os programas suportem grandes quantidades de objetos, mantendo baixo o consumo de memória.

Aplicabilidade:
Utilize o padrão Flyweight apenas quando seu programa deve suportar um grande número de objetos que mal cabem na RAM disponível.

Identificação:
O Flyweight pode ser reconhecido por um método de criação que retorna objetos em cache em vez de criar novos.

Exempos de utilizacao:
java.lang.Integer#valueOf(int) (também Boolean, Byte, Character, Short, Long e BigDecimal)