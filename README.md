# Modelo Lotka-Volterra Trifásico para Dinâmica de Predação e Competição
Este projeto implementa um modelo Lotka-Volterra trifásico em Python para simular a dinâmica de predação e competição entre coelhos, castores e lobos. O objetivo é entender as interações e mudanças nas populações ao longo do tempo, considerando taxas de predação, competição e mortalidade. As simulações são visualizadas em gráficos que representam as populações individualmente, em pares e no ecossistema completo.

## Funcionalidades
Simulação de dinâmica populacional para três espécies (coelho, castor e lobo) com base em equações diferenciais.

## Gráficos de evolução das populações:
População de cada espécie individualmente.
Interação entre pares (coelho-castor, coelho-lobo, castor-lobo).
População total com as três espécies.

## Espécies
Coelhos: Taxa de crescimento na ausência de predadores, predação pelo lobo e competição por recursos com o castor.

Castores: Taxa de crescimento, predação pelo lobo e competição com os coelhos.

Lobos: Eficiência de conversão de presas em novos lobos, taxa de mortalidade natural e fatores externos de mortalidade.

## Parâmetros do Modelo

A: Taxa de crescimento dos coelhos na ausência de predadores.

B: Taxa de predação dos coelhos pelos lobos.

C: Taxa de competição entre coelhos e castores.

M: Taxa de crescimento dos castores.

N: Taxa de predação dos castores pelos lobos.

D, K: Eficiência de conversão de coelhos e castores em novos lobos.

G: Taxa de mortalidade dos lobos.

T: Taxa de mortalidade dos lobos por fatores externos.

## Visualização
Os gráficos resultantes mostram as dinâmicas das populações ao longo do tempo. Cada espécie é representada individualmente e em pares, mas apenas para visualização, todo o cálculo ainda é feito com as 3 espécies, com um gráfico adicional para a população total.

## Equipe
- Heitor Cordeiro
- Luiz Gustavo
- Marco Antônio
- Túlio Lira
