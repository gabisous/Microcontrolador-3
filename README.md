# Microcontrolador-3
lista 3

Perguntas:
1: Qual a principal vantagem em utilizar uma interrupção ao invés de checar peri-
odicamente o status de uma GPIO, por exemplo.
A interrupção desvia a execução da CPU para uma Rotina de Interrupção, o fluxo do programa. Uma vez finalizado, as condições anteriores do processador são restauradas.
Ao usar as interrupções obtemos resultados mais rápidos, melhorando a eficiência do programa. 

2: Por que não é recomendável executar operações custosas e longas dentro de
uma rotina ISR?
Porque pode ocorrer um atraso no programa.
