# Fonte de Tensão Variável

## Descrição
O projeto se trata de uma fonte de tensão variável que, ao receber uma corrente alternada (AC), fornece uma corrente direta aproximadamente contínua (DC). Nesse contexto, deve ser possível regular a tensão de saída por meio de um potenciômetro, podendo escolher entre 3V e 12V e mantendo uma corrente de cerca de 100mA. Desse modo, a fonte deve ser capaz de carregar um celular sem causar danos.

## Componentes

| Quantidade      | Componente              | Valor   |
| --------------- | ----------------------- | ------- |
| 0x              | Placeholder             | R$0,00  |
| 0x              | Placeholder             | R$0,00  |
| TOTAL           |                         | R$00,00 |

#### Transformador
O transformador é responsável por diminuir o pico da tensão recebida da tomada de 180V para 18,1V. Essa transformação ocorre por meio da variação do campo magnético nas espiras do componente que causa uma indução de corrente elétrica.

#### Ponte de Diodo
A ponte de diodo é responsável por garantir que a corrente flua em somente um sentido ao longo do circuito. Isso é necessário, pois a tensão de entrada é uma senoide e, desse modo, possui uma parte negativa. Sendo assim, a ponte é composta por 4 diodos que, da forma em que estão dispostos, permitem a passagem de corrente em apenas um sentido.

#### Capacitor
O capacitor é responsável por continuar a fornecer tensão ao circuito mesmo nos mementos em que a senoide da tensão está com uma taxa de variação negativa, isto é, está diminuindo. Nesse sentido, o componente armazena carga quando a tensão está alta e libera carga quando a tensão de fora está menor do que a tensão do capacitor.

#### Resistor
O resistor é responsável por diminuir a tensão elétrica que chega a um outro componente. Isso é feito a fim de não ultrapassar a tensão de operação do componente em questão e mantê-lo funcionando.

#### LED
O LED é responsável por facilitar a visualização do comportamento do circuito. Nesse sentido, o intuito é que ele se mantenha aceso durante todo o período. Assim, indicando que a corrente está de fato contínua (aproximadamente).

#### Diodo Zenner
O diodo zenner é reponsável por limitar a tensão máxima que passa por ele. No circuito em questão, ele garante que a tensão máxima de saída seja 12V.

#### Transistor

#### Potenciômetro

## Circuito

## Design de PCB

## Cálculos

## Vídeo

## Integrantes do Grupo
