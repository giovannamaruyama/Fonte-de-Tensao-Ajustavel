# Fonte-de-Tensao-Ajustavel
Projeto realizado para a disciplina SSC0180 – Eletrônica para Computação', acompanhado pelo professor Eduardo do Valle Simões. Com o objetivo de projetar uma fonte de tensão ajustável entre 3v e 12

## INTEGRANTES:
Barbara Naomi Morimoto Hatano - 13678755, Eric Costa Lopes - 17070779, Giovanna Maruyama - 16869489 e Giovanni Torres Bullo- 16869833

## LISTA DE COMPONENTES:
| Componente      |     Especificação       | Preço
| -------------   |:-------------:          | -----:|
|PROTOBOARD        |BB-01 400P            | 1 x 21,70
|CAPACITOR       | 470UFX35V            | 1 x 2,80 |
| LED        | 5MM VERMELHO            |  1 x 0,50 |
| DIODO ZENER   | 13V 1W            |  1 x 0,50|
| POTENCIÔMETRO        |  1W B5K                | 1 x 7,00 |
| RESISTOR CR25  | 100R               | 10 x 0,07 |
| RESISTOR CR25| 820R                |  10 x 0,07 |
| RESISTOR CR25  |  1K               |  10 x 0,07 |
| RESISTOR CR25  | 2K              | 2 X 1,90 |
| TRANSISTOR  |60V 0,2A 0,625W      | 1 x 1,60 |
| PONTE DE DIODO  |1N4007     | 1 x 2,00 |
| TOTAL  |             |   R$42,00 |

 A fonte inicia com um transformador 110 V→24,2 V AC que reduz a tensão de rede a um nível seguro e isolado para as etapas seguintes. Em seguida, a ponte de quatro diodos 1N4007 converte essa tensão alternada em pulsos de corrente contínua; o modelo 1N4007 foi selecionado por sua capacidade de suportar até 1 A e tensões elevadas. O capacitor eletrolítico de 470 µF × 35 V suaviza esses pulsos, mantendo o ripple em torno de 1,8 Vpp e fornecendo reserva de energia para pequenos picos de demanda de carga.

Para estabelecer a referência de controle, um diodo Zener de 13 V em conjunto com dois resistores de 1,8 kΩ em série limita a corrente a cerca de 5 mA, assegurando que o Zener opere em sua região de regulação sem sobreaquecimento. O potenciômetro de 5 kΩ, ligado entre o terminal do Zener e o terra, transforma essa referência fixa em uma tensão ajustável de 0 a 13 V na base do transistor, permitindo a definição continuamente a saída entre aproximadamente 3 V e 12 V, respeitando a queda de base emissor de cerca de 0,7 V.

O transistor 2N3904, empregado como seguidor de emissor, “acompanha” a tensão da base e amplifica a corrente de modo que até 100 mA possam ser entregues à carga sem que o circuito de referência seja afetado. O LED vermelho de 5 mm com resistor série de 2 kΩ oferece indicação visual de que a fonte está ligada, acendendo com brilho confortável e sem comprometer a tensão de trabalho. Cada componente foi escolhido com equilíbrio entre custo, disponibilidade e desempenho, resultando em uma fonte ajustável estável e adequada às especificações de 3–12 V DC e até 100 mA.

## PROJETO NO FALSTAD
[Clique para abrir a simulação](https://www.falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWKsDMAmALANgZrB2FBADhQwE58QFJqQMVqBTAWjDACgA3EFhLWhmK9+tFuSxRwIAeGK0FyBBwAmvIml4T1aMVgwhNYAHIY4GVetw6deg0dPnLLFMQMt9VzeMkOzkCzUXN15PF2sXTT8nABURWR9ef3phQWQwDDRiBHwMrJy87OQsMEpickgwLBRyDDAayT5oBDAEbAlIGnrILFrWDORyIY4AdyS4FK9JyFGpoSnIqFmWZMTw720ZseCDeXUAkD2ZgHN1EL2dkE2l7dddsTvQgy3bJ-33TxmAY3e3lwO9s9YOYqGgUM0wTQMNgiJQocg4BAZlVvJg7Lw0bwqoYQComAAzACGAFcADYAFxYpKYaiRUhglQ4ACcMWYsY1MUdDPBligDh53JiBTdfhdOQoOGQQAAvJgAOyYTIA+ioAPZK8lMwkAI0JpIAFqrpGBoLkGLhiKUsmB4GhWFRaGhgfAXa6QvVwBxpVjyJoLlb2TjZQrlWqNVrdQ)



## PROJETO NO TINKERCAD
![WhatsApp Image 2025-07-03 at 12 28 19](https://github.com/user-attachments/assets/9f044a7b-a746-420a-9315-0b6ec314d7ee)

## VÍDEO DO PROJETO SENDO TESTADO
[![Assista ao vídeo no YouTube](https://img.youtube.com/vi/HnunIId9lDY/0.jpg)](https://youtu.be/HnunIId9lDY)

